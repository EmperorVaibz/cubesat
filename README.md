XCubed Data and Images Repository

Overview
Welcome to the XCubed Data and Images Repository! This repository is designed to store and manage data and images collected from XCubed, our cube satellite project. 
Whether you're a team member looking to access the latest satellite data or a collaborator interested in our project, this repository is the central hub for all things XCubed.

Table of Contents
Getting Started
Prerequisites
Installation
Usage
Uploading Data
Accessing Images

Getting Started
Prerequisites
Before you begin, ensure you have the following prerequisites installed:

Python 3.x
Git
Installation
Clone this repository to your local machine:

bash

git clone https://github.com/EmperorVaibz/cubesat.git
Navigate to the repository directory:

bash

cd XCubed-Data-Images
Create a virtual environment (optional but recommended):

bash

python -m venv venv
Activate the virtual environment:

On Windows:

bash

.\venv\Scripts\activate
On Unix or MacOS:

bash

source venv/bin/activate
Install the required dependencies:

bash

pip install -r requirements.txt
Usage
Uploading Data
To upload new data from XCubed, follow these steps:

Ensure you are in the repository directory and have activated the virtual environment.

Run the data upload script:

bash
Copy code
python upload_data.py
Follow the prompts to input the relevant information.

Accessing Images
To access satellite images, navigate to the images directory. The images are organized by date and satellite pass.
