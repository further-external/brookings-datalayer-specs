# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_load_started",
  "detailed_event": "Page Load Started",
    "event_data": {
        "archived": <archived>,
        "author": "<author>",
        "author_id": "<author_id>",
        "author_type": "<author_type>",
        "center": "<center>",
        "chart_id": "<chart_id>",
        "content_type": "<content_type>",
        "email_subscribers": <email_subscribers>,
        "historical_url": "<historical_url>",
        "interactive": <interactive>,
        "original_post_id": "<original_post_id>",
        "parent": "<parent>",
        "post_id": "<post_id>",
        "primary_topic": "<primary_topic>",
        "program": "<program>",
        "project": "<project>",
        "publish_date": "<publish_date>",
        "region": "<region>",
        "subtype": "<subtype>",
        "tag_id": "<tag_id>",
        "tags": "<tags>",
        "template": "<template>",
        "topic": "<topic>",
        "type": "<type>",
        "word_count": "<word_count>"
    },
    "page_data": {
        "language": "<language>",
        "name": "<name>",
        "page_location": "<page_location>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.archived|boolean|Whether the content has been archived|Yes, No|||||||
|event_data.author|string|The expert\(s\) who have created the content; can include a comma separated list of authors|Sandra Rozo, Hernan Winkler|||||||
|event_data.author_id|string|ID for distinct author in Wordpress||||||||
|event_data.author_type|string|Describes the type of author|Guest Author, Expert, Leadership|||||||
|event_data.center|string|Collection of topics and fellows organized under a program|The Katzmann Initiative|||||||
|event_data.chart_id|string|From Data Wrapper||||||||
|event_data.content_type|string|Captures the content category like post, essay, or research|post|||||||
|event_data.email_subscribers|integer|Boolean value to segment users who have subscribed to a newsletter|yes|||||||
|event_data.historical_url|string|URL of post from historical site|\/research\/what-caused-the-u-s-pandemic-era-inflation\/|||||||
|event_data.interactive|boolean|Whether it is interactive content|Yes, No|||||||
|event_data.original_post_id|string|Original Post ID from historical site|20619|||||||
|event_data.parent|string|"Parent" dropdown in the Post Options panel of the Wordpress Editor UI|Events, Experts, Home|||||||
|event_data.post_id|string|Unique content identifier|617631|||||||
|event_data.primary_topic|string|Primary value selected in the CMS|Global Economy|||||||
|event_data.program|string|Captures the research program for the content|Global Economy and Development|||||||
|event_data.project|string|Initiatives tied to a research program|Brookings Economic and Social Policy in Latin America Initiative|||||||
|event_data.publish_date|string|Date the content was published.|2019-10-11|||||||
|event_data.region|string|Geo|Africa, Asia & the Pacific|||||||
|event_data.subtype|string|Subtype of post|Op-ed, Podcast, Testimony|||||||
|event_data.tag_id|string|ID for distinct tag in Wordpress||||||||
|event_data.tags|string|From Wordpress Post Editor under the "Tags" dropdown within the format dialogue. Covers "Series", "Blog".|17 Rooms Podcast, Africa in Focus|||||||
|event_data.template|string|Template type in Wordpress|Research & Commentary Landing|||||||
|event_data.topic|string|List of comma separated themes that can be shared between programs|Colombia, Global Economy|||||||
|event_data.type|string|Type of post|Commentary, Research|||||||
|event_data.word_count|string|Total word count for content|389|||||||
|page_data.language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.|en-us, en-gb, ch-cn, fr-ca, fr-fr|||||||
|page_data.name|string|Captures the name of the page the user is on|product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page_data.page_location|string|The URL of the page currently being viewed. This value will include the full, unaltered URL of the page\/screen the user is currently viewing, including query parameters, fragments, etc., for example https:\/\/www.example.com\/home?user=true&audience=test\#aboutus.|https:\/\/www.example.com\/home?user=true&audience=test\#aboutus|||||||




