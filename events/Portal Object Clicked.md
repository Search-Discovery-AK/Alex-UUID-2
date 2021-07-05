# Portal Object Clicked

### 

## Javascript Code
```js
window.appEventDataUUID2 = window.appEventDataUUID2 || [];
appEventDataUUID2.push({
  "event": "Portal Object Clicked",
    "portalObjectClicked": {
        "portalObject": [
            {
                "portalObjectId": "<portalObjectId>"
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|portalObjectId|string|Unique identifier of a portal object|My Accounts, Transactions, Messages, My Reports|||||||
