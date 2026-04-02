**Note**  
`Only rest api with https support can be deployed behind API/ML, make sure to enable https support in your rest api.
`   
This sample express app, has https enabled already.    

##  Build on local

###  Clone the repository, install node packages  and verify routes locally

``` 
//on local
cd node-api
npm install
npm start
```

Open your local browser and verify the sample-node-api is working by accessing:     
`http://localhost:18000/accounts/`   
`http://localhost:18000/accounts/1`   
`http://localhost:18000/accounts/1/cars/`   
