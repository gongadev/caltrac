# caltrac-kivy
Kivy rework of the Caltrac project. Requires the latest Kivy and Python 2. This project is not completely functional and should be considered heavily WIP. The stable Tkinter release can be found here: https://shiburizu.github.io/caltrac
NOTE: this project generates a file Caltrac.db which is part of the .gitignore -- this file contains user-specific info.

CalTrac-kivy is soon to be replacing the tkinter caltrac repo. Stay tuned.

![alt text](http://i.imgur.com/O9W23Al.png "CalTrac")
### Experimental Calorie recommendation and tracker program.
CalTrac is a graphical desktop application with a goal to visualize and raise awareness on the importance of calorie intake in our daily diet. Current nutritional standards generalize us into the 2000 calorie diet and our purpose in this project is so both find where we might find ourselves in the personal calorie needs, and to create an application that puts this value in context with what we eat by portion count. Nutrition is a numeric matter and CalTrac’s codebase is a combination of Python 2.7 and SQLite3 implementations. Native look and feel is provided by Python’s minimalist Tkinter library. The application achieves a desired personal estimate on caloric intake needs by the well-studied Harris-Benedict equation and provides recommendations on losing and gaining weight over time by means of hard limits on how little we should eat, and works in standard increments of 500 calories per day. This is complemented by a personal tracker of items eaten, summarizing them in calorie intake by portion which is compared as a total with the recommended intake number.
