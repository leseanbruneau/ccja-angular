# CCJA - Angular: Project Description

Code Challenge Journal Application (CCJA) - Angular

Simple Angular application to use routing and external Restful API call to pull in data.

## ccja-angular 

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.2.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Default project setup

git clone https://github.com/leseanbruneau/ccja-angular.git

cd ccja-angular

npm install

ng serve

## Change Data Source

/src/app/components/sprints/sprints.components.ts

Variable sourceData - where data is pulled from; number value
  Options are
  1 - Local Variable
  2 - REST API using a localhost endpoint
  3 - REST API using a remote endpoint

### 1 - Local Variable

Application will pull data from

/src/app/services/local-var-test.service.ts

Data is hard coded - need to recompile when data is updated

### 2 - REST API using a localhost endpoint

Application will pull data from 

/src/app/services/local-var-test.service.ts

Data is hard coded - need to recompile when data is updated

Note:  More information regarding running json-server locally, see

/db/json-server-readme.txt


### 3 - REST API using a remote endpoint

Application will pull data from

/src/app/model/UtilConstants.ts

remoteEndpointApiUrl

This variable will define external endpoint of data.  Intended for an endpoint of external data source.
