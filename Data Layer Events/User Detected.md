# User Detected

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Detected",
    "user": {
        "employeeID": "<employeeID>",
        "loyalty": {
            "memberId": "<memberId>"
        },
        "profileAttributesList": "<profileAttributesList>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.employeeID|string|The employee ID associated with user activity.||||||||
|user.loyalty.memberId|string|Member Identifier in a Loyalty program|abc1234, def876, 87987659|||||||
|user.profileAttributesList|string|A twice delimited string of key \/ value pairs.  Use \~ between key and value.  Use \| between pairs|homeStore\~234\|loyaltyTier\~gold\|memberSince\~2002|||||||




