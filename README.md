# SmartCart — a mobile smart shopping cart system

## 📝 About the project

SmartCart is a mobile application that facilitates the shopping process in regular stores.
Scan the barcode of the product through the camera and it will be automatically added to your virtual shopping cart.
All prices and quantity are always under control!

---

## ❓ What are we solving

The problems of regular shopping:

* it is difficult to keep track of the total amount,
* it is easy to forget how many items have already been taken,
* queues at the checkout waste time,
* unexpected amount at the checkout.

**SmartCart** helps you shop consciously and saves you time.

---

## 🎯 Main functionality

* 📷 Barcode scanning
* 🛒 Automatic adding of products to the basket
* 🔁 Repeat scan — increase the number of
* ➕➖ Manual quantity management
* 💰 Automatic calculation of the total amount
* 🎨 User -friendly and minimalistic interface
* 💳 Preparation for future payment integration

---

## ⚙️ Technologies used

| Component | Technologies |
| ------------- | ------------------------------ |
| Interface | Jetpack Compose |
| Language | Kotlin |
| Scanner | Google ML Kit Barcode Scanning |
| Camera | Android CameraX |
| Database | Firebase Realtime Database |
| Asynchrony | Kotlin Coroutines |

---

## 🚀 Project launch

1. **Clone the repository:**

   ```bash
   git clone https://github.com/D-Arshad-Dazai-Dimash/SmartCart
   ```
2. Open the project in **Android Studio**
3. Make sure that Gradle is successfully synchronized
4. Add the `google-services' file.json` to the `app/` folder
5. Launch the project on your device or emulator
6. Allow access to the camera

> Requires an internet connection to work with Firebase

---

## 🕹 How to use

* Open the app and the camera will start
* Hover over the barcode and the product will be added
* Repeated scanning increases the number of
* In the shopping cart you can:

  * change the quantity
  * delete products
* The total amount is updated automatically
* The payment screen is still a blank

---

## , Testing

* Android Studio Emulator
* Testing on real devices

---

## ⚠️ Restrictions

* Low lighting impairs speech recognition
* Android support from version **8.0 / API 26**
* Online payment has not been implemented
* Firebase works only when the Internet is available

---

## 👥 Team

| Member |
| ----------------- |
| Dimash Yeskendir | 
| Olzhas Musakhan   | 
| Asylzhan Bitore   |
| Ayan Amantay      |
---
