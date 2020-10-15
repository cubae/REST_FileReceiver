# REST_FileReceiver
File receiving via REST resource on TIBCO BWCE
- HTTPServer.bwp is working
- RESTServer.bwp is not working. Error message is [here]:./err/console.log

# call via curl
```
curl --location --request POST 'http://localhost:8080/restserver' \
--form 'fileText=@/D:/sample.txt'
```
