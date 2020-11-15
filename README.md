# Password Locker

## Built By [KIREZI BANA HORTENSE]

## Description
Password Locker is a terminal run python application that will help manage passwords and generate new passwords.
## User Stories
As a user:

* I Can create a password locker account with details, a login username and password.
* I want to store my already existing account credentials in the application. 
* I want to create new account credentials in the application. 
* I want to have the option of putting in a password that I want to use for the new credential account.
* I also want to view my various account credentials and their passwords in the application.
* I want to delete a credentials account that I no longer need in the application.
* I can copy my credentials to the clipboard

## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display codes for navigation | **In terminal: $./password_locker.py** | Welcome, choose an option: ca-Create Account, li-Log In, ex-Exit |
| Display prompt for creating an account | **Enter: ca** | Enter your first name, last name and password |
| Display prompt for login in | **Enter: li** | Enter your account name and password |
| Display codes for navigation | **Successful login** | Choose an option: cc - Create Credential, dc - Display Credentials, copy - Copy Credential, ex - exit |
| Display prompt for creating a credential | **Enter: cc** | Enter the site name, your username and password |
| Display a list of credentials | **Enter: dc** | Prints a list of saved credentials |
| Display prompt for which credential to copy | **Enter: copy** | Enter the site name of the credential you wish to copy. |
| Exit application | **Enter: ex** | Exit the current navigation stage |

## SetUp / Installation Requirements
### Prerequisites
* python3.6
* pip
* pyperclip
* xclip

## Running the Application
* To run the application, in your terminal:

        $ chmod +x password_locker.py
        $ ./password_locker.py
        
## Testing the Application
* To run the tests for the class file:

        $ python3.6 user_credentials_test.py
        
## Technologies Used
* Python3.6

## License
MIT &copy;2020 [kirezi bana hortense]

