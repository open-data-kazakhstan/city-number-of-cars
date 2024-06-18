# city-avg-salary

## Description
Main data are in the file `car-amount-rate.csv` and column car-amount-rate describes amount of car for 1000 people by [eurostat](https://ec.europa.eu/eurostat/web/products-eurostat-news/w/ddn-20240117-1) standarts

## Installation 

Clone the repository
```shell
https://github.com/open-data-kazakhstan/city-number-of-cars.git
```
Requires Python 3. 

Create a virtual environment and activate it 
```bash
pip install venv
python -m venv /path/to/localrepo
```

Swicth to venv directory by using cd comand
```bash
cd /path/to/localrepo
Scripts/activate
```

Install dependecies in venv by using pip
```bash
pip install -r requirements.txt
```

Run the project:
```bash
python scripts/process.py
```

## Data 

Data collected from https://stat.gov.kz

We extracted the data from these sources and put it in the acrhive folder as quarters.xlsx .

We processed the original data to bring them back to normal, and extracted several aggregated datasets from them into the Data folder:

* `car2022.xlsx` - contains information of 2022 year 
* `datapackage.json` - contains all the key information about our dataset
* `car-amount-rate.csv` - contains data about number of cars for 1000 people
* `city_population` - data about population in each region collected from repository [city-population](https://github.com/open-data-kazakhstan/city-population)

## Scripts

* `process.py ` - runs the script

## License

This dataset is licensed under the Open Data Commons [Public Domain and Dedication License][pddl].

[pddl]: https://www.opendatacommons.org/licenses/pddl/1-0/
