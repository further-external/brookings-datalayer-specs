# Register Event

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "register_event",
  "detailed_event": "Register Event",
    "event_data": {
        "event_count": "<event_count>",
        "event_name": "<event_name>",
        "identifier": "<identifier>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.event_name|string|Event Name||||||||
|event_data.identifier|string|Captures the ID associated with exit links used. |act now, cancel, ok, 3456, 8765|||||||




