## Postman training 2

Endpoint: http://3.13.86.142:3000/contacts/

1. Add a new POST request to the Negative Tests folder;
the request should result in some type of validation error.

2. Add a body-type assertion to the request to validate that the appropriate error message is returned

You can run your collection in *Postman* or with *newman* from the command line:  
open a command prompt in your working directory where your postman collection and environment are located and run the following command    
```newman run Contact_List.postman_collection.json -e Contact_List.postman_environment.json```

![newman run](/training-2/newman_run_screenshot.jpg "test")