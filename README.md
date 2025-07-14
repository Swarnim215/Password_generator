# Password_generator_py_project
Hello World, this is my profile and here I have created a password generator.
This project is a **customizable password generator** built using Python's `random` and `string` modules. 

The script allows users to generate **strong and secure passwords** based on their preferences, including minimum length, inclusion of numbers, and special characters.

The core function, `password_generator()`, dynamically creates passwords using a pool of characters made up of uppercase and lowercase letters, digits, and punctuation symbols. Users can specify the **minimum password length** and whether they want to include **numerical digits** and **special characters**. The generator continues to add random characters until the specified conditions are met, ensuring the generated password is both random and secure.

The project uses:

* `string.ascii_letters` for alphabetic characters
* `string.digits` for numeric characters
* `string.punctuation` for symbols
* `random.choice()` to randomly select characters

By interacting with user input through the command line, the program tailors the password to user-defined requirements, making it both **flexible** and **user-friendly**. It is a great beginner project to practice **conditional logic**, **loops**, and the **use of standard Python libraries**. This password generator is ideal for creating secure login credentials for websites, applications, or personal use.
