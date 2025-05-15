# MovieMate 🎬

MovieMate is a mobile application that allows users to discover and explore movies with real-time search, trending analysis, and a clean UI. Built using React Native, Expo, and Appwrite, this app offers a sleek experience and leverages modern tools like TypeScript and TailwindCSS.

## ✨ Features

- **Real-Time Movie Data**: Instantly fetch and display movie info using the TMDB API.
- **Trending Algorithm**: Tracks user searches to highlight the most popular movies.
- **Explore & Discover**: Home screen with curated lists and recommendations.
- **Search Functionality**: Find any movie with an advanced search UI.
- **Smooth UI/UX**: Tailwind-based modern design with responsive layout.
- **Appwrite Integration**: Backend-as-a-service for storing trending data and handling real-time updates.

## 💪 Tech Stack

**Frontend:**

- React Native  
- Expo  
- TypeScript  
- Tailwind CSS (NativeWind)  

**Backend:**

- Appwrite  
- TMDB API

## 🛠️ Setup Instructions

Follow these steps to run the project locally:

### 1. Prerequisites

Make sure the following tools are installed:

- [Node.js](https://nodejs.org/en)  
- [Git](https://git-scm.com/)  
- [Expo CLI](https://docs.expo.dev/get-started/installation/)  
- Expo Go app (on your mobile device)

### 2. Clone the Repository

```bash
git clone https://github.com/edadural/rn_movie_app.git
cd rn_movie_app
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Set Up Environment Variables

Create a `.env` file in the root directory and add your credentials:

```bash
EXPO_PUBLIC_MOVIE_API_KEY=your_tmdb_api_key
EXPO_PUBLIC_APPWRITE_PROJECT_ID=your_project_id
EXPO_PUBLIC_APPWRITE_DATABASE_ID=your_database_id
EXPO_PUBLIC_APPWRITE_COLLECTION_ID=your_collection_id
```
You can obtain these values from [TMDB](https://www.themoviedb.org/) and [Appwrite]([https://www.themoviedb.org/](https://cloud.appwrite.io/console/organization-65605eb9e463140f4bf1)).

### 5. Run the Project

```bash
npx expo start
```
Scan the QR code with the Expo Go app to launch the app on your device.

## 📺 Tutorial & Credits

This project is based on the YouTube tutorial by JavaScript Mastery:

- **[📹 Watch the Full Tutorial](https://www.youtube.com/watch?v=f8Z9JyB2EIE)**

## 📸 Screenshots

<p align="center">
  <img src="https://raw.githubusercontent.com/edadural/rn_movie_app/main/assets/images/1.png" alt="Image 1" width="200"/>
  <img src="https://raw.githubusercontent.com/edadural/rn_movie_app/main/assets/images/2.png" alt="Image 2" width="200"/>
  <img src="https://raw.githubusercontent.com/edadural/rn_movie_app/main/assets/images/3.png" alt="Image 3" width="200"/>
</p>
