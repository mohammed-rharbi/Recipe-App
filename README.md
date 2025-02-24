# 🍽️ Pepe Nero Recipe App

Welcome to **Pepe Nero Recipe App**! This mobile application helps users explore delicious recipes, Users can browse meals, view detailed recipes, and even save their favorites for later. 🚀

## 📌 Features

- 🔍 **Browse Recipes** – View a list of recipes.
- 📖 **Recipe Details** – Get step-by-step instructions, ingredients, and images.
- ❤️ **Save Favorites** – Bookmark recipes Favorites Recipes .
- ➕ **Add Recipes** – Users can create and Manage their own recipes.
- 🎨 **Smooth UI & Animations** – A user-friendly interface with animations.
- 📱 **React Native Navigation** – Seamless navigation between screens.

---

## 🛠️ Tech Stack

- **Frontend:** React Native (CLI)
- **Navigation:** React Navigation
- **State Management:** Redux
- **Storage:** AsyncStorage
- **API Calls:** Axios
- **Database:** Json-server
- **Testing:** Jest / React Native Testing Library

---

## 📂 Project Structure

```
PepeNeroRecipeApp/
│── src/
│   ├── components/       # Reusable UI components
│   ├── screens/          # App screens (Home, Details, Favorites, AddRecipe)
│   ├── services/         # API handling logic
│   ├── storage/          # Local storage logic
│   ├── navigation/       # App navigation configuration
│   ├── assets/           # Images, icons, etc.
│── App.js                # Root component
│── package.json          # Dependencies & scripts
│── README.md             # Documentation
```

---

## 🚀 Installation & Setup

### Prerequisites
Make sure you have the following installed:
- Node.js & npm/yarn
- React Native CLI
- Android Studio (for emulator) or a physical device

### Steps to Run Locally
```bash
# Clone the repository
git clone (https://github.com/mohammed-rharbi/Recipe-App/)
cd recipe-app

# Install dependencies
yarn install  # or npm install

# Start the Metro Bundler
yarn start  # or npm start

# Run on an Android device/emulator
yarn android  # or npm run android
```

---

## 🏗️ Features Breakdown

### 📌 **1. Fetch Recipes from API**
- Display a list of recipes with images and titles.
- Implement error handling and loading indicators.

### 📌 **2. Recipe Details Screen**
- Show ingredients and preparation steps.
- Include an image and a "Save to Favorites" button.

### 📌 **3. Save Favorite Recipes**
- Store recipes using AsyncStorage.
- Display saved recipes on a separate "Favorites" screen.

### 📌 **4. Add a New Recipe**
- Allow users to enter a title, ingredients, and steps.
- Save user-created recipes locally.

### 📌 **5. Search & Filter (Optional Enhancements)**
- Implement a search bar to find recipes.
- Add category-based filtering.

---

## ✅ Testing
Run unit tests to ensure stability:
```bash
yarn test  # or npm test
```

---



## 🤝 Contribution
Feel free to contribute! Fork the repo, create a branch, and submit a PR. 


🚀 **Happy Cooking with Pepe Nero Recipe App!** 🍽️
