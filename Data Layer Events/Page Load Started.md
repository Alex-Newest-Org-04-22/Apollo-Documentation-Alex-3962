# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_view",
  "detailed_event": "Page Load Started",
    "page_data": {
        "country": "<country>",
        "language": "<language>",
        "name": "<name>",
        "page_location": "<page_location>",
        "site_name": "<site_name>",
        "site_type": "<site_type>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page_data.country|string|The country the site is associated with.||||||||
|page_data.language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.||||||||
|page_data.name|string|Captures the name of the page the user is on|product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page_data.page_location|string|The url of the page currently being viewed.||||||||
|page_data.site_name|string|Common language used within the business to refer to the website. May be specific County Sites.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|page_data.site_type|string|Common language description of the site type of purpose. May be used to group siteName.|Prospecting, Shop, Members, Brand|||||||




