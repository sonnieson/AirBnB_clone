Airbnb Clone Project
Welcome to the Airbnb Clone Project! This project is designed to help you learn fundamental concepts of higher-level programming through the development of a simplified version of the Airbnb website.

Overview
The project is divided into several steps, each focusing on a different aspect of web development and programming. By following these steps, you will gain hands-on experience with concepts such as command-line interfaces, web statics, database management, RESTful APIs, and more.

Getting Started
To get started with the project, follow these steps:

Clone the Repository: Begin by cloning this repository to your local machine using the following command:

bash
Copy code
git clone https://github.com/sonnieson/airbnb_clone.git
Navigate to the Project Directory: Enter the project directory using the cd command:

bash
Copy code
cd airbnb_clone
Setup: Follow the instructions in the project documentation to set up your development environment and install any necessary dependencies.

Project Structure
The project is organized into several directories and files, each serving a specific purpose:

console.py: This file serves as the entry point for the command-line interface (CLI) used to manipulate data without a visual interface.

models/: This directory contains all the classes used for the project. Each class represents a model, which is a representation of an object or instance.

tests/: This directory contains all unit tests for the project. Testing is an essential aspect of software development, and writing tests will help ensure the reliability and stability of your code.

models/base_model.py: This file contains the base class for all models in the project. It includes common attributes and methods such as id, created_at, updated_at, save(), and to_json().

models/engine/: This directory contains storage classes for managing persistence. For now, you'll only have file_storage.py, which handles file storage using JSON serialization.

Project Progression
The project is divided into several steps, each building upon the previous one:

The Console: Develop a command-line interface for manipulating data and storing objects in a JSON file.

Web Static: Learn HTML/CSS and create static HTML files for the website.

MySQL Storage: Replace file storage with database storage using MySQL and an Object-Relational Mapper (ORM).

Web Framework and Templating: Create a web server in Python and make static HTML files dynamic by integrating them with the database.

RESTful API: Expose objects stored in the database via a JSON web interface and manipulate them through a RESTful API.

Web Dynamic: Learn JQuery and load objects from the client side using your RESTful API.

Contributions
Contributions to the project are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request on GitHub.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Special thanks to Esther and Faith for providing guidance and inspiration throughout the development of this project.
