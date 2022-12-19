# User Registration Errored

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Registration Errored",
    "user": {
        "registrationError": "<registrationError>",
        "registrationType": "<registrationType>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.registrationError|string|Captures the registration error code or message associated with user registrations.|Form is incomplete, EC345, Invalid field entry|||||||
|user.registrationType|string|Describes the thing that was registered for |account, loyalty program, event, sweepstakes, warranty|||||||




