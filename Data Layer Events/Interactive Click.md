# Interactive Click

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "interactive_click",
  "detailed_event": "Interactive Click",
     "event_data": {
        "archived": "<archived>",
        "author": "<author>",
        "author_id": "<author_id>",
        "center": "<center>",
        "chart_name": "<chart_name>",
        "chart_id": "<chart_id>",
        "content_type": "<content_type>",
        "format": "<format>",
        "historical_url": "<historical_url>",
        "identifier": "<identifier>",
        "interactive": "<interactive>",
        "interactive_name": "<interactive_name>",
        "interactive_type": "<interactive_type>",
        "language": "<language>",
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
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.archived|boolean|Whether the content has been archived|Yes, No|||||||
|event_data.author|string|The expert\(s\) who have created the content; can include a comma separated list of authors|Sandra Rozo, Hernan Winkler|||||||
|event_data.author_id|string|ID for distinct author in Wordpress||||||||
|event_data.center|string|Collection of topics and fellows organized under a program|The Katzmann Initiative|||||||
|event_data.chart_id|string|From Data Wrapper||||||||
|event_data.content_type|string|Captures the content category like post, essay, or research|post|||||||
|event_data.email_subscribers|integer|Boolean value to segment users who have subscribed to a newsletter|yes|||||||
|event_data.format|string|Post type|Page, Landing Page, Article, Event, Collection, Book and News|||||||
|event_data.historical_url|string|URL of post from historical site|\/research\/what-caused-the-u-s-pandemic-era-inflation\/|||||||
|event_data.identifier|string|Captures the ID associated with CTA links used.|act now, cancel, ok, 3456, 8765|||||||
|event_data.interactive|boolean|Whether it is interactive content|Yes, No|||||||
|event_data.language|string|Language in which the content is viewed|en|||||||
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






