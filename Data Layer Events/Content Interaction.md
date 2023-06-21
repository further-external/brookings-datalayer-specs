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
|event_data.archived|boolean|Whether the content has been archived|Yes, No|||||||
|event_data.author|string|The expert\(s\) who have created the content; can include a comma separated list of authors|Sandra Rozo, Hernan Winkler|||||||
|event_data.author_id|string|ID for distinct author in Wordpress||||||||
|event_data.content_type|string|Captures the content category like post, essay, or research|post|||||||
|event_data.date_published|string|Captures the publish date of content items \(i.e. article or blog post\).|37247, 40544|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|event_data.format|string|Post type|Page, Landing Page, Article, Event, Collection, Book and News|||||||
|event_data.interactive|boolean|Whether it is interactive content|Yes, No|||||||
|event_data.language|string|Language in which the content is viewed|en|||||||
|event_data.method|string|Method||||||||
|event_data.parent|string|"Parent" dropdown in the Post Options panel of the Wordpress Editor UI|Events, Experts, Home|||||||
|event_data.post_id|string|Unique content identifier|617631|||||||
|event_data.project|string|Initiatives tied to a research program|Brookings Economic and Social Policy in Latin America Initiative|||||||
|event_data.region|string|Geo|Africa, Asia & the Pacific|||||||
|event_data.subtype|string|Subtype of post|Op-ed, Podcast, Testimony|||||||
|event_data.tags|string|From Wordpress Post Editor under the "Tags" dropdown within the format dialogue. Covers "Series", "Blog".|17 Rooms Podcast, Africa in Focus|||||||
|event_data.template|string|Template type in Wordpress|Research & Commentary Landing|||||||
|event_data.type|string|Type of post|Commentary, Research|||||||




