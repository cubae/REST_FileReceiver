# REST_FileReceiver
File receiving via REST resource on TIBCO BWCE
- HTTPServer.bwp is working
- RESTServer.bwp is not working. Error message is [here.](./err/BusinessStudio_console.log)

# REST or HTTP call via curl
```
curl --location --request POST 'http://localhost:8080/restserver' \
--form 'fileText=@/D:/sample.txt'
```

# Postman response 500 Internal Server Error
Error message is [here.](./err/Postman_Response_500.log)
