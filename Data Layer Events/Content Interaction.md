# Content Interaction

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "content_interaction",
  "detailed_event": "Content Interaction",
    "event_data": {
        "archived": <archived>,
        "author": "<author>",
        "author_id": "<author_id>",
        "content_type": "<content_type>",
        "date_published": "<date_published>",
        "format": "<format>",
        "interactive": <interactive>,
        "language": "<language>",
        "method": "<method>",
        "parent": "<parent>",
        "post_id": "<post_id>",
        "project": "<project>",
        "region": "<region>",
        "subtype": "<subtype>",
        "tags": "<tags>",
        "template": "<template>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.archived|boolean|Has the content been archived||||||||
|event_data.author|string|Author||||||||
|event_data.author_id|string|Author ID||||||||
|event_data.content_type|string|Type of content||||||||
|event_data.date_published|string|Captures the publish date of content items \(i.e. article or blog post\).|37247, 40544|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|event_data.format|string|Format||||||||
|event_data.interactive|boolean|Is the content interactive or not.||||||||
|event_data.language|string|Language of the content||||||||
|event_data.method|string|Method||||||||
|event_data.parent|string|Parent||||||||
|event_data.post_id|string|Post ID||||||||
|event_data.project|string|Project||||||||
|event_data.region|string|Region||||||||
|event_data.subtype|string|Subtype||||||||
|event_data.tags|string|Tags||||||||
|event_data.template|string|Template||||||||
|event_data.type|string|Type||||||||




