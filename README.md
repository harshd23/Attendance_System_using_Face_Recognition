# Attendance_System_using_Face_Recognition

## INTRODUCTION :

The goal of this project is to create an attendance system that tracks employee presence, time-in,
and time-out using facial recognition. The construction of a web application to support a variety
of system use cases, including the registration of new employees, the contribution of images to the
training dataset, the viewing of attendance records, etc., is also covered in this paper, which also
covers issues like facial detection, alignment, and identification. The system utilizes advanced
image processing and artificial intelligence algorithms to recognize individuals' faces and
automatically mark their attendance. This technology provides several benefits over traditional
attendance methods, including improved accuracy, efficiency, and convenience. It can also reduce
the risk of fraudulent activities such as proxy attendance. This project aims to be a productive
replacement for outdated manual attendance systems. When security is a priority, it can be
employed in corporate offices, educational institutions, and other organizations.  

## PROBLEM STATEMENT :

The traditional methods of taking attendance in educational institutions and corporate offices, such
as paper-based sign-in sheets or manual roll-calls, are time-consuming, inefficient, and prone to
errors. These methods can also be easily manipulated, leading to inaccurate attendance records and
potential fraudulent activities, such as proxy attendance. Additionally, during the ongoing COVID-
19 pandemic, traditional attendance methods pose a risk of spreading the virus due to physical
contact.  
To address these challenges, an attendance system using face recognition technology can provide
a viable solution. This system can automatically recognize and verify individuals' faces, reducing
the need for manual intervention and eliminating the risk of fraudulent activities. Moreover, there
is a need for a comprehensive evaluation of the system's effectiveness, reliability, and scalability
to ensure its suitability for various applications and settings.  

## SCOPE AND IMPORTANCE :

In modern society, facial recognition is becoming more prevalent. In the area of security, it has
achieved significant advancements. It is a very useful tool that can assist law enforcement in
identifying criminals, and software providers are utilizing the technology to make it easier for
people to access the technology. This technology can be improved to be used in several
contexts, such as ATMs, accessing private files, or handling other delicate materials.
The traditional attendance system, where attendance is manually recorded, will be automated
as part of this project. Additionally, it enables an organization to digitally preserve its
attendance, break time, in-time, and out-of-time data. The system's digitization would also aid
in a better data visualization employing graphs to show the number of personnel now present,
their cumulative work hours, and their break times. With its new features, the conventional
attendance system is effectively upgraded and replaced.

## DESIGN :
It is a collection of processes that facilitate the designing, development, implementation and maintenance of enterprise data management systems. It helps produce database systems:

- That meet the requirements of the users.
- Have high performance.

### FLOWCHART

![Flowchart](./assets/Flowchart.png "Flowchart of the attendance system")

### TRAINING DATA FOR THE SVM ALGORITHM :

![Training data](./assets/Training_data.png "TRAINING DATA FOR THE SVM ALGORITHM")


## GUI SCREENSHOTS :

![Admin Dashboard]( ./assets/Admin.png)
<p align="center">Admin Dashboard</p>

![Register Window]( ./assets/Register_Window.png)
<p align="center">Register Window</p>

![Homepage]( ./assets/Homepage.png)
<p align="center">Homepage</p>

![Stats]( ./assets/Stats.png)
<p align="center">Previous Week Data in Graph</p>

## CONCLUSION :

An attendance system using face recognition is a powerful tool that can streamline attendance
management and improve security in various settings such as schools, workplaces, and events. The
system works by capturing facial images of individuals and using machine learning algorithms
such as SVM to identify and track attendance.

## STEPS TO RUN THIS APPLICATION :
1. Please install [Python version 3.8.10](https://www.python.org/downloads/release/python-3810/) to run the project successfully.
2. It is necessary to install the [**CMake**](https://cmake.org/download/) and [**Visual Studio**](https://visualstudio.microsoft.com/downloads/).
3. Create a folder in your PC and Clone this project in it.
4. To run the project, Open the terminal and run the following commands:
 ```js
  python manage.py migrate
 ```
 ```js
  python manage.py runserver
 ```
5. If everything is okay with your project, Django will start running the server at `localhost port 8000` (127.0. 0.1:8000) and then you have to navigate to that link in your browser.
6. **For Admin login, the credentials are Username - admin & Password - admin **
7. Also, To view the Database please download [**DB Browser for SQLite**](https://sqlitebrowser.org/dl/).
8. You can then manually change the password for the employee and admin using the DB Browser.
9. While successfully running the project, Login using Admin credentials then for Adding new employees you need to first register them as *New Employee* and then *Add Photos* of the Employee. It will take 20 seconds to capture the photos and then you can *Train the model*.
10. You need to then Go to the landing/home page and *Mark their attendance*, to check whether the model can detect the New Employee with the name and accuracy. Similary, you can add new employees and train the model.
11. **Note:** It is necessary to Train the model everytime after new employee have been added. 
12. Congratulations!!✨ You have successfully run the project.

## CONTRIBUTING :

This is an open source project, and contributions of any kind are welcome and appreciated. Open issues, bugs, and feature requests are all listed on the [issues](https://github.com/harshd23/Attendance_System_using_Face_Recognition/issues) tab and labeled accordingly. Feel free to open bug tickets and make feature requests.

## CONTRIBUTORS :

- [Sarvesh Chavan](https://github.com/sarvesh2847)
- [Harsh Dalvi](https://github.com/harshd23)
- [Osama Shaikh](https://github.com/Osamashaikh90)
- [Bhanu Sunka](https://github.com/Bhanu1776)

<hr>

© 2023 Harsh Dalvi and contributors  
This project is licensed under the [**MIT license**](https://github.com/harshd23/Attendance_System_using_Face_Recognition/blob/main/LICENSE).

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
