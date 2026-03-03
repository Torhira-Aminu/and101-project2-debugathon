# AND101 Project 2 - Kotlin Debug-a-thon

Submitted by: **Torhira Aminu**

Time spent: **3** hours spent in total

## Summary

**Android Kotlin Debugging** is an Android app that originally contained multiple runtime crashes caused by common Kotlin mistakes such as improper type casting, null assertions, off-by-one errors, and infinite recursion.  

After debugging and refactoring the code, the app now runs smoothly and demonstrates multiple small activities including navigation, number calculations, date handling, color randomization, list iteration, and null safety handling.

If I had to describe this project in three (3) emojis, they would be:  


## Application Features

The following REQUIRED features are completed:

- [x] 👋 Debug and fix navigation to Hello World activity
- [x] 4️⃣ Debug and fix Number Sum (2 + 2) activity
- [x] 📅 Debug and fix Current Day activity 
- [x] 🌈 Debug and fix behavior of Random Color activity
- [x] 🗒️ Debug and fix Print List activity
- [x] 💯 Debug and fix Favorite Number activity

The following STRETCH features are implemented:

- [ ] None

The following EXTRA features are implemented:

- Improved understanding of Kotlin null safety and safe type conversions
- Refactored recursive bug in Random Color activity
- Corrected loop bounds to prevent ArrayIndexOutOfBoundsException

## Video Demo

Here's a video / GIF that demos all of the app's implemented features:


[project 2 gif](https://github.com/user-attachments/assets/c28301eb-2c3f-4478-9820-8b33591f932e)


GIF created with **ScreenToGif**

## Notes

This project strengthened my understanding of Kotlin debugging. I learned how improper type casting (`as Int`), misuse of `!!`, incorrect resource handling with `getString()`, and off-by-one errors can cause runtime crashes.  

Debugging using Logcat helped me identify stack traces and trace errors directly to the faulty lines. This project improved my confidence in reading error logs and fixing issues systematically.

## License

Copyright 2026 Torhira Aminu

Licensed under the Apache License, Version 2.0
