# Weather Station

## Overview

**Cooling System** is an automatic cooling platform designed to monitor object temperatures and dynamically control cooling devices. Although originally developed for computers and laptops, the system can be adapted for any temperature-controlled object.

The project consists of several independent components:

* **Backend Server** (Flask)
* **ESP8266-based Device**
* **Mobile Application**

The system collects temperature, humidity and pressure measurements, stores data and provides visualization through a mobile application.

---

## Architecture


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
