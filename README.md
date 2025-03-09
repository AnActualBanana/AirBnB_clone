# AirBnB Clone

## Description
This Holberton School project is a clone of AirBnB, developed in six phases each either solo or in groups of 2-4 members. The goal was to build a web application that replicates the core functionalities of AirBnB, including user authentication, property listings, and a web interface.
This version of the project was the console application, implementing some basic functionality for adding and removing data from a command-line interface

## Features
- Command-line interface for managing database objects
- Web-based frontend with static and dynamic content

## Project Structure
| Directory/File | Description |
|--------------|-------------|
| `models/` | Contains the data models for users, places, reviews, states, and amenities |
| `models/engine/` | Handles file storage for the database |
| `models/engine/file_storage.py` | Implements file-based storage for objects |
| `tests/` | Unit tests for the project |
| `tests/test_models/` | Tests for individual models |
| `tests/test_models/test_engine/` | Tests for the engine module |
| `tests/test_models/test_engine/test_file_storage.py` | Tests for `file_storage.py` |
| `web_static/` | Static HTML and CSS files for the frontend |
| `web_static/styles/` | CSS styles for the frontend |
| `console.py` | Command-line interpreter for managing objects |

## Installation
Clone the repository:
```sh
git clone https://github.com/yourusername/AirBnB_clone.git
cd AirBnB_clone
```

## Usage
Run the command-line interface:
```sh
python3 console.py
```
Example commands:
```sh
(hbnb) create User
d75e1d2d-6c91-4b2a-b0e4-12a3b8e12345
(hbnb) show User d75e1d2d-6c91-4b2a-b0e4-12a3b8e12345
(hbnb) quit
```

## Contributors
- [Logan McClain](https://github.com/AnActualBanana)
- [Jarrett Jewart](https://github.com/jarrettjewart)
