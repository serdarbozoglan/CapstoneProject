# Data Wrangling

The steps I follwed through data wranling part of the project shown below:

1. Converting data types
2. Checking duplicating values
3. Going over data points for every feature
4. Cleaning Outliers
5. Getting rid of null/missing values 
6. Feature Enginerring

## 1. Converting Data Types

  ### A. DateTime Object: 
  
  In the original dataset date time feature were saved as object/string, we changed those columns into data time object.

  ### B. Integer :
  
  Target column (Cancelled) was type of float, we converted it into integer.

## 2. Checking Duplicating Values

We checked for duplication and confirmed we did not have any duplicate values.

## 3. Going Over Data Points for Every Feature

We examined every feature of dataset in terms of data sanity. Some columns were regarded as unnecessary for cancellation prediction and were dropped. Some other columns belonged to actual happened flights and those columns were also dropped. Some columns were dropped after EDA and those are the columns dropped in total `[LongestAddGTime, TotalAddGTime, FirstDepTime, CancellationCode, LateAircraftDelay, SecurityDelay, NASDelay, WeatherDelay, CarrierDelay, Year, Quater, Month, DayofMonth, DayOfWeek, FlightDate, OriginCityName, OriginState, DestCityName, DestState, CRSDepTime, DepTime, DepDelay, DepDel15, DepartureDelayGroups, DepTimeBlk, WheelsOff, WheelOn, TaxiIn, CRSArrTime, ArrTime, AirTime, ArrDelay, ArrDelayMinutes, ArrDel15, ArrivalDelayGroups, ArrTimeBlk, ActualElapsedTime, Company, Distance]`

## 4. Cleansing Outliers

## 5. Getting Rid of Null/Missing Values

## 6. Feature Engineering


### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
asd
