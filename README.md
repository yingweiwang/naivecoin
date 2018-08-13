# Dewcoin 

Dewcoin is a blockchain cryptocurrency system that is based on dew computing principles. The code is pretty detailed but still not detailed enough for immediate production operation. It is basically a Proof of Concept system. 

The mechanism of dewcoin will be introduced separately. Some information about dew computing can be found in: http://www.dewcomputing.org/

Dewcoin is based on Naivecoin. The introduction of Naivecoin can be found in: A tutorial for building a cryptocurrency https://lhartikk.github.io/


## Package Placement

Dewcoin has two components: the cloud package and the dew package. Ideally, the cloud package should be installed in a computer that is running all the time and has a fixed IP address so that it can be accessed easily. The dew package can be installed in a locally computer. For testing purposes, the cloud package and the dew package can be put in the same computer. 

## Package Configuraton

Configuraton files:
dewcoin-dew/src/config.ts
dewcoin-cloud/src/config.ts

Detailed configuration guidelines can be found in these files.


## Package Installation

Both packages should be installed in the Node.js environment. 

Installation command: 
```
npm install
```
Running command: 
```
npm start
```
## Dewcoin Operation

Dewcoin system can be operated through an API composed of a group of HTTP commands. These commands can be issued through browsers, designed web forms, HTTP clients such as curl.

We use curl to describe the API, but it does not mean curl is the only way to operate Dewcoin.

