# Cat Breeds Explorer

Cat Breeds Explorer is a mobile application written in Kotlin using Jetpack Compose for the user interface and Model-View-Intent architecture for code organization. The app allows users to explore various cat breeds, displaying detailed information about each breed.

## Features

- **Breeds List Screen:** Displays a list of all known cat breeds with basic information.
- **Breeds Details Screen:** Detailed view of each breed including images, description, origin countries, temperament traits, lifespan, weight/height, and additional behavioral information.
- **Search Breeds:** Search functionality by breed name
- **Integration with Wikipedia:** Direct links to Wikipedia pages for more breed information.

## Technical Details

- **Asynchronous Programming:** Utilizes Kotlin Coroutines for asynchronous operations.
- **Networking:** Retrofit and OkHttp libraries for web service communication.
- **Error Handling:** Implements loading and error states for better user experience.
- **Data Serialization:** Kotlinx Serialization for data serialization.
