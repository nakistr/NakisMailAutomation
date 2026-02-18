# 📧 NakisMailAutomation (Spam-Savar)

[TR] Oyun geliştiricileri için tasarlanmış, spama düşmeyi engelleyen profesyonel toplu mail otomasyon sistemi.
[EN] A professional bulk email automation system designed for game developers to reach influencers without hitting spam filters.


### 🚀 Proje Hakkında
Bu proje, özellikle bağımsız oyun geliştiricilerinin (indie developers) oyunlarını tanıtmak amacıyla yayıncılara ve basın mensuplarına güvenli bir şekilde toplu mail gönderebilmesi için geliştirilmiştir. Sistem, maillerin spama düşmesini engellemek için profesyonel API entegrasyonları ve arka plan görevleri kullanır.

### ✨ Özellikler
* **Toplu Gönderim:** Tek panelden yüzlerce alıcıya aynı anda erişim.
* **Akıllı Kişiselleştirme:** `{{Ad}}` yer tutucusu ile her alıcıya kendi ismiyle hitap etme.
* **Arka Plan Görevleri:** Hangfire entegrasyonu sayesinde mail kuyruğu yönetimi ve zamanlama.
* **Takip Paneli (Dashboard):** Gönderim geçmişini ve durumunu izleyebileceğiniz kullanıcı dostu arayüz.
* **Güvenli Çıkış:** Brevo (Sendinblue) API üzerinden yüksek teslimat oranı.

### 🛠 Teknolojiler
* **Framework:** ASP.NET Core 8.0 MVC
* **Veritabanı:** SQL Server & Entity Framework Core
* **Mail Servisi:** Brevo API
* **Görev Yönetimi:** Hangfire


### 🚀 About the Project
This project is developed for game developers to send their press releases and keys to influencers and press members safely. The system utilizes professional API integrations and background processing to ensure high deliverability and avoid spam folders.

### ✨ Features
* **Bulk Emailing:** Reach hundreds of recipients simultaneously from a single dashboard.
* **Smart Personalization:** Use `{{Name}}` placeholders to address each recipient by their name.
* **Background Tasks:** Queue management and scheduling powered by Hangfire.
* **User Dashboard:** A clean UI to track your mailing history and status.
* **High Deliverability:** Integration with Brevo (Sendinblue) API for reliable mail delivery.

### 🛠 Tech Stack
* **Framework:** ASP.NET Core 8.0 MVC
* **Database:** SQL Server & Entity Framework Core
* **Email Service:** Brevo API
* **Task Management:** Hangfire

---

## ⚙️ Kurulum / Setup

1. **[TR]** `appsettings.json` dosyasındaki `ConnectionStrings` ve `BrevoSettings` alanlarını kendi bilgilerinizle güncelleyin.
2. **[EN]** Update `ConnectionStrings` and `BrevoSettings` in the `appsettings.json` file with your own credentials.
3. **[TR]** Package Manager Console üzerinden `Update-Database` komutunu çalıştırın.
4. **[EN]** Run the `Update-Database` command via the Package Manager Console.
