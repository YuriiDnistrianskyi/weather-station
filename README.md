# Weather Station

## Overview

**Weather Station** is platform for monitoring temperature, humidity and pressure by meteostantion device.

The project consists of several independent components:

* **Backend Server** (Flask)
* **ESP8266-based Device**
* **Mobile Application**

The system collects temperature, humidity and pressure measurements, stores data and provides visualization through a mobile application.

---

## Architecture

<img width="447" height="396" alt="image" src="https://github.com/user-attachments/assets/d4242bb3-a24c-4579-acd0-f7c43b4488e7" />

---

## Components

### Backend

The backend is responsible for:

* User management
* Device management
* Authentication and authorization
* Data storage

#### Technologies

* Python
* Flask
* SQLAlchemy
* HTTP
* MySQL
* JWT

---

### MySQL

Stores relational data:

* Users
* Meteostantion
* Info (temperature, humidity, pressure)

---

### ESP8266 Device

Hardware controller built on:

* ESP8266 WEMOS
* BME280
* 7-Segment LED Display

Responsibilities:

* Read temperature
* Read humidity
* Read pressure
* Send telemetry to the backend

#### Technologies

* C++
* PlatformIO

---

### Mobile Application (not finished)

Provides user interface for:

* Authentication
* Device management
* Monitoring temperatures
* Monitoring hummidity
* Monitoring pressure

#### Technologies

* Expo
* JS/TS

---

## Structure

| Repository | Description | Link |
|---|---|---|
| Backend | API server | https://github.com/YuriiDnistrianskyi/weather-stantion-server
| Mobile App (not finished) | Expo app for monitoring | https://github.com/YuriiDnistrianskyi/weather-station-app
| Firmware | Meteostantion (ESP8266) | https://github.com/YuriiDnistrianskyi/weather-station-hardware

---

## Features

* Monitoring temperaure
* Monitoring humidity
* Monitoring pressure  
* Historical telemetry storage
* Mobile application

---
