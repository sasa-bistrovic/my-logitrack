# LogiTrack iOS & Android Build

This repository contains **only the compiled app files** for iOS and Android.  

- 🍏 **iOS:** The IPA file has been tested on **iPhone 14 Pro running iOS 16** and can be found inside **LogiTrack-ipa.zip**.  
- 🤖 **Android:** The APK file (**app-release.apk**) has been tested on **Android 15, Samsung Galaxy A54 5G**.  

🌍 The app is fully functional and can also be used via the web interface:  
[https://logitrack.expense-tracking.com](https://logitrack.expense-tracking.com)

> ⚠️ **Note:** The source code is not included in this repository.  
If you need access to the source code, I can provide the **Java Spring Boot backend** and the **Expo Go application** which works on **iOS, Android, and web**.  

---

### 🚚 About the Expo Go Application

The **Expo Go app** allows transporters to create invoices and set transport prices using coefficients based on cubic meters and kilograms.  

- 📦 The **shipper (orderer)** specifies the weight and volume of the goods to be transported, from pickup to delivery destination.  
- 🚛 The app finds the **nearest transporter vehicles** to the pickup location.  
- 💰 Based on the transporter’s coefficients, the app **automatically calculates the transport cost** when creating an order.  
- 🧾 The shipper must also **generate an invoice** in the app.  
- ✅ The transporter **accepts the shipment** (order) to complete the process.  

🔑 The application integrates with **Google API OAuth** for authentication and 🗺️ **Google Maps API** for route and location services.  

---

📧 Please contact me at: **sasa.bistrovic@gmail.com** for access to the source code.