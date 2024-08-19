# Aicom4Health

Bu proje, React kullanılarak geliştirilmiş bir Hava Kalitesi ve POI Yönetim Uygulamasıdır. Kullanıcıların hava kalitesi verilerini görüntülemesine, ilgi noktalarını (POI) yönetmesine ve harita üzerinden çeşitli etkileşimler gerçekleştirmesine olanak tanır. Uygulama aynı zamanda kullanıcı kimlik doğrulamasıyla korunan sayfalar içerir.

Temel Özellikler:
Kullanıcı Giriş ve Kimlik Doğrulama:

Kullanıcılar giriş yaparak sisteme erişebilir.
Kimlik doğrulaması yapılmış kullanıcılar için withAuth.js fonksiyonu ile korunan sayfalara erişim sağlanır. Eğer kullanıcı giriş yapmamışsa, giriş sayfasına yönlendirilir​(withAuth).
Navigasyon:

Proje React Router kullanarak sayfalar arasında geçiş yapmayı sağlar. Giriş yaptıktan sonra kullanıcı, harita, POI, kullanıcı, hava kalitesi ve istatistikler gibi bölümlere erişebilir​(App).
App.js dosyası, tüm rotaları yönetir ve her rota için ilgili bileşenleri render eder.
Harita ve POI Yönetimi:

Kullanıcılar, harita üzerinde POI ekleyebilir, güncelleyebilir ve yönetebilir.
Harita ve POI yönetimi için Leaflet kullanılır ve haritada tıklanarak POI bilgileri alınabilir​(MapContainer).
Hava Kalitesi Verisi:

Hava kalitesi verileri grafikler ile kullanıcıya sunulur. LineChart bileşeni ile verilerin görsel olarak takibi sağlanır​(AirQualityChart).
Kullanıcı ve İstatistik Yönetimi:

Uygulama, kullanıcıları listeleme ve yönetme özellikleri sunar​(UserContainer).
Ayrıca, kullanıcıların istatistikleri izleyebilmesi için istatistik ekranı mevcuttur​(Statistics).
Kullanılan Teknolojiler:
React
React Router
Leaflet (Harita ve POI Yönetimi)
MUI (Kullanıcı Arayüzü Bileşenleri)
