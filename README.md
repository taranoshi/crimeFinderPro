# Crime Finder

This project was developed for the Dandyhacks 2018 Hackathon.

This software is designed to work with crime data for Rochester, NY. A few machine learning algorithms analyze the data and learn it in order to make predictions on it, as to what crime is most likely to occur at what time and where that crime is likely to occur. This functionality could be used to enable the Rochester Police Department to make Rochester a safer place for the entirety of the population by monitoring crime-prone areas and enable them to be better prepared for the likely crime to occur.

## Getting Started

This project is not yet ready for professional deployment on host systems. It is rudimentary, but runnable under a host system, it is just the UI is not the most user friendly at the moment.

### Prerequisites

In order to run this project, you will need:
```
Python 3.5 or newer
```
and you will need to install the following python packages, by running the following lines:
```
pip install pandas
pip install sklearn
pip install geoplotlib
pip install googlemaps
pip install tensorflow
pip install matplotlib
```
Unless you already have the packages...in that case, you're pretty cool.

### Installing

At the moment, the best way to "install" this project is to clone it to your drive and to then proceed to run the functions in the following files:
```
data_analyze.py
data_visualizer.py
crime_fighter.py
```

## Running the Tests

We currently do not recommend running the tests, unless you have a buffy machine. This code can take awhile to process all the data. However, if you REALLY want to run the tests, we have a file called: *example.py* for that. The file will generate the graphs used for the demonstration at Dandyhacks. In the future, we hope to add more tests to this example so that you can get a better idea as to how this code functions, and how you too can adapt it to your own personal or public project. Anyway, if you want to run the example, the following command should work, granted you followed our advice about installing necessary packages and cd'd into the directory where you decided to clone this repository ;-)
```
python ./examples.py
```

## Authors

* **Nathan Bunch** - *Repo Builder* - [LinkedIn](https://www.linkedin.com/in/nathan-bunch-024068b6/)

* **Jonathan Povish** - *Data Scientist*

* **Sumayyah Alahmadi** - *Data Visualizer and l33t h4kr*

See also other contributors, if there are more by the time you check out this project, as the list of [contributors](https://github.com/taranoshi/crimeFinderPro/graphs/contributors) may continue to grow...if this project takes off.

## License

This project is licensed under the GNU GPL v3 - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgements

* Inspiration by Dandyhacks, thanks for that ;-).
* Hat tip to our data scientist and data visualizer, you guys are really cool.
* Oh yea, and there's the repo dude.