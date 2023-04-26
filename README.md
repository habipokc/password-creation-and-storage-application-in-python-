# password-creation-and-storage-application-in-python-
 A password generator built using tkinter and json
 
The code is a simple password manager that allows a user to save and retrieve login credentials for various websites. The user interface is built using the Tkinter library.

The password generator function generates a random password by combining letters, numbers, and symbols. The length of the password and the number of symbols/numbers are randomly generated within a certain range.

The save function is responsible for saving the user's login credentials in a JSON file called "data.json". It creates a new dictionary with the website, email, and password as key-value pairs, and appends this dictionary to the existing data in the file.

The find_password function searches for the user's login credentials based on the website entered in the GUI. It reads the "data.json" file and looks for a dictionary with a key that matches the website entered by the user. If a match is found, the function displays the email and password associated with that website.

The user interface consists of several labels, entry fields, and buttons. The canvas widget displays a logo image at the top of the window. The website entry field is used to input the name of the website for which the user wants to save or retrieve login credentials. The email and password entry fields are used to input the user's login credentials. The "Add" button is used to save the user's login credentials, and the "Search" button is used to retrieve them. The "Generate password" button is used to generate a random password, which can be used for the current website or copied and used elsewhere.

Overall, this code provides a simple and useful tool for managing login credentials and can be expanded upon to include additional functionality such as encryption and secure storage.
