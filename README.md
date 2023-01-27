# Age In Minutes Android Application

![](https://img.shields.io/badge/Release-v1.0-blueviolet)
![](https://img.shields.io/badge/Language-Kotlin-005255)
![](https://img.shields.io/badge/Libraries-AndroidStudio-00cfff)
![](https://img.shields.io/badge/OS-Android-9cf)
![](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)
![](https://i.ibb.co/vHGHb84/image-2.png)

This project is an Android Application that convert time in minutes, I use it the 26th Junuary 2023 to know my age in minutes (I am born the 1st April 2003), and at the moment when I am writing these lines, I am 10 427 100 minutes old. 

# Summary

* **[Credits](#credits)**
* **[Installation](#installation)**
* **[How it works ?](#how-it-works)**
* **[Versions](#versions)**

# Credits

* **[FACON Nicolas](www.github.com/FACON-Nicolas/)** : project creator

# Installation

```bash
git clone https://github.com/FACON-Nicolas/age-in-minutes-app
# Open it on Android Studio
```

# How it works ?

the program is easy, when the user press the `SELECT DATE` button on the screen, there is a date picker dialog that opens and it is possible to choose a date.

Then the program get the current time since the 1970-01-01 in milliseconds and divide it by 60000 (to get the time in minutes).

```
currentTime <- now().getTime().ms / 60000 # time in minutes since 1970-01-01
dateChosen <- datePickerDialog.get().getTime() / 60000
timeInMinutes <- currentTime - dateChoosen
```


# Versions

* **1.0.0** : 2023-01-26
