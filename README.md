# ESP32 Live Distance Dashboard

## Aim

To interface an HC-SR04 ultrasonic sensor with an ESP32 and display live distance readings on a self-refreshing web dashboard.

## Components Required

* ESP32 development board
* HC-SR04 ultrasonic sensor
* Jumper wires
* Breadboard

## Technologies Used

* ESP32
* Arduino C++
* Wi-Fi
* HTML, CSS and JavaScript
* Wokwi Simulator

## Features

* Measures object distance using an ultrasonic sensor.
* Hosts a webpage on the ESP32.
* Displays distance in centimetres.
* Automatically updates readings every second.
* Shows an error message if the dashboard cannot retrieve data.

## Working Principle

The ESP32 triggers the HC-SR04 sensor and measures the returning echo pulse. It calculates the distance and provides the reading through a web endpoint. JavaScript requests updated data every second and refreshes the displayed value without reloading the entire webpage.

## Result

The ESP32 ultrasonic sensor system measures distance and displays live readings on a self-refreshing web dashboard.
