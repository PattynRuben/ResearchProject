# ResearchProject

This repository is dedicated to a research project that develops advanced recommendation systems. These systems are specifically tailored to suggest running or cycling routes to users. The recommendations are made based on the users' individual profiles, employing content-based recommender systems to provide personalized route suggestions.

## Installation

- Clone the repository:
  ```bash
  git clone https://github.com/PattynRuben/ResearchProject
  ```
- Ensure a recent version of Python is installed on your system. The code for this project was developped in Python version 3.10.11. 
- Install required libraries using:
  ```bash
  python -m pip install -r requirements.txt
  ```

### Optional: Setting up a virtual environment

While it's not mandatory, it's a good practice to create a virtual environment for your project. This isolates your project and its dependencies from the rest of your system. To set up a virtual environment, follow these steps:
- Create a new virtual environment
  ```bash
  python -m pip install -r requirements.txt
  ```
- Activate the virtual environment:
  - On Windows
      ```bash
      venv\Scripts\activate
      ```
  - On Unix or MacOs:
      ```bash
      source venv/bin/activate
      ```
- You should now see (venv) in your command line, indicating that the virtual environment is active.
- Install required libraries using:
  ```bash
  python -m pip install -r requirements.txt
  ```
## Usage

### Structure Explanation

- **Data Directory**: This directory contains all the data used in various scripts of the project. The data is organized into different subdirectories.
- **Extradata Directory**: Includes additional scripts that were either experimental, not fully implemented, or not directly related to the recommendation systems. It contains:
  - `fietsaanbevelingssysteem.ipynb`: Implementation of recommendation system that will recommend bike routes based on user profile
  - `loopaanbevelingssysteem.ipynb`: Implementation of recommendation system that will recommend run routes based on user profile
  - `nieuwe_routes.ipynb`: Testcode to generate new routes
  - `ondergrond.ipynb`: Script to determine the most common type ground/roads of routes.
  - `routes_gebruiker.ipynb`: Visualizes routes from a specific user.
  - `stravaprofiel.ipynb`: Generates a user profile using data from the Strava API.
- **Fietsdata Directory**: Contains notebooks with code for a content-based recommendation system, specifically for recommending cycling routes. It includes:
  - `aanbevelingssysteem.ipynb`: Implementation of different recommendation systems that suggest routes based on the user's profile.
  - `analyse_bestand.ipynb`: Analysis of data used in the recommendation systems.
  - `preprocessing.ipynb`: Preprocessing of source data for the recommendation system, including the creation of user profiles and item profiles.
- **Loopdata Directory**: This directory holds the data and scripts for the content-based recommendation system for running routes. It includes:
  - `aanbevelingssysteem.ipynb`: Various implementations of recommendation systems that recommend running routes to users based on their profiles.
  - `analyse_bestand.ipynb`: Analysis of data used in the recommendation systems.
  - `preprocessing.ipynb`: Preprocessing of source data for the recommendation system, including the creation of user profiles and item profiles.
  - `testcode.ipynb`: Implementations of recommender systems that were tested or didn't work very well.

### Use of recommendation sytems

After installing the repository and ensuring Python and necessary libraries are set up on your system, you can use the code in the aanbevelingssysteem.ipynb files found in the directories to generate and evaluate recommended routes for users.

- Modify the userId in the code to view recommendations for different users from the dataset.
- Personal activities/data can also be leveraged for route recommendations. This data can be sourced from the Strava API in JSON format.
- The stravaprofiel.ipynb file includes a script to create a user profile from activity data, which is then can be used to generate new route suggestions.