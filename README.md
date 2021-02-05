# test

Project Contains ContactApi to test it run in visual studio.
Project is using Unit of work pattern to ensure all respective repositories are updated. In our case we have only ContactRepository.But in practically there might be multiple
related repositories like Address Repository this framework ensure data integrity.
Project Contains unit test case for each framwork modules files.

To test post request, you can use postman and modify below json to test it
URL to use http://localhost:54201/Cotact

{
        "id": 2,
        "firstName": "Test again",
        "lastName": "Test2",
        "email": "sd@com",
        "phone": "98734562",
        "isActive": false
}
    
