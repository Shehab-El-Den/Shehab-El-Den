# Hi, I'm Shehab El-Den Ehab 👋

<div align="center">

### Senior Flutter Developer · Native video & DRM · Payments · Realtime · CI/CD

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shehab-el-den-ehab-5193b32b0)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shehabeldenehab@gmail.com)

</div>

---

## About me

I'm a Senior Flutter Developer at **Incube Venture Studio**. I've been shipping production Flutter apps since 2021, mostly in streaming, marketplaces, mobility and social.

- 🎞️ Native players and decoders
- 💰 Payments that must never double-charge
- 💬 Realtime chat
- 🚀 Test suites and pipelines that let a small team release every week

- 📱 **19+ published apps** on Google Play and the App Store
- 🎬 **Native video:** an ExoPlayer/AVPlayer DRM player with PiP, AirPlay and Cast, plus a decoder-aware reels engine
- 💳 **Payments:** Stripe, PayPal, Mollie, Pay.nl, Checkout, Tap, StoreKit and Play Billing
- 🧪 **Testing:** 600+ test files written in 2026, including live API contract tests
- ⚙️ **CI/CD:** multi-flavor pipelines with GitHub Actions, Fastlane and Xcode Cloud
- 🧩 **Backend when needed:** Laravel 12 + Livewire, Node.js, Supabase and Firebase

---

## Featured apps

### 🎬 Kayef: places, video reels and offers
A video-first discovery app. Users browse places through short videos and redeem offers by QR.
- Rebuilt reels playback around an **LRU controller pool, serial decoder init and a decoder budget**. Feeds no longer exhaust hardware decoders on low-end Android devices.
- Offers wallet with QR redemption, lucky draws and a lucky wheel. A companion merchant app scans and redeems.
- Migrated to **feature-first MVVM with Riverpod**, with 140+ test files including live API contract tests.
- **4-flavor CI/CD:** GitHub Actions, Fastlane and Xcode Cloud.

**Top features:** 📹 Short video reels of places · 🎁 Offers wallet with QR redemption · 🍀 Lucky draws · 🔗 Shareable deep links · 🏪 Merchant app for scanning and redeeming offers

**Tech:** Flutter · Riverpod · MVVM · ExoPlayer (native) · Deep links · GitHub Actions · Fastlane
[Google Play]({{https://play.google.com/store/apps/details?id=com.incube.kayefapp}}) · [App Store]({{https://apps.apple.com/eg/app/id6608980529}})

---

### 📺 Seen: video streaming (OTT)
- Built a **native DRM player** (ExoPlayer/Media3 + AVPlayer platform views) with FairPlay fallback, PiP on iOS and Android, AirPlay, Cast and Now Playing.
- Added HLS/403 recovery and a DRM session cache, so playback survives expired tokens and flaky networks.
- Ran a full architecture refactor: core/shared/features layers and auto-disposed Riverpod. It removed **about 281k lines** of dead files and assets.
- Subscriptions with StoreKit and Play Billing restore. 4-flavor CI/CD.

**Top features:** 🔐 DRM-protected streaming · 🖼️ Picture-in-Picture · 📺 AirPlay & Chromecast · 🎛️ Lock-screen playback controls · 💳 Subscriptions with restore purchases

**Tech:** Flutter · Kotlin/Swift platform views · DRM · Riverpod · StoreKit · Play Billing
[Google Play]({{https://play.google.com/store/apps/details?id=com.incube.seen2}}) · [App Store]({{https://apps.apple.com/eg/app/id6737268389}})

---

### 💬 Zefaaf: matchmaking platform (33 languages)
- **Realtime chat** on Laravel Reverb: typed events, read receipts, presence, groups, call logs and push deep links.
- **Payments:** Stripe, PayPal, Mollie, Pay.nl and Rewaq, plus App Store offer codes and VIP plan gating.
- Rebuilt onboarding, OTP signup, home and stories for 2.0.
- **420 test files** on shared harnesses. Moved from `.env` to compile-time flavors with GitHub Actions and Fastlane.

**Top features:** 💬 Live chat with seen and online status · 👥 Group and support chats · 📖 Stories and success stories · 📲 OTP signup · 👑 VIP plans · 🌍 33 languages

**Tech:** Flutter · WebSockets (Reverb) · Payments · i18n/RTL · Fastlane
[Google Play]({{https://play.google.com/store/apps/details?id=com.zefaaf.zefaaf}}) · [App Store]({{https://apps.apple.com/eg/app/id6747707022}})

---

### ⚽ Squad & Squad Player: football scouting social apps
I'm the sole developer of both apps.
- Video reels and a share sheet.
- Deep links: App Links, associated domains and deferred routing, all covered by tests.
- Competitions with score and penalty predictions.
- Video compression with **2 MB chunked, resumable uploads**.

**Top features:** 🎥 Football video reels · 🏆 Competitions with score and penalty predictions · ⬆️ Reliable video upload · 🔗 Share and deep links · 🔔 Push notifications

**Tech:** Flutter · Deep links · Video upload pipeline · FCM
Squad: [Google Play]({{https://play.google.com/store/apps/details?id=com.mohamed_helicopter.squad}}) · [App Store]({{https://apps.apple.com/eg/app/id6756811939}})

Squad Player: [Google Play]({{https://play.google.com/store/apps/details?id=com.mohamed_helicopter.squad_player}}) · [App Store]({{https://apps.apple.com/eg/app/id6756811939}})

---

### 🚌 Meshwar El Assema: bus-subscription platform
I built the full system: a Laravel backend plus two Flutter apps.
- **Backend (Laravel 12 + Livewire):**
  - booking engine with prorated add-seats, vacations and date-scoped cancellations
  - server-timed trip start and end
  - targeted push notifications
  - Livewire admin panel
  - 26 feature tests
- **Passenger app:** book seats, take vacations, cancel days, pick a university and get route suggestions.
- **Supervisor app:** start and end trips against server-time countdowns, live occupancy per trip, booking reports and GPS-checked stops.

**Top features:** 💺 Seat booking and subscriptions · 🏖️ Vacations and day cancellations · 🎓 University and route suggestions · ⏱️ Server-timed trips · 📊 Live occupancy and reports

**Tech:** Flutter · Laravel 12 · Livewire · REST APIs · FCM · GPS
Passenger: [Google Play]({{https://play.google.com/store/apps/details?id=tech.brmja.meshwarapp}}) · [App Store]({{https://apps.apple.com/eg/app/id6782609278}})

Supervisor: [Google Play]({{https://play.google.com/store/apps/details?id=tech.brmja.meshwar.driver}}) · [App Store]({{https://apps.apple.com/eg/app/id6782851511}})
---

### 🛒 4YouMart: grocery marketplace
- Catalog and checkout UX for the customer app on mobile and web.
- Backend work: idempotent bulk import, POS barcode, stock-in, profit-margin reports, hardened database access and automated SSH deploys.

**Top features:** 🛍️ Product catalog and search · 🛒 Smooth checkout · 🌐 Mobile and web · 🏷️ Barcode-based stock management · 📈 Profit reports

**Tech:** Flutter · Laravel · GitHub Actions
[Google Play]({{https://play.google.com/store/apps/details?id=com.forUMart.forUMart}})
---

### 🏪 Albiaa: multi-vendor marketplace
- Two apps: a **customer app** with wallet and cashback, and a **vendor app** for orders and inventory.
- Governorate-based delivery zones across the app and the Laravel API.
- Returns, order push notifications, and Bluetooth receipt printing for vendors.
**Top features:** 🏬 Multi-vendor marketplace · 💰 Wallet with cashback · 🚚 Real-time order tracking · 📍 Delivery zones by governorate · ↩️ Returns · 🌍 4 languages (RTL)
 
**Tech:** Flutter · GetX · Laravel · FCM · 4 languages (RTL)
🛍️ **Customer app:** [Google Play](https://play.google.com/store/apps/details?id=com.mohamed_helicopter.albaiaa) · [App Store](https://apps.apple.com/eg/app/%D8%A7%D9%84%D8%A8%D9%8A%D8%A7%D8%B9/id6749823719)  
🏪 **Vendor app:** [Google Play]({{https://play.google.com/store/apps/details?id=com.mohamed_helicopter.albaiaavendors}}) · [App Store]({{https://apps.apple.com/eg/app/id6750769926}})
 
---
 
### 🧠 Nawaa (formerly Amlood): mental health consultations
- Session booking with the Checkout payment gateway and OTP auth.
- Two apps: a **client app** for booking sessions and a **consultant app** with wallet, biometric login and availability management.
- Crashlytics with a network interceptor that flags any API slower than 3 seconds.
**Top features:** 📅 Book sessions with specialists · 💳 Secure online payment · 📲 OTP login · 🔔 Appointment notifications · 🔒 Biometric login for consultants
 
**Tech:** Flutter · BLoC · Firebase · Checkout
🧑 **Client app:** [Google Play](https://play.google.com/store/apps/details?id=com.amlood.app) · [App Store](https://apps.apple.com/eg/app/id6624304969)  
🩺 **Consultant app:** [Google Play]({{https://play.google.com/store/apps/details?id=com.amlood.consultant}}) · [App Store]({{https://apps.apple.com/eg/app/id6754966302}})
 
---
 
## 🧩 Backend work
 
When an app needs it, I build or extend the backend myself.
 
| Project | Stack | What I built |
|---|---|---|
| 🚌 **Meshwar El Assema** | Laravel 12 · Livewire | Booking engine (prorated seats, vacations, date-scoped cancellations), server-timed trips, targeted push, Livewire admin panel, 26 feature tests |
| 🛒 **4YouMart** | Laravel · GitHub Actions | Idempotent bulk product import, POS barcode and stock-in, profit-margin report, hardened database access, automated SSH deploys |
| 🏪 **Albiaa** | Laravel 10 | Governorate-based delivery zones API, order status notifications, returned-items flow |
| 🎓 **Campus guide CMS** | Supabase · Flutter Web | Content dashboard with row-level security (RLS), media management and bilingual chatbot Q&A, powering a companion mobile app |
 
**Backend skills:** REST API design · Laravel (Eloquent, Livewire, Reverb) · Supabase (Postgres, RLS) · Firebase · Node.js · Feature testing · CI/CD deploys
 
---
 
## 📂 More work
 
<!-- For each link cell: paste the store link as [Download](URL), write — if the app is not on that store, or "Not published" if it is not released yet. -->
 
| App | What it is | Highlights | Google Play | App Store |
|---|---|---|---|---|
| 🏷️ **Alsemsar** | Classifieds marketplace | Phone + OTP login rewrite, cleaned-up codebase without ads and IAP | [Google Play](https://play.google.com/store/apps/details?id=com.mohamed_helicopter.alsemsar) | - |
| 📺 **Seen TV** | Streaming app for TV (React Native) | Moved releases off EAS to Gradle and the Play Developer API; environment-based config | [Google Play] (https://play.google.com/store/apps/details?id=com.incube.seen.tv) | Not published |
| 🎓 **Signify (campus guide)** | University campus guide app + CMS | Supabase dashboard with RLS, media and bilingual chatbot Q&A | {{SIGNIFY_PLAY}} | {{SIGNIFY_APPSTORE}} |
| 🔎 **InstaSearch** | Branch and service finder | Offline analytics queue with batched sending; branch-aware maps | {{INSTASEARCH_PLAY}} | {{INSTASEARCH_APPSTORE}} |
| 🛍️ **El Wakeel** | E-commerce app | Real-time chat, barcode scanning, speech-to-text search, Google Maps delivery tracking | [Google Play](https://play.google.com/store/apps/details?id=com.mohamed_helicopter.almandub) | [App Store](https://apps.apple.com/eg/app/%D8%B4%D8%B1%D9%83%D8%A9-%D8%A7%D9%84%D9%88%D9%83%D9%8A%D9%84/id6751055906) |
| 💼 **GM ERP** | Enterprise resource planning | Dart Isolates for **70% faster** data processing; PDF generation and barcode scanning | [Google Play](https://play.google.com/store/apps/details?id=com.ashalpos.gmerp) | — |
| 🚗 **Click Car Care** | Car service booking | Map-based booking, OTP login, voice-to-text service requests (mentored the team) | [Google Play](https://play.google.com/store/apps/details?id=com.clickcarcare.clickcarcare) | [App Store](https://apps.apple.com/eg/app/id6775898329) |
| 🔄 **Tabadil** | Item exchange marketplace | Item matching and real-time availability | [Google Play](https://play.google.com/store/apps/details?id=com.tabadil.app.tabadil) | — |
| 💄 **Axel Cosmetics** | Cosmetics e-commerce | UI fixes, Apple Sign-In, published to both stores | [Google Play](https://play.google.com/store/apps/details?id=com.ashalpro.axelcosmetics) | - |
 
---
 
## Tech stack
 
**Mobile:** Flutter · Dart · Riverpod · BLoC · GetX · Provider · Clean Architecture · MVVM · Isolates
**Native:** Kotlin · Swift · ExoPlayer/Media3 · AVPlayer · Platform views · Notification Service Extension
**Backend:** Laravel (Livewire, Reverb) · Node.js · Supabase · Firebase · REST · WebSockets
**Quality & delivery:** Unit, widget and contract tests · GitHub Actions · Fastlane · Xcode Cloud · Crashlytics
 
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Fastlane](https://img.shields.io/badge/Fastlane-00F200?style=flat-square&logo=fastlane&logoColor=black)
 
---
 
## Let's connect
 
📧 [shehabeldenehab@gmail.com](mailto:shehabeldenehab@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/shehab-el-den-ehab-5193b32b0) · 📍 Cairo, Egypt (remote)
