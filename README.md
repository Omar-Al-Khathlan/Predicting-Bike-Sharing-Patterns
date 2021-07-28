# Deep Learning Nanodegree
# Deep Learning
## Project: Predicting Bike Sharing Patterns

Project for Udacity's Deep Learning Nanodegree program. In this project, I developed code for a deep learning model from scratch, using only matrix manipulation with the NumPy library.

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [sys](https://docs.python.org/3/library/sys.html)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

I recommend installion [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### Code

Template code is provided in the `Your_first_neural_network.ipynb` notebook file and in the `my_answers.py` file.

### Run

In a terminal or command window, navigate to the top-level project directory `Predicting-Bike-Sharing-Patterns/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Your_first_neural_network.ipynb
```  
or
```bash
jupyter notebook Your_first_neural_network.ipynb
```

This will open the iPython Notebook software in your browser.

### Data
The data for this project is present within the Bike-Sharing-Dataset folder. The dataset originally came from here: https://github.com/selva86/datasets/blob/master/BostonHousing.csv
    
**Number of Cases:** 
The dataset contains a total of 17379 cases.

**Features**

- instant: record index
- dteday : date
- season : season (1:winter, 2:spring, 3:summer, 4:fall)
- yr : year (0: 2011, 1:2012)
- mnth : month ( 1 to 12)
- hr : hour (0 to 23)
- holiday : weather day is holiday or not (extracted from [Web Link])
- weekday : day of the week
- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
- weathersit :-
  - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
  - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
  - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
  - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly scale)
- atemp: Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-16, t_max=+50 (only in hourly scale)
- hum: Normalized humidity. The values are divided to 100 (max)
- windspeed: Normalized wind speed. The values are divided to 67 (max)
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered 


### Certification
<p align="middle"><a href="https://github.com/Omar-Al-Khathlan/Predicting-Bike-Sharing-Patterns/blob/main/Certificate/Omar%20Al%20Khathlan%20-%20Udacity%20Certificate%20(Deep%20Learning).pdf"><img src="https://github.com/Omar-Al-Khathlan/Predicting-Bike-Sharing-Patterns/blob/main/Certificate/Omar%20Al%20Khathlan%20-%20Udacity%20Certificate%20(Deep%20Learning).png"/></a></p>
