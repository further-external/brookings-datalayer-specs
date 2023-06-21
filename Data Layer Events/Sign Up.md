# Sign Up

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "sign_up",
  "detailed_event": "Sign Up",
    "event_data": {
        "event_count": "<event_count>",
        "newsletter_name": "<newsletter_name>",
        "program": "<program>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.program|string|Captures the research program for the content|Global Economy and Development|||||||




