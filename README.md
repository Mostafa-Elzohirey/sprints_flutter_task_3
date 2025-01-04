# sprints_dart_task_3
make signup page to access the shopping screen

## Screen Components

1. the screen has an app bar that has a title "Sign up"
2. four TextFormFields for email, username, password, and confirm password
3. each text form field has a validator that makes sure that the field is not empty in addition to:
   1. the email validator to make sure the email has the '@' sign
   2. the username to make sure the first letter is an uppercase using the validators package
   3. the password to make sure its not less that 6 letters
   4. the confirm password makes sure the password is identical to the original
4. and then a signup button that verifies all form fields and if they are all correct shows an alert dialog that says sign in successful and when closed navigates to the shopping screen

the shopping screen code is [here](https://github.com/Mostafa-Elzohirey/sprints_flutter_task_2.git)