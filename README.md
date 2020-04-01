# (Work-in-progress) COVID-19 Open API for Cases in Puerto Rico

[The Institute of Statistics of Puerto Rico](https://estadisticas.pr/en) has prepared an open database for COVID-19 cases in Puerto Rico, sourced by the Department of Health. The goal of this project is to offer developers an easy way to access COVID-19 datasets from Puerto Rico. Currently the open database only includes cases from the Department of Health, but please submit an isssue if you have ideas for more. 

![screenshot of covid-19 dataset](docs/img/covid19database.png)

*Data will be uploaded daily from their [website](https://estadisticas.pr/en/covid-19). (Last Updated 4/1/20 7:00 AM).*

## **Disclaimer:** 

The data in this API was sourced from [The Department of Health of Puerto Rico](http://salud.gov.pr/). Data may have errors and/or omissions. 

### GET /cases

Get all current published data about COVID-19 cases in Puerto Rico. 

### GET /cases/:id

Find data about an individual case by number. 

### GET /cases/count

Get total number of cases.
