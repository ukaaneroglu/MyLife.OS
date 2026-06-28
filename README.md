🌌 MyLife.OS

Kişisel hayat yönetimi, finans takibi, alışkanlık zinciri, proje yönetimi (Kanban) ve oyunlaştırmayı (Gamification) tek bir ekranda birleştiren, sunucusuz (serverless) ve %100 gizlilik odaklı modern web tabanlı kişisel işletim sistemi.

📌 Proje Hakkında

MyLife OS, günümüzde dağılmış olan üretkenlik araçlarını (Notion, Trello, Apple Sağlık, Finans uygulamaları) tek bir merkezde toplamak amacıyla geliştirilmiştir. "Premium Dark Mode" ve Glassmorphism tasarım diliyle inşa edilen uygulama, hiçbir veritabanı veya sunucu bağlantısı gerektirmez. Tüm veriler doğrudan kullanıcının kendi tarayıcısında (localStorage) şifrelenmeden ancak dışarıya kapalı bir şekilde saklanır.

🚀 Öne Çıkan Özellikler

🏆 Oyunlaştırma (Gamification): Su içtikçe, görev tamamladıkça veya odaklanma seanslarını bitirdikçe XP kazanın ve seviye atlayın.

🤖 Yapay Zeka Koçu: İçerisinde 20'den fazla yaşam senaryosuna (stres, uyku, motivasyon, ders programı) anında akıllı yanıtlar veren entegre bir sanal asistan bulunur.

🌦️ Gerçek Zamanlı Hava Durumu: Open-Meteo API kullanılarak seçtiğiniz şehrin (Ayarlardan değiştirilebilir) anlık hava durumunu getirir.

📊 Kişisel Finans & Bilanço: Gelir/gider takibi, net varlık hesabı ve Chart.js destekli harcama analizleri. Birikim hedeflerinizi bar grafikleriyle takip edin.

📋 Proje Panosu (Kanban): Sürükle-bırak mantığına sahip Yapılacaklar, Devam Edenler ve Tamamlananlar sütunlarıyla gelişmiş görev yönetimi.

🔥 Alışkanlık Takibi (Habits): Rutinlerinizi ekleyin, "zinciri kırmadan" serinizi büyütün. Son 14 günü GitHub tarzı mini ısı haritası (heatmap) ile görün.

⏱️ Derin Odak (Pomodoro): Görsel olarak zengin 25 dk çalışma / 5 dk mola sayacı.

🧠 İkinci Beyin & Günlük: Hızlı notlar alın, klasörleyin ve tarih/saat damgalı kişisel günlüğünüzü tutun.

🏋️ Sağlık ve Fitness: Antrenman günlüğü ve dinamik çizgi grafikli (Line Chart) kilo takibi.

🛠️ Teknolojiler & Mimari

Proje tek bir HTML dosyası mimarisine sahiptir ve tamamen Vanilla JavaScript ile yazılmıştır. Herhangi bir paket yöneticisine (npm) veya build aracına (Webpack/Vite) ihtiyaç duymaz.

Tasarım: Tailwind CSS (CDN)

İkonlar: FontAwesome 6 (CDN)

Grafikler: Chart.js (CDN)

Animasyonlar: Canvas-Confetti (CDN)

API Entegrasyonu: Open-Meteo (Hava durumu, Fetch API ile)

Veri Yönetimi: Tarayıcı Yerel Depolaması (window.localStorage)

🔒 Gizlilik ve Güvenlik (Offline First)

MyLife OS, "Offline First" ve "Privacy First" prensipleriyle çalışır.

Girilen finansal veriler, günlük yazıları veya özel hedefler hiçbir şekilde bir sunucuya veya buluta gönderilmez.

İnternet bağlantısı olmasa bile uygulamanın tüm temel modülleri çalışmaya devam eder (Hava durumu API'si hariç).

Yedekleme: Ayarlar modülünden tüm verilerinizi bir .json dosyası olarak bilgisayarınıza/telefonunuza indirebilir ve dilediğiniz zaman başka bir cihazda içe aktarabilirsiniz (Export/Import).

💻 Nasıl Çalıştırılır?

Hiçbir kurulum gerektirmez!

Bu depoyu (repository) indirin veya mylife.html dosyasını kopyalayın.

Dosyaya çift tıklayarak modern bir tarayıcıda (Chrome, Edge, Safari, Brave vb.) açın.

Kullanmaya başlayın!

(İsteğe bağlı: Projeyi tüm cihazlarınızdan erişilebilir yapmak için Github Pages, Netlify veya Vercel üzerinden anında ve ücretsiz bir şekilde yayınlayabilirsiniz (Deploy).)


Bu proje kişisel üretkenliği sanatla buluşturmak için tasarlanmıştır.
