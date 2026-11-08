# Android Sensors Lab

COMP3074 - Mobile App Development I

**Student:** Felipe da Rocha Vieira Mattos  
**Student ID:** 101581203

## Description

This Android application monitors two device sensors using the Android Sensor API and displays their values using Jetpack Compose.

The application reads:

- Ambient temperature in degrees Celsius (°C)
- Gyroscope angular velocity for the X, Y, and Z axes in radians per second (rad/s)

## Features

- Reads the ambient temperature sensor
- Reads gyroscope X, Y, and Z values
- Updates the Jetpack Compose UI when new sensor events are received
- Handles unavailable sensors without crashing
- Registers sensor listeners in `onResume()`
- Unregisters sensor listeners in `onPause()`

## Technologies

- Kotlin
- Android Studio
- Jetpack Compose
- SensorManager
- SensorEventListener
- Android Emulator

## Sensor Testing

The application was tested using a Pixel 7 Android Emulator.

The ambient temperature sensor was tested with a simulated value of 30.0 °C.

The gyroscope was tested with simulated angular velocity values:

- X: 0.500 rad/s
- Y: 0.200 rad/s
- Z: -0.300 rad/s

Both sensor readings were displayed successfully in the application.

## Build

The project was successfully compiled using:

```powershell
.\gradlew.bat assembleDebug
```

## Repository

https://github.com/felipervm/101581203_COMP3074_SensorsLab
