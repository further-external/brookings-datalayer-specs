# Navigation Click

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "navigation_click",
  "detailed_event": "Navigation Click",
    "event_data": {
        "archived": <archived>,
        "author": "<author>",
        "author_id": "<author_id>",
        "author_type": "<author_type>",
        "center": "<center>",
        "format": "<format>",
        "historical_url": "<historical_url>",
        "language": "<language>",
        "module_link": "<module_link>",
        "module_name": "<module_name>",
        "module_text": "<module_text>",
        "original_post_id": "<original_post_id>",
        "parent": "<parent>",
        "post_id": "<post_id>",
        "primary_topic": "<primary_topic>",
        "project": "<project>",
        "publish_date": "<publish_date>",
        "region": "<region>",
        "subtype": "<subtype>",
        "tag_id": "<tag_id>",
        "tags": "<tags>",
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
|event_data.author_type|string|Describes the type of author|Guest Author, Expert, Leadership|||||||
|event_data.center|string|Collection of topics and fellows organized under a program|The Katzmann Initiative|||||||
|event_data.format|string|Post type|Page, Landing Page, Article, Event, Collection, Book and News|||||||
|event_data.historical_url|string|URL of post from historical site|\/research\/what-caused-the-u-s-pandemic-era-inflation\/|||||||
|event_data.language|string|Language in which the content is viewed|en|||||||
|event_data.module_link|string|URL for module|https:\/\/www.brookings.edu\/articles\/tracking-the-invisible-primary-money-cant-buy-a-presidential-nomination\/|||||||
|event_data.module_name|string|Name of content module on homepage. e.g. Hero, Events, Latest Research|hero, events, latest research|||||||
|event_data.module_text|string|Captures the readable text \(either article headline, menu name, or other call-to-action\) in a module||||||||
|event_data.original_post_id|string|Original Post ID from historical site|20619|||||||
|event_data.parent|string|"Parent" dropdown in the Post Options panel of the Wordpress Editor UI|Events, Experts, Home|||||||
|event_data.post_id|string|Unique content identifier|617631|||||||
|event_data.primary_topic|string|Primary value selected in the CMS|Global Economy|||||||
|event_data.project|string|Initiatives tied to a research program|Brookings Economic and Social Policy in Latin America Initiative|||||||
|event_data.publish_date|string|Date the content was published.|2019-10-11|||||||
|event_data.region|string|Geo|Africa, Asia & the Pacific|||||||
|event_data.subtype|string|Subtype of post|Op-ed, Podcast, Testimony|||||||
|event_data.tag_id|string|ID for distinct tag in Wordpress||||||||
|event_data.tags|string|From Wordpress Post Editor under the "Tags" dropdown within the format dialogue. Covers "Series", "Blog".|17 Rooms Podcast, Africa in Focus|||||||
|event_data.topic|string|List of comma separated themes that can be shared between programs|Colombia, Global Economy|||||||
|event_data.type|string|Type of post|Commentary, Research|||||||
|event_data.word_count|string|Total word count for content|389|||||||




