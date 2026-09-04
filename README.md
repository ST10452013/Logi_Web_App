# LogiCost SA – Supply Chain & Costing System

LogiCost SA is a complete logistics and supply chain management platform designed for South African manufacturing SMMEs. It combines a web-based dashboard and a native Android application to help businesses track inventory, manage deliveries, optimize routes, and calculate production costs in real-time — even during load shedding.



 🌟 Key Features

 Web Dashboard (PHP/MySQL)
- User authentication with role-based access control
- Inventory management with barcode scanning
- Supplier and customer database management
- Real-time delivery tracking and route optimization
- Automated costing engine (landed cost, BOM, profitability)
- Load shedding alerts and offline mode support
- VAT reporting and customizable dashboards

 Mobile App (Kotlin/Android)
- Real-time GPS tracking for drivers (Google Maps API)
- Barcode scanning for package verification
- Offline mode for areas with poor connectivity
- Biometric authentication (fingerprint/face unlock)
- Push notifications (Firebase Cloud Messaging)
- Photo capture for proof of delivery
- Digital signatures for delivery confirmation
- Driver route optimization



 Technology Stack

| Component | Technologies |
|-----------|--------------|
| Backend (Web) | PHP 8.2+, MySQL, Apache/Nginx |
| Frontend (Web) | HTML5, CSS3, JavaScript, Bootstrap 5, jQuery, Chart.js |
| Android App | Kotlin, Android Studio, MVVM, Jetpack Components |
| Mobile Database | Room (SQLite) |
| API Communication | Retrofit, Gson, RESTful APIs |
| Push Notifications | Firebase Cloud Messaging (FCM) |
| Maps & GPS | Google Maps API |
| Architecture | MVC (Web), MVVM (Mobile) |



 Folder Structure
LogiCostSA/
├── website/
│ ├── config/
│ │ └── database.php
│ ├── includes/
│ │ ├── header.php
│ │ ├── footer.php
│ │ └── navbar.php
│ ├── assets/
│ │ ├── css/
│ │ ├── js/
│ │ └── uploads/
│ ├── index.php
│ ├── login.php
│ ├── register.php
│ ├── dashboard.php
│ ├── inventory.php
│ ├── deliveries.php
│ ├── route-map.php
│ ├── load-shedding.php
│ ├── offline-mode.php
│ ├── profile.php
│ ├── contact.php
│ └── logout.php
│
├── mobile-app/
│ ├── app/
│ │ ├── src/
│ │ │ ├── main/
│ │ │ │ ├── java/com/logiscost/
│ │ │ │ │ ├── activities/
│ │ │ │ │ ├── adapters/
│ │ │ │ │ ├── fragments/
│ │ │ │ │ ├── models/
│ │ │ │ │ ├── repository/
│ │ │ │ │ ├── utils/
│ │ │ │ │ └── viewmodel/
│ │ │ │ ├── res/
│ │ │ │ │ ├── layout/
│ │ │ │ │ ├── drawable/
│ │ │ │ │ ├── values/
│ │ │ │ │ └── menu/
│ │ │ │ └── AndroidManifest.xml
│ │ └── build.gradle
│ └── README.md
│
├── database/
│ └── database.sql
│
└── README.md

Team Members
Name	Student Number	Role
Lethabo Mdhluli	ST10447479	Project Manager / App Developer
Tumelo Matlou	ST10452013	Business Analyst / Website Developer
Modise Mashishi	ST10447481	Software Developer / Presenter
