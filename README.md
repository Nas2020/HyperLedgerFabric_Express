## HyperLedgerFabric_Express
BCDV1012 - Lab: ExpressJS REST API for HyperLedger Fabric (fabcar example) [as part of BCDV1012 Lab of Blockchain Development Program @  <a href='https://www.georgebrown.ca'>George Brown College</a>].

## Procedure

Clone this repository to 'fabcar' folder 'fabric-smples'(https://github.com/hyperledger/fabric-samples) 

* `npm install`
* `node app.js` 

To Query all the cars: http://[lpocalhost]:3000/api/queryallcars 
To Add new car: http://localhost:3000/api/addcar (static for testing purpose only) 
        To change Car's attribute  "await contract.submitTransaction('createCar', 'CAR98', 'Honda', 'City', 'Black', 'Nas');" change here.

#### Limitation
* Simple ExpressJs-HFL REST API for training purpose only.

## Resources and References:

* [ExpressJs](https://expressjs.com/)
* [HyperLedger Fabric](https://hyperledger-fabric.readthedocs.io/en/latest/write_first_app.html)
* [GCP](https://console.cloud.google.com/compute/metadata/sshKeys?project=thematic-vertex-269707&authuser=1)

## Credit

* Professor Tarun @ George Brown College.
* KC Tam @ Medium.com https://medium.com/@kctheservant/an-implementation-of-api-server-for-hyperledger-fabric-network-8764c79f1a87.
