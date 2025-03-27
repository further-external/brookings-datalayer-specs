# Navigation Click

### 

## Site Sections

| Description | GA4 Event | GA4 Custom Dimension |
| --- | --- | --- |
| Main Menu | navigation_click | module_name=`primary`| 
| Main Menu | navigation_click | module_name=`secondary`| 
| Main Menu | navigation_click | module_name=`featured_posts`| 
| Main Menu | navigation_click | module_name=`topics_submenu`| 
| Main Menu | navigation_click | module_name=`regions_submenu`| 
| In-Page Sections: Table of Contents | navigation_click | module_name=`table_of_contents_static`| 
| In-Page Sections: Table of Contents (Sticky/Flyout) | navigation_click | module_name=`table_of_contents_sticky`| 
| In-Page Sections: Tabs | navigation_click | module_name=`tabs`| 
| In-Page Sections: Read More On - Widget | navigation_click | module_name=`read_more_widget`| 
| In-Page Sections: Read More On - Right Rail | navigation_click | module_name=`read_more_rail`| 
| In-Page Sections: Read More On - Footer | navigation_click | module_name=`read_more_footer`| 

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
        "module_campaign": "<module_campaign>",
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
|event_data.module_campaign|string|Associates CTA to a particular module campaign|Election 2024|||||||
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

## Module Examples

Secondary Navigation
<img width="1012" alt="Screen Shot 2025-03-19 at 11 23 54 PM" src="https://github.com/user-attachments/assets/bdd922b3-8fca-47e7-b359-66b1b82b3827" />

Featured Posts

<img width="1393" alt="Screen Shot 2025-03-19 at 11 15 25 PM" src="https://github.com/user-attachments/assets/2105521a-a08e-4331-b393-9f7750c30d01" />

Topics Submenu

<img width="1761" alt="Screen Shot 2025-03-19 at 11 15 32 PM" src="https://github.com/user-attachments/assets/48859a17-52b4-4783-9bae-ae1c718ea4bd" />

Regions Submenu

<img width="1761" alt="Screen Shot 2025-03-19 at 11 15 32 PM" src="https://github.com/user-attachments/assets/98bd9a27-87ac-472e-9536-32298d7311a4" />

Table of Contents (Static)

<img width="249" alt="Screen Shot 2025-03-19 at 11 32 28 PM" src="https://github.com/user-attachments/assets/a0bd8f1a-35dd-427b-b145-6398f9f0ea53" />

Table of Contents (Sticky or Flyout)

<img width="305" alt="Screen Shot 2025-03-19 at 11 32 20 PM" src="https://github.com/user-attachments/assets/a070f6e2-f2f1-4192-aeda-11e9c0091c4e" />

Tabs

<img width="1655" alt="Screen Shot 2025-03-19 at 11 33 11 PM" src="https://github.com/user-attachments/assets/f319d5b6-0ec1-4913-b167-e2c5eb42b2f6" />
