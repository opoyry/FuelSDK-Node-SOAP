# FuelSDK-Node-SOAP

Merged changes from https://github.com/salesforce-marketingcloud/FuelSDK-Node-SOAP/pull/69/commits/d95a6f8f47e1fdc23ecf0868b95e43e9297f06d7 into https://github.com/salesforce-marketingcloud/FuelSDK-Node-SOAP

Use continueRequest to allow fetching more than 2500 records

```
body.RetrieveRequestMsg.RetrieveRequest.ContinueRequest = continueRequest; // continueRequest == the RequestID
```

See https://code.exacttarget.com/apis-sdks/soap-api/retrieving-more-than-2500-records-using-the-continuerequest-property.html
