# Flutter user input

A very simple Flutter app, that asks the user to enter their name, and then tap on a button. The user's input would then be displayed. 

## How it was made

The `main.dart` file uses the `ToDoPage()` widget for home: 

The `todo_page.dart` file is a stateful widget that uses the `TextEditingController` to gather the inputted value into a variable called `myController`. 
The variable `greetingMessage` is created with an empty string value 
This variable is then referenced in the `greetUser()` method, which grabs the user's input from `myController.text` and sets the String `userName` variable in turn it sets the empty string to `"Hello $userName"`. The `greetingMessage` is then displayed in a Text widget to the user.

![image](https://github.com/user-attachments/assets/89325c34-828f-4fa5-b198-e118e70a9089)

