# Location-Service-REST-API

# Basic Design of a location service REST API

To reduce workload: 

-simulate the drivers' location. 
-save the drivers' location in cache, no implement of database.

        *  POST to /drivers to create a driver 
        *  GET to /drivers/{id} to view a driver 
        *  POST to /drivers/{id}/locations to update current location 
        *  GET to /drivers/{id}/locations to view all historical locations for a driver 
        *  PUT to /drivers/{id}/locations/{locationId} to update a location 
             
        *  GET to /drivers/{id}/locations/{locationId} to view a specific location by Id.
        *  GET to /drivers/{id}/locations/current to view the current location
        *  DELETE to /drivers/{id}/locations/{locationId} to delete a location
        *  POST to /drivers/{id}/locations/{locationId}/delete to delete a location

