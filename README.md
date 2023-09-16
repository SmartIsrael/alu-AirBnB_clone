## Introduction
This project is the first step towards building a full web application, an Airbnb clone. The key objectives are:
- Create a parent class (`BaseModel`) for Airbnb object initialization, serialization, and deserialization.
- Develop a simple flow for serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file.
- Implement classes for Airbnb objects (e.g., User, State, City, Place) that inherit from `BaseModel`.
- Create the initial abstracted storage engine (File storage).
- Write comprehensive unit tests to validate all classes and the storage engine.

## Project Structure
The project is organized as follows:
- `models/`: Contains the Airbnb object classes (e.g., User, State, City, Place) that inherit from `BaseModel`.
- `tests/`: Holds unit tests for all project components. Tests are organized to match the project structure.
- `console.py`: The main command-line interface (CLI) script for managing Airbnb objects.
- `base_model.py`: Defines the `BaseModel` class for object initialization and serialization/deserialization.
- `file_storage.py`: Implements the File storage engine for saving and retrieving objects.
- `README.md`: This documentation file.

## Requirements
To run this project, you'll need:
- Python 3.8.5 or later.
- Ubuntu 20.04 LTS or a compatible environment.
- Pycodestyle (for code formatting).

## Installation
1. Clone this repository to your local machine:
   ```shell
   git clone https://github.com/your-username/airbnb-clone.git
