## Flutter CRUD App with Parse Server and Back4App Integration
This is a Flutter CRUD (Create, Read, Update, Delete) application with Parse Server integration. The app allows you to manage a list of tasks with features such as adding, editing, and deleting tasks.

### Features
1. **List Tasks**: View a list of Tasks retrieved from the Parse Server.
2. **Add Task**: Add a new Task with a task name and description.
3. **Edit Task**: Modify the details of an existing Task.
4. **Delete Task**: Remove a Task after confirming the deletion.
5. **Pull-to-Refresh**: Refresh the Task list by pulling down the screen.
6. **Side Navigation**: Access additional features and information from the side navigation menu.
7. **About Section**: View information about the developer.
8. **Responsive Pop-ups**: The add and edit pop-ups are responsive to the number of fields available in the form.
9. **Attractive UI**: The app features a clean and attractive user interface.
10. **Pop-up**: The confirmation pop-up for delete feature. 

### Prerequisites
Before you start, make sure you have the following installed on your Windows 10 machine:
1.	Flutter SDK: Install the Flutter SDK by following the instructions on the official Flutter website: Flutter - Get Started
2.	Git: Ensure that Git is installed on your machine. You can download Git from Git - Downloads.
3.	Android Studio: Install Android Studio, which includes the Android SDK, by visiting Android Studio - Download.
4.	Visual Studio Code (Optional): Although you can use any text editor, Visual Studio Code is recommended for a smoother development experience. Download it from Visual Studio Code.



### Getting Started
1.	Add Flutter to System Path: Add the flutter/bin directory to your system path to run Flutter commands globally.
2.	Run flutter doctor: Open a terminal and run the following command to check if there are any dependencies you still need to install: 
```bash
flutter doctor
```
Follow the instructions provided by flutter doctor to resolve any issues.



### Creating and Running a Flutter Application
1.	Create a New Flutter Project:
Run the following commands to create a new Flutter project:
```bash
flutter create my_flutter_app_name
```

2.	Navigate to the Project Directory:
Change to the project directory:
```bash
cd my_flutter_app_name
```

3.	Open the Project in Visual Studio Code (Optional):
If you're using Visual Studio Code, open the project by running:
```bash
code .
```

4.	Run the App:
Connect your Android device or start an Android emulator. Then, run the app using:
```bash
flutter run
```
This command compiles and runs your Flutter app on the connected device.

5.	Hot Reload:
Make changes to your Flutter code, and press R in the terminal to hot reload the app instantly.



### Installation
1.	Clone the repository:
```bash
git clone https://github.com/humbeveeraj/flutter_task_crud_app.git
cd repository-location
```

2.	Install dependencies:
```bash
flutter pub get
flutter pub upgrade
```

3.	Update Parse Server keys:
•	Open lib/main.dart.
•	Replace keyApplicationId, keyClientKey, and keyParseServerUrl with your Parse Server details.

4. To list all the configured devices, run below command from Terminal:
```bash
flutter devices
```

5.	Run the App:
Connect your Android device or start an Android emulator. Then, run the app using:
```bash
flutter run
```

6. Run the application on specific device:
**Chrome Browser:**
```bash 
flutter run -d chrome
```
**Android Emulator**
```bash
Android Emulator: flutter run -d <Android_Device_Name>
```


### Screenshots
### Flutter Mobile Application - Task List - Android
<img src="https://github.com/humbeveeraj/flutter_task_crud_app/raw/main/application_images/screenshot1.jpeg" width="250" height="550">

### Flutter Mobile Application - Add Task - Android
<img src="https://github.com/humbeveeraj/flutter_task_crud_app/raw/main/application_images/screenshot2.jpeg" width="250" height="550">

### Flutter Mobile Application - Edit Task - Android
<img src="https://github.com/humbeveeraj/flutter_task_crud_app/raw/main/application_images/screenshot3.jpeg" width="250" height="550">

### Flutter Mobile Application - Delete Task Confirmation Pop-up and Delete - Android 
<img src="https://github.com/humbeveeraj/flutter_task_crud_app/raw/main/application_images/screenshot4.jpeg" width="250" height="550">

### Flutter Mobile Application - Side Navigation - Android 
<img src="https://github.com/humbeveeraj/flutter_task_crud_app/raw/main/application_images/screenshot5.jpeg" width="250" height="550">

### Flutter Mobile Application - About Page - Android 
<img src="https://github.com/humbeveeraj/flutter_task_crud_app/raw/main/application_images/screenshot6.jpeg" width="250" height="550">

### Flutter Web Application View 
![App Screenshot 7](https://github.com/humbeveeraj/flutter_task_crud_app/raw/main/application_images/screenshot7.png)



### Additional Resources
1. Flutter Documentation: Explore detailed documentation to enhance your Flutter development skills.
2. DartPad: Try Dart programming language online in a DartPad.

Congratulations! You've successfully set up and run your first Flutter application. 
**Happy Coding!!!**


### Assignment Submission Details
Veeraj Rajendra Humbe
2022mt93538
