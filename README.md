### Racetrack Hero

# Overview

Racetrack Hero is a software solution designed to transform your Raspberry Pi into a powerful data acquisition and analysis tool for motorsports enthusiasts. Whether you're a professional racer, amateur driver, or simply passionate about cars and racing, Racetrack Hero provides the tools you need to analyze and improve your performance on the track.

# Features

- **Data Logging:** Capture real-time data from your vehicle's onboard sensors, including GPS, acceleration, speed, RPM, and more.
- **Visualization:** Visualize your driving data in real-time or post-session to analyze your performance and identify areas for improvement.
- **Comparison Tools:** Compare your laps side by side to understand where you're gaining or losing time on the track.
- **Customizable Dashboards:** Create custom dashboards tailored to your preferences, displaying the metrics that matter most to you.
- **Export and Sharing:** Export your data for further analysis or share it with friends, coaches, or fellow racers.

# Acceptance
By using Racetrack Hero software and the associated hardware component, you agree to all of the terms and conditions below.

# Racetrack Hero License

This software is licensed under the [GNU General Public License v3.0 (GPL-3.0)](https://www.gnu.org/licenses/gpl-3.0.html).

# No Liability

The Racetrack Hero software and hardware component come as is, without any warranty or condition, and the licensor will not be liable to you for any damages arising out of these terms or the use or nature of the Racetrack Hero software or hardware component, under any kind of legal claim. This includes, but is not limited to, any accidents, injuries, deaths, or damage to property, including vehicles, that may occur as a result of using the Racetrack Hero software or hardware component for building a telemetry device with a lap timer or any related purposes.

# Getting Started

To get started with Racetrack Hero on Raspberry Pi 4 and 0 W with GPS hat ensure to obtain following components:

## Headless Device
<img width="620" height="480" src="https://private-user-images.githubusercontent.com/7461901/318235895-f0694de3-5d04-4bbe-91a7-da1ce0b5a151.jpeg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTE4NDk5MjAsIm5iZiI6MTcxMTg0OTYyMCwicGF0aCI6Ii83NDYxOTAxLzMxODIzNTg5NS1mMDY5NGRlMy01ZDA0LTRiYmUtOTFhNy1kYTFjZTBiNWExNTEuanBlZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAzMzElMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMzMxVDAxNDcwMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTYyOGFjZjAzMzE1OWQ1ZDViMDgwZGFmOTQ1ZWQ2NTU5OWQ0Njg2ZmMwZDM3YjJkZDExYTM1NTZhZmFiZWIxM2UmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.e_9_GXqPq_epUaKzaWmcjlfphr7SzoFIYbg-JvLua3s"/>

### Hardware Components
1. Rasbperry Pi zero W 2. 
2. [Berry GPS-IMU V4](https://ozzmaker.com/product/berrygps-imu). You can also obtain different GPS hats which might be already compatible with this software (look at GPS hat drivers in "./libs/gps" directory).
3. GPS Antenna - 32db High Gain Cirocomm 5cm Active GPS Antenna Ceramic Antenna 25x25x2mm Geekstory
4. ZTE MF833V 4G LTE USB Modem Dongle for data.
5. Case - UniPiCase Pi Zero Case - Tall (Stock Faceplate)
6. [Suction Cup](https://www.amazon.com/dp/B07YJJSCLX?psc=1&ref=product_details)

### Assembly
1. Install the Berry GPS hat onto the Raspberry Pi0. Soldering is required for getting the hat attached to it.
<img width="620" height="480" src="https://private-user-images.githubusercontent.com/7461901/318236432-01eb32f4-33a6-49e3-b488-f37f1a2767d8.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTE4NTA1NTIsIm5iZiI6MTcxMTg1MDI1MiwicGF0aCI6Ii83NDYxOTAxLzMxODIzNjQzMi0wMWViMzJmNC0zM2E2LTQ5ZTMtYjQ4OC1mMzdmMWEyNzY3ZDguanBnP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI0MDMzMSUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNDAzMzFUMDE1NzMyWiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9NGJkMjk3Y2RjZGM0MzhlYWJlZTBjOTM0OGY1NGYyMmY2OTU4MGM2OTMxZTRhZjBkNjQ2MGY1MzE3ZjE1NzM2YiZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QmYWN0b3JfaWQ9MCZrZXlfaWQ9MCZyZXBvX2lkPTAifQ.rZ8Qiw_SXPVyTYqoBQk58WiRVbMDipHi1ro5kqEIGSk"/>

2. Obtain the GPS floor either by ordering it from the Racetrack Hero store, or by printing it yourself from the following CAD file.
3. Attach the GPS floor onto the top of the stack.
4. Attach the GPS antenna onto the previously printed/obtained GPS floor.
5. Attach the suction cups into the shell.
6. Glue all thing together, being generous, at the end of the day this will be on your winshield.
7. Insert the GPS angled connector into the mini USB on PI0, and connect the ZTE modem. Angle it like on this picture, glue it all together.



## Touchscreen Device with bigger screen
<img width="480" height="620" src="https://private-user-images.githubusercontent.com/7461901/318235897-6c9e1012-b2a1-4dff-8652-64834cdae670.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTE4NTI0NzgsIm5iZiI6MTcxMTg1MjE3OCwicGF0aCI6Ii83NDYxOTAxLzMxODIzNTg5Ny02YzllMTAxMi1iMmExLTRkZmYtODY1Mi02NDgzNGNkYWU2NzAucG5nP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI0MDMzMSUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNDAzMzFUMDIyOTM4WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9NjliNDkxMDkxYTEyMTUwYmQyNzkzYTI5YmI0N2I0Njk3YWYyZjdiNzlmOWNiZDg1OWZjN2I0YjM3MjBjODNjZiZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QmYWN0b3JfaWQ9MCZrZXlfaWQ9MCZyZXBvX2lkPTAifQ.8DTk8CS2esS3vvAQQXwA9Xuc3H85h7aBrxlVFcvzM9M"/>

### Hardware Components
1. Raspberry Pi 4
2. [Berry GPS-IMU V4](https://ozzmaker.com/product/berrygps-imu). You can also obtain different GPS hats which might be already compatible with this software (look at GPS hat drivers in "./libs/gps" directory).
3. External GPS Antenna - GPS/GNSS Magnetic Mount Antenna - 3m (SMA)
4. SMA GPS Connector. 
5. ZTE MF833V 4G LTE USB Modem Dongle for data.
6. Pi Case 
7. Pi Touchscreen 7inch.
   
## Touchscreen Device with smaller screen
<img width="480" height="620" src="https://private-user-images.githubusercontent.com/7461901/318236051-cd1f8169-47e7-4a7b-a62d-0be9ec05ec67.jpeg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTE4NTI0NzgsIm5iZiI6MTcxMTg1MjE3OCwicGF0aCI6Ii83NDYxOTAxLzMxODIzNjA1MS1jZDFmODE2OS00N2U3LTRhN2ItYTYyZC0wYmU5ZWMwNWVjNjcuanBlZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAzMzElMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMzMxVDAyMjkzOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTdjYjU5ZmJjZDJhM2JiMzIxZmE5MGVmM2JkZDkzM2QyNzBlY2EwZDAzNWIxNTVlMTM4ZmI3MTE1YjA5OGZmMjgmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.zeBUhFB1N4Yb_x3imyDXoN1gOzu5BqgBecEKEufAxUQ"/>

# Author
- Racetrack Hero was created by Orcha Software, LLC
- Author [wawura](https://github.com/wawura) 
- Website [Racetrack Hero](https://www.racetrackhero.com)


