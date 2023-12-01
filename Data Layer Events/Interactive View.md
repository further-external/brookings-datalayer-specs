# Interactive View

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "interactive_view",
  "detailed_event": "Interactive View",
    "event_data": {
        "interactive_name": "<interactive_name>",
        "interactive_type": "<interactive_type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.interactive_name|string|Name of chart||||||||
|event_data.interactive_type|string|Type of chart used in visualization||||||||




