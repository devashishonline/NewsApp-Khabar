# NewsApp-Khabar

**NewsApp-Khabar** is a fully functional Android news application built using **Kotlin** and **Jetpack Compose**, which delivers the latest news articles through seamless integration with the **Google News API**. The app follows the **MVVM (Model-View-ViewModel)** architecture pattern to maintain a clean and scalable codebase. Users can browse through news articles, search for specific topics, and bookmark their favorite articles for later reference.

## Features
- **Modern UI with Jetpack Compose**: A clean, responsive user interface designed with Jetpack Compose for native Android views.
- **Splash Screen**: A quick splash screen displayed during app launch.
- **News Feed**: Fetch and display real-time news articles using Retrofit to consume the Google News API.
- **Search Functionality**: Allows users to search for specific news articles by keyword.
- **Bookmarking**: Users can save articles they want to revisit later and access them from the Bookmark section.
- **Bottom Navigation**: Smooth navigation between Home, Search, and Bookmark sections through a bottom navigation bar.

## Screenshots
Here are some screenshots of the app:

### Onboarding Screens
![Onboarding]([path/to/onboarding-screens.jpg](https://github.com/devashishonline/NewsApp-Khabar/blob/master/app/Assets/262676788-0ba957e5-8b70-42d6-ab09-2cf38ba3936e.png))
![Onboarding]([path/to/onboarding-screens.jpg](https://github.com/devashishonline/NewsApp-Khabar/blob/master/app/Assets/262678744-90385dcf-a852-47c2-be23-aa243adb12e8.png))


### Home Screen, Search, and Article Details
![Home and Search]([path/to/home-search-screens.jpg](https://github.com/devashishonline/NewsApp-Khabar/blob/master/app/Assets/262676811-6dda119b-1b3f-4637-91a4-314b85eda214.png))
![Home and Search]([path/to/home-search-screens.jpg](https://github.com/devashishonline/NewsApp-Khabar/blob/master/app/Assets/262678757-63e8be30-6de8-4060-9ce2-0fa5000c95b8.png))


### Bookmark Section
![Bookmark]([path/to/bookmark-screens.jpg](https://github.com/devashishonline/NewsApp-Khabar/blob/master/app/Assets/262676840-6e7186fa-9c05-4705-b568-8326cc99c17f.jpg))
![Bookmark]([path/to/bookmark-screens.jpg](https://github.com/devashishonline/NewsApp-Khabar/blob/master/app/Assets/262678767-0382d92a-e965-4bb3-a1f4-d82c0da87f94.png))


## Tech Stack
- **Kotlin**: The programming language used for building the app.
- **Jetpack Compose**: A modern toolkit for building native Android UI.
- **Retrofit**: For making API requests to the Google News API.
- **Coroutines**: To manage background threads and asynchronous code.
- **Room Database**: For saving and retrieving bookmarked articles.
- **Paging 3**: Used for efficient and smooth pagination, allowing the app to load data incrementally as users scroll through articles.
- **Dagger Hilt**: A dependency injection library used to manage and inject dependencies across the app, improving modularity and scalability. 

## Architecture
The app follows the **MVVM architecture** pattern:
- **Model**: Responsible for handling business logic and managing data sources like the API and local Room database.
- **View**: The UI layer built with Jetpack Compose.
- **ViewModel**: Manages the communication between the Model and the View, ensuring separation of concerns.

## How to Run the App
1. Clone the repository.
   ```bash
   git clone https://github.com/devashishonline/NewsApp-Khabar.git
