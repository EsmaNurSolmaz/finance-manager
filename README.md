<p float="left">
  <img src="./client/assets/screenshots/IMG_4112.PNG" alt="Image 1" width="250" />
  <img src="./client/assets/screenshots/IMG_4113.PNG" alt="Image 2" width="250" />
  <img src="./client/assets/screenshots/IMG_4114.PNG" alt="Image 3" width="250" />
  <img src="./client/assets/screenshots/IMG_4115.PNG" alt="Image 4" width="250" />
  <img src="./client/assets/screenshots/IMG_4116.PNG" alt="Image 5" width="250" />
  <img src="./client/assets/screenshots/IMG_4117.PNG" alt="Image 6" width="250" />
</p>


# Finance Manager Project

Finance Manager is a modern and user-friendly mobile application built with React Native (Expo) that helps users track their daily and monthly financial activities. The app allows you to record income and expenses, view categorized spending, and visualize your financial status through interactive charts. Designed with a clean interface and smooth animations, the app aims to simplify budget tracking for everyday use.

## Features

- Add income and expense entries easily
- Categorize transactions for better analysis
- View total balance, total expenses, and remaining monthly budget
- Category-based spending breakdown
- Periodic financial summary
- Interactive charts for visual insights (Pie charts)
- Save important financial notes (e.g., goals, reminders, bills, saving targets)
- View, edit, or delete notes
- Set reminders for due bills, payment dates, or savings milestones
- View real-time currency exchange rates (USD, EUR, GBP, vb.)
- Auto-refresh or manual refresh options
- Modern and clean interface


## Technologies
- **Frontend:** React Native, Context API, Expo
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT
- **UI:** CSS, Modern components
- Currency API 


This project consists of two main parts:

- **client/** — React Native Expo-based mobile application  
- **server/** — Node.js backend API

---

## Client (Mobile Application) — Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the app:

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a:

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)  
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)  
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)  
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo  

⚠️ **This is a mobile application, so some features may not work properly in a web browser. Please test the app using Expo Go, an Android Emulator, or an iOS Simulator.**

---

## Server (Backend API) — Getting Started

1. Navigate to the server directory:

   ```bash
   cd server
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the server:

   ```bash
   node server.js
   ```

---

## Project Structure

```
/client     # React Native application code  
/server     # Backend API code  
```

---

## Additional Notes

- Make sure your backend server is running before testing features in the client app that require API calls.
- Update environment variables (e.g., `.env` files) as needed for database connections and API keys.

---

## Contact

For any questions or inquiries, please contact:

- **Email:** esmanursolmaz@outlook.com