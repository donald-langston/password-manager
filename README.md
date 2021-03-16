# password-manager

Simple desktop gui application to create random passwords for websites that you decide to store. After passwords are created they will be stored in a json file inside the project directory. There is a search box as well where you can search for the website if you have forgotten the password and an alert box will display the password. The password will be copied to the clipboard as well where you can paste the password directly into the website.

# Installation

Clone this repository
CD into the password-manager directory that was just created
Create a virtual environment i.e. on Windows run python -m venv env
Activate virtual environment i.e. on Windows run .\env\Scripts\activate
Install depencies in requirements.txt by running pip install -r requirements.txt

# Usage

Run the main.py file which will open the program
Enter a website that you would like to create a password for in the website field
Enter an email/username in the email/username field
Click generate password and a randomly generated password will be created
Click add and the email/username password combination will be saved inside a data.json file in the directory

A password can be searched for by entering the website and clicking the search button
If a password was created for that website it will show in an alert box and also copied to the clipboard where it can be pasted directly in the particular website
