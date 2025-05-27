Hava Durumuna Göre Kıyafet Öneri Sistemi

Bu proje, kullanıcının yaşadığı şehirdeki güncel hava durumuna, cinsiyetine ve kıyafeti kullanacağı amaca göre en uygun kıyafet önerilerini sunan bir sistemdir. Python ile geliştirilmiş olup, Random Forest algoritması, hava durumu API'si ve Gradio arayüzü ile entegre çalışmaktadır.

Proje Özeti:

-Gerçek zamanlı hava durumu verileri WeatherAPI üzerinden alınır.

-Kullanıcının girdiği bilgiler doğrultusunda (şehir, cinsiyet, kullanım amacı) model girdileri oluşturulur.

-Temizlenmiş ve etiketlenmiş moda veri seti kullanılarak üç ana kategori (üst giyim, alt giyim, ayakkabı) için ayrı Random Forest modelleri eğitilir.

-Her bir kategori için kullanıcıya uygun kıyafet türü önerilir.

Kullanılan Teknolojiler:

-Python

-Pandas, NumPy

-Scikit-learn (RandomForestClassifier)

-Gradio (Arayüz geliştirme)

-WeatherAPI (Gerçek zamanlı hava verisi)

Makine Öğrenmesi Yöntemi:

Proje kapsamında, Random Forest sınıflandırma algoritması kullanılmıştır. Kıyafet önerileri üç ana kategoriye ayrılmış ve her biri için ayrı model eğitilmiştir:

-Topwear (T-shirt, Sweatshirt, Ceket vb.)

-Bottomwear (Pantolon, Etek, Şort vb.)

-Footwear (Spor ayakkabı, Bot, Sandalet vb.)

Model girdi değişkenleri:

-Cinsiyet

-Mevsim

-Kullanım amacı

-Hissedilen sıcaklık aralığı
