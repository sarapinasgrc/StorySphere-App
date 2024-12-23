# StorySphere - Android PDF App

In collaboration with Gabriela Marín and Afina Nurova.

StorySphere is an Android app implemented using Kotlin. This app allows users to easily store and read their PDF files, organize their digital library, and discover new books. Additionally, StorySphere integrates features like geolocation to find nearby libraries, Google Books integration for exploring and purchasing books, a review system for reflecting on readings, and a database using FireBase.

---

## Description

StorySphere was developed for the subject of Mobile Applications with the goal of simplifying the reading of PDF ebooks on Android devices. Users can store, read, and organize their PDF books, discover new books through Google Books integration, and find nearby libraries and bookstores using geolocation. 

---

## Main Features

- **Persistent Storage**: Users can store their PDF books, reviews, and favorite books in Firebase, making them accessible across devices.
- **PDF Viewing**: Users can upload and read PDFs with an optimized interface.
- **Maps and Location Services**: Using the Google Places API, users can view nearby libraries and bookstores based on their location.
- **Explore Books**: Google Books integration allows users to explore and purchase books directly from within the app.
- **Book Reviews**: Users can write reviews for books they've read, whether uploaded or not, and save them for future reference.
- **Favorites**: Users can mark books as favorites for easy access at any time.

---

## Secondary Features

- **Third-Party Libraries Used**:
  - For book search using Google Books: `com.android.volley:volley:1.1.1`
  - For PDF viewing: `com.github.barteksc:android-pdf-viewer:2.8.2`
  - For finding nearby libraries/bookstores: `com.google.android.libraries.places:places:2.7.0`
  
- **Notifications**: Upon entering the app, users receive a welcome notification.
  
- **Explore New Books**: Users can explore new books via the Google Books API and view previews or purchase books directly from Google Play Store.

---

## Technologies Used

- **Programming Language**: Kotlin
- **Libraries**:
  - Firebase Realtime Database
  - Google Maps API
  - Google Places API
  - Google Books API
  - Android PDF Viewer (Bartek Szczerbinski)
  

