Satellite Finder
A precise satellite dish alignment tool for Android built with Kotlin. Uses device sensors and trigonometric calculations to help users position satellite dishes with accuracy.
Features
Real-time Compass & Azimuth: Uses device magnetometer and accelerometer for accurate heading
Bubble Level: Visual bubble meter for horizontal dish alignment
AR Overlay: Camera-based augmented reality view for visual satellite positioning
Trigonometric Positioning: Calculates elevation and azimuth angles using GPS coordinates and satellite orbital data
Multiple Satellite Support: Pre-configured with popular satellite positions (Paksat, Asiasat, etc.)
Material Design UI: Clean, intuitive interface optimized for outdoor use
Tech Stack
Language: Kotlin
Architecture: MVVM
Sensors: Accelerometer, Magnetometer (Compass), GPS
UI: XML with Material Design Components
Math: Custom trigonometric formulas for satellite positioning
Camera: Camera2 API for AR overlay
Screenshots
(Add screenshots here)
How It Works
Select target satellite from the list
Point device camera toward the sky
Follow AR overlay and compass guidance
Use bubble meter to level the dish horizontally
Fine-tune using signal strength feedback
Installation
bash
git clone https://github.com/Shehbaz99/Satellite-Finder.git
Open in Android Studio and run on a device with magnetometer and GPS sensors.
Future Improvements
[ ] Signal strength integration via USB DVB tuner
[ ] Saved location presets
[ ] Satellite database expansion
[ ] Jetpack Compose migration
License
MIT License
Author: Shehbaz Hussain
