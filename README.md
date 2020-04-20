
#### Pssword Locker, April 20th 2020
#### By **Mamadou Billo Diallo**
## About Application
This Python application will help you to manage your passwords and even generate new passwords. On Average, a person has at least 7 different accounts he or she has signed into, be it email, social media, entertainment or job portal accounts. It becomes really hard to remember all those passwords and even create new ones. As a user, you will be able to create a password locker account with your details, a login username and password, store already existing account credentials in the application, store already existing account username and password in the application, create new account credentials, create a credentials account and the application generates a password for you to use when you sign up for an account, have the option of putting in a password that you want to use for the new credential account, view various account credentials and their passwords in the application and delete a credentials account that you no longer need in the application.

## User Stories
These are the behaviours/features that the application implements for use by a user.
As a user, you will be able to:
- To create an account with your details - log in and password
- Store your existing login credentials
- Generate a password for a new credential/account
- Copy your credentials to the clipboard

## Set-ip/Installation Requirements
- python3.6
- pip
- pyperclip
- Terminal/Command Line Interface

### Test & Behaviour Driven Development(BDD & TDD)

| Behaviour                                   | Input                              | Output                                                                                                |
|---------------------------------------------|------------------------------------|-------------------------------------------------------------------------------------------------------|
| Display codes for navigation                | In terminal: $./run.py | Welcome, choose an option: ca-Create Account, li-Log In, ex-Exit                                      |
| Display prompt for creating an account      | Enter: ca                          | Enter your first name, last name and password                                                         |
| Display prompt for login in                 | Enter: li                          | Enter your account name and password                                                                  |
| Display codes for navigation                | Successful login                   | Choose an option: cc - Create Credential, dc - Display Credentials, del - Delete Credential, ex - exit |
| Display prompt for creating a credential    | Enter: cc                          | Enter the site name, your username and password                                                       |
| Display a list of credentials               | Enter: dc                          | Prints a list of saved credentials                                                                    |
| Display prompt for which credential to copy | Enter: cp                        | Enter the site name of the credential you wish to copy.                                               |
| Exit application                            | Enter: ex                          | Exit the current navigation stage                                                                     |


Deployment
To run the program, link all classes to the run file and use the following code at the beginning of your main code:

#!/usr/bin/env python3.6
At the terminal, run the following command:

./run.py
Behavior Driven Development
Given	When	Then
allowed actions	a user types in the action	the program fulfils the action
Built With
PyCharm - The text editor used
Git - The version control environment Used
Bootstrap
Technologies Used
Python
Contributing
Any contributions to this projects will be greatly appreciated. If you want to contribute to it, here are the suggested instructions:

Clone this GitHub repository to your local machine.
git clone 
Make your contributions.
Email me the zipped project at billodiallonet@gmail.com , or
Request permissions to post your contribution at my GitHub repository through the same email address.
Alternatively, you could email the main developer at billodiallonet@gmail.com with ideas on how this project could be more effective, efficient or beneficial.

Versioning
Used GIT and GitHub. There are commits attached to the entire project to show the management of versions.

Authors
Billo Diallo, any other contributor after the completion of the work can be viewed at this GitHub repository

Copyright
All Rights Reserved by @Billodiallo Other GitHub can however fork or clone this repository provided the necessary credit is given to the original author

License
This project is licensed under the MIT License. Moringa School moreover retains certain rights to elements in the code of this program.
