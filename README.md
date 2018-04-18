# zcash-rates-api
A Restful API that displays current ZCASH exchange Rates

## Requirements
Requires node version 6.0 and above

## Installation
Install npm dependencies with command:
```
npm install
```

## Usage
Start the service with command:
```
npm start
```

After the service has been started, you should be able to browse to it on port 3333.
Example: http://localhost:3333/rates

## Docker
To build the docker image run with command:
```
docker build -t zcash/zcash-rates-api .
```

Then run the docker image with command:
```
docker run -d --restart always -p 3333:3333 --name zcash-rates-api zcash/zcash-rates-api
```
