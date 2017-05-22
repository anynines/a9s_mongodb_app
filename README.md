# Getting started

## On pass.anynines.com

* Create a service instance of MongoDB

* Export the Service name as an environment variable in the
   manifest.yml files

* Deploy the app (It will most probably fail)

* Bind the service you created to this app

* Re-stage the app

## On your local

* deploy MongoDB bosh release on your local (https://github.com/anynines/mongodb-boshrelease/)

* set the service name as an environment variable (SERVICE_NAME)

* set the VCAP_SERVICES environment variable

* Connect your app to the local deployed service

* Run the rail server

* Open http://localhost:3000/ in your browser
