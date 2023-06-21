# Contact Us Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "contact_us_complete",
  "detailed_event": "Contact Us Completed",
    "event_data": {
        "author": "<author>",
        "contact_purpose": "<contact_purpose>",
        "method": "<method>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.author|string|The expert\(s\) who have created the content; can include a comma separated list of authors|Sandra Rozo, Hernan Winkler|||||||
|event_data.contact_purpose|string|Captures the reason that a visitor submitted a Contact Us form.|General Inquiry, Order Status, Legal, Other|||||||
|event_data.method|string|Captures the website method \(i.e. search, top nav\) used to find each product.|email, facebook, twitter|||||||




