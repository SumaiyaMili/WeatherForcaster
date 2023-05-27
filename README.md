Weather Forecaster App
This project is a Flutter weather app that fetches weather data from a public weather API and displays it to the user in a visually appealing and user-friendly interface.

Features

GeoLocator: The app utilizes GeoLocator to provide location access and retrieve the user's current location.

Stateful Widget Life Cycle Methods:
initState(): This method is triggered when the Stateful Widget is inserted in the widget tree. It can be used to perform initialization tasks.
build(): The build() method is called when the widget is being built and allows you to define the UI of the widget.
dispose(): The dispose() method is invoked when the created object from the Stateful Widget is permanently removed from the widget tree. It can be used to clean up resources.

Dart Exception Handling: Exception handling is implemented using try-catch blocks to gracefully handle any errors that may occur.

Null Aware Operator: The null-aware operator (??) is used to assign a default value if a variable is null.

Open Weather API: The app fetches weather data from the Open Weather API. You can find more information about this API at https://openweathermap.org/current.

Networking with http package: The app uses the http package to make network requests and retrieve weather data from the API.

JSON Viewer Awesome: JSON Viewer Awesome is a Chrome extension that allows you to view formatted JSON files for easier data interpretation. You can use this extension to analyze the weather data retrieved from the API.

Dart Converter: The Dart converter is used to convert JSON data into usable objects that can be displayed in the app.

flutter_spinkit: The flutter_spinkit library is utilized to show a spinner widget to the user while waiting for data to be fetched or loaded.
