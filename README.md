# weather_app

A new Flutter project.

## Description

Flutter Weather App - A simple weather app. This app take your current location from geolocator plugin form where it can get you latitude and longitude. I give the cooridinates to the open weather API with the we can get the information about the weather of current location and showcase that location on the UI of the app. It's configured with [BLoC] for state management.

## Features and Enhancements:
- **Detailed Weather Information:** Display various weather parameters such as temperature, humidity, wind speed, etc.

- **Error Handling:** Provide informative messages in case of errors, such as failed API requests or location access issues.

- **Clean BLoC Architecture:** Utilize BLoC pattern for managing state, making the codebase modular and easy to maintain.

- **Separation of Concerns:** Divide functionalities into different folders (bloc, data, models, screens, services) for better organization.

- **Location Service:** Separate service for handling location-related tasks to keep the codebase modular.

- **Reusable Constants:** Store API keys, URLs, and other constants in a separate file for easy access and management.

# First Run

The project is configured with the following command. See the next section for configuring run configurations.

After installing the package dependencies with 

```
flutter pub get
```

run the app 

```
flutter run --release
```

## Run Configurations

In addition to the [Flutter's build modes][flutter_build_modes] (debug, profile, release), 

To run the app use the following command:
```
flutter run --weather_app  lib/main.dart
```





## App ScreenShot

![img1](https://github.com/Kakarot2002/Weather-App/assets/106004670/07bfc6db-2790-4b3a-92c3-c34209d78a95)
![img2](https://github.com/Kakarot2002/Weather-App/assets/106004670/46c93ce0-60e9-411a-a0f5-49f7c2c96571)


## App apk



For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
