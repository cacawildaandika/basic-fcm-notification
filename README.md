# basic-send-fcm-notification

## Method : POST
## Url : https://fcm.googleapis.com/fcm/send
## Json Body : 
```
{
    "to" : "CLIENT-TOKEN",
    "notification" : {
        "title": "YOUR-TITLE",
        "body" : "YOUR-BODY",
        "shipmentWallNumber" : SHIPMENT-NUMBER
    },
    "data" : {
        "foo" : "bar",
        "john" : "doe"
    }
}
```
