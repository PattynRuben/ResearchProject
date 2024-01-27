# ResearchProject

This repository contains the code for a research project focused on developing a recommendation system. The system is designed to suggest running or cycling routes based on user profiles.

## Installation

- Clone the repository:
  ```bash
  git clone https://github.com/PattynRuben/ResearchProject
  ```
- Ensure a recent version of Python is installed on your system.
- Install required libraries using:
  ```bash
  python -m pip install -r requirements.txt
  ```

## Usage

### Structure Explanation

- **Data Directory**: This directory contains all the data used in various scripts of the project. The data is organized into different subdirectories.
- **Extradata Directory**: Includes additional scripts that were either experimental, not fully implemented, or not directly related to the recommendation systems. It contains:
  - `nieuwe_routes.ipynb`: Script to generate new routes.
  - `ondergrond.ipynb`: Script to determine the ground type of routes.
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

This organized structure ensures easy navigation and understanding of the different components of the research project.