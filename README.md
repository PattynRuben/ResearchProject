# ResearchProject

Code voor het een onderzoeksproject in verband met een aanbevelingssysteem dat loop- of fietsroutes kan aanraden op basis van hun gebruikersprofiel.

## Installation

- Clone the repository with  ``` git clone https://github.com/PattynRuben/ResearchProject ```
- In order to use the project a recent version of python has to be installed
- In order to use the code in the project, libraries can be installed via ``` python -r requirements.txt ```

## Gebruik

### Uitleg structuur

- Map Data: Contains the data, used in the code of the different code. The data is organised in different submaps
- Map Extradata: Extra code that wasn't , not fully implemented or useful for recommendation systems
* nieuwe_routs.ipynb: code to generate new routes
* ondergrond.ipynb: code to determine ground of routes
* routes_gebruiker.ipynb: visualize routes from a specific user
* stravaprofiel.ipynb: generates a user profile with data from the Strava API
- Map Fietsdata: Contains notebooks with code for a recommendation system to recommend routes to user with a content-based recommendation system
* aanbevelingssysteem.ipynb: code with different implementations of recommendation systems that recomemend routes to users based on userprofile
* analyse_bestand.ipynb: code with analysis of data used in recommmendation sytems
* preprocessing.ipynb: code with preprocessing of source data to data for recommendation system
- Map Loopdata: Contains the data used for the content-based recommendation system to recommend routes 
* aanbevelingssysteem.ipynb: code with different implementations of recommendation systems that recommnd cycling routes to users based on userprofile
* analyse_bestand.ipynb: code with analysis of data used in recommmendation sytems
* preprocessing.ipynb: code with preprocessing of source data to data for recommendation system