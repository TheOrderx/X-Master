# 🚀 X-Master (v4.0)

X (Twitter) işlemlerinizi saniyeler içinde otomatize eden, modern arayüze sahip, yüksek kararlılık sunan gelişmiş bir tarayıcı eklentisidir. Algoritma dostu gecikme sistemleri, insan simülasyonu ve detaylı istatistik takibi ile hesabınızı güvenle büyütmenize yardımcı olur.

![X-Automation Banner](https://img.shields.io/badge/X--Automation-Pro--Bot-blue?style=for-the-badge&logo=twitter)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Version](https://img.shields.io/badge/Version-3.5-orange?style=for-the-badge)

## ✨ Öne Çıkan Özellikler

### 🤖 Gelişmiş Etkileşim Motoru (v3.5 Güncellemesi)
- **Toplu Döngü 2.0 (Bulk Loop):** Belirlenen sayıda tweet'i teker teker açar, mention'ları (yanıtları) beğenir ve otomatik olarak bir sonraki tweet'e geçer.
- **SPA & Navigasyon Desteği:** Twitter'ın Single Page Application yapısıyla tam uyumlu; sayfa yenilenmeden yapılan geçişleri algılar ve işleme devam eder.
- **Otomatik Sahip Etkileşimi:** Yanıtları beğenirken tweet sahibini (ana tweeti) de otomatik olarak beğenerek etkileşim kalitesini artırır.
- **Akıllı Akış Kontrolü:** Eğer bir akışta yeni tweet bulunamazsa, ayarlanabilir "Boş Akış Yenileme" sınırı uyarınca sayfayı otomatik tazeler.
- **Hassas Tıklama Teknolojisi:** MouseEvent yanında **PointerEvent** desteği ve butonların iç katmanlarına (SVG) erişim yeteneği ile %100 etkileşim başarısı.
- **Keşfet Bölümü Koruması:** "Daha fazlasını keşfet" alanını otomatik algılayarak önerilen (alakasız) tweetleri etkileşim dışı bırakır.

### 🧹 Profesyonel Temizlik Araçları
- **Toplu Takipten Çıkma:** Sizi takip etmeyenleri (Non-Followers) veya onaylı olmayan (Unverified) hesapları tek tıkla ayıklayın.
- **Her Şeyi Temizle:** Tüm tweetlerinizi, beğenilerinizi, yanıtlarınızı veya retweetlerinizi tek bir komutla toplu olarak temizleyin.
- **Beyaz Liste (Whitelist):** Korunmasını istediğiniz kullanıcıları ekleyin; bot onlara asla dokunmaz.
- **Akıllı Kelime Filtresi:** Belirlediğiniz anahtar kelimelerin (ör: "kazan", "takip et", "spam") geçtiği mentleri otomatik olarak atlayın.
- **🛡️ Gelişmiş Anti-Shadowban:** Belirlenen işlem sayısına ulaştığında (ör: 30 beğeni) botun otomatik olarak uyku moduna geçmesini (ör: 10 dk) sağlayarak X arayüzündeki radardan kaçın.

### 🛡️ Güvenlik ve Algoritma Dostu Yapı
- **İnsan Simülasyonu:** Rastgele gecikmeler, staggered tıklama (basma ve çekme arası süre) ve doğal kaydırma hareketleri ile bot tespitini engeller.
- **Maksimum Yaş Filtresi:** Sadece güncel içeriklerle etkileşim kurmak için saat bazlı tweet yaşı sınırlaması.
- **Sessiz Durdurma:** İşlemleri durdurduğunuzda hata vermeden temiz bir şekilde sonlanır.

### ⚡ Ultra Hızlı Takipçi Çekimi (Turbo Scrape v4.0)
- **Ultra Turbo Mod:** Takipçi listesini "ışık hızında" kaydırarak tarar. Listede zaten kayıtlı kişiler varsa 0.35 saniyede geçer, yeni kişi bulursa 1 saniyede okur.
- **Akıllı Bitiş Algılama:** İnternet yavaşladığında veya sayfa takıldığında yanlışlıkla "Bitti" demesini engelleyen akıllı sabır mekanizması.
- **Limit Kontrolü:** "Bir sorun oluştu" veya "Yeniden dene" butonlarını algılayıp otomatik olarak tıklar ve devam eder.

### 💾 Veritabanı ve Yedekleme (YENİ)
- **Tam Yedekleme:** Tek tıkla tüm ayarlarınızı, kara listenizi ve binlerce kişilik takipçi önbelleğinizi `.json` dosyası olarak bilgisayarınıza indirin.
- **Geri Yükleme:** İndirdiğiniz yedeği seçerek farklı bir tarayıcıda veya bilgisayarda kaldığınız yerden devam edin.
- **Limitsiz Depolama:** Chrome'un 5MB depolama limiti aşıldı, artık on binlerce takipçiyi veri kaybı yaşamadan saklayabilirsiniz.

### 📊 Modern Kontrol Paneli
- **Dashboard:** Şık, koyu temalı, cam morfizmli (glassmorphism) modern UI.
- **Canlı Loglama:** Botun yaptığı her işlemi, neden atladığını veya kaçta kaç ilerlediğini anlık olarak panelden görün.
- **Gelişmiş Ayarlar:** Kaydırma hızı, tıklama hızı, sayfa yenileme sınırı gibi tüm parametreleri kendinize göre optimize edin.

## 🛠️ Kurulum

1. Bu projeyi bilgisayarınıza indirin veya klonlayın.
2. Google Chrome tarayıcınızı açın ve `chrome://extensions/` adresine gidin.
3. Sağ üst köşedeki **"Geliştirici Modu"** (Developer Mode) seçeneğini aktif hale getirin.
4. **"Paketlenmiş eklenti yükle"** (Load Unpacked) butonuna tıklayın ve proje klasörünü seçin.
5. X.com (Twitter) sayfasını yenileyin ve dashboard üzerinden otomasyonunuzu başlatın!

## 📄 Lisans

Bu proje MIT Lisansı ile lisanslanmıştır.

---
*⚠️ **Feragatname:** Bu proje eğitim ve kişisel kullanım amaçlı geliştirilmiştir. Twitter'ın (X) kullanım koşullarına aykırı aşırı işlemler yapmak hesabınızın kısıtlanmasına veya askıya alınmasına neden olabilir. Kullanım sorumluluğu kullanıcıya aittir.*

---

# 🇬🇧 English Description

# 🚀 X-Master (v4.0)

An advanced browser extension that automates your X (Twitter) operations in seconds, featuring a modern interface and high stability. It helps you grow your account safely with algorithm-friendly delay systems, human simulation, and detailed statistics tracking.

## ✨ Key Features

### 🤖 Advanced Interaction Engine
- **Bulk Loop 2.0:** Opens a set number of tweets one by one, likes mentions (replies), and automatically moves to the next tweet.
- **SPA & Navigation Support:** Fully compatible with Twitter's Single Page Application structure; detects page transitions without reloading.
- **Automatic Owner Interaction:** Automatically likes the tweet owner (main tweet) when liking replies to improve interaction quality.
- **Smart Flow Control:** If no new tweets are found in a feed, it automatically refreshes the page according to the adjustable "Empty Flow Refresh" limit.
- **Precision Click Technology:** 100% interaction success with **PointerEvent** support alongside MouseEvent, accessing inner layers of buttons (SVG).
- **Explore Section Protection:** Automatically detects the "Discover more" area and excludes suggested (irrelevant) tweets from interaction.

### 🧹 Professional Cleaning Tools
- **Bulk Unfollow:** Unfollow non-followers or unverified accounts with a single click.
- **Clean Everything:** Bulk delete all your tweets, likes, replies, or retweets with a single command.
- **Whitelist:** Add users you want to protect; the bot will never touch them.
- **Smart Keyword Filter:** Automatically skip mentions containing keywords you define (e.g., "win", "follow back", "spam").
- **🛡️ Advanced Anti-Shadowban:** Puts the bot into sleep mode (e.g., 10 mins) automatically when a set number of operations (e.g., 30 likes) is reached to stay under the radar.

### 🛡️ Secure & Algorithm-Friendly Structure
- **Human Simulation:** Prevents bot detection with random delays, staggered clicking (time between press and release), and natural scrolling movements.
- **Max Age Filter:** Time-based tweet age limitation to interact only with current content.
- **Silent Stop:** Terminates cleanly without errors when you stop operations.

### ⚡ Ultra Fast Follower Scraping (Turbo Scrape v4.0)
- **Ultra Turbo Mode:** Scrapes the follower list at "light speed". Skips cached users in 0.35s and reads new ones in 1s.
- **Smart Finish Detection:** Intelligent patience mechanism preventing accidental "Finished" status during internet lags.
- **Limit Control:** Detects "Something went wrong" or "Retry" buttons and clicks them automatically to continue.

### 💾 Database & Backup (NEW)
- **Full Backup:** Download all your settings, blacklist, and cached followers list as a `.json` file with one click.
- **Restore:** Resume from where you left off on a different browser or computer by loading your backup.
- **Unlimited Storage:** Bypassed Chrome's 5MB storage limit; now store tens of thousands of followers without data loss.

### 📊 Modern Control Panel
- **Dashboard:** Stylish, dark-themed, glassmorphism modern UI.
- **Live Logging:** See every action the bot takes, why it skipped, or progress instantly from the panel.
- **Advanced Settings:** Optimize all parameters like scroll speed, click speed, page refresh limit to your liking.

## 🛠️ Installation

1. Download or clone this project to your computer.
2. Open Google Chrome and go to `chrome://extensions/`.
3. Enable **"Developer Mode"** in the top right corner.
4. Click **"Load Unpacked"** and select the project folder.
5. Refresh the X.com (Twitter) page and start your automation via the dashboard!

## 📄 License

This project is licensed under the MIT License.

---
*⚠️ **Disclaimer:** This project is developed for educational and personal use purposes. Performing excessive operations contrary to Twitter's (X) terms of use may cause your account to be restricted or suspended. Responsibility for usage belongs to the user.*
