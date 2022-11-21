---
permalink: /misc
layout: page
title: Misc
---
# Misc
![Misc](https://telegra.ph/file/f55de9a42e9a3ce94b29d.jpg)

---
## /quotly 
### HTTP Request
`GET https://weeb-api.up.railway.app/quotly?pfp=https://telegra.ph/file/e991bb4b535a0f1425aa0.jpg&username=Texas&text=Hello_World`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| pfp       | true     | `string` | profile pic url |
| username  | true     | `string` | your username |
| text      | true     | `string` | your text message | 

> The response schema would be like this:

![Buffer.png](https://telegra.ph/file/ceff40e9d9d0c3f8c3a50.png)
---

---
## /ytsearch
### HTTP Request
`GET https://weeb-api.up.railway.app/ytsearch?query=let me down slowly`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| query     | true     | `string` | video name you are looking for |

> The response schema would be like this:

```JSON
[
   {
      "type":"video",
      "videoId":"PwsbuzLgIZM",
      "url":"https://youtube.com/watch?v=PwsbuzLgIZM",
      "title":"Alec Benjamin - Let Me Down Slowly (Lyrics)",
      "description":"Alec Benjamin - Let Me Down Slowly (Lyrics) ⬇️ Download / Stream: https://lnk.to/LetMeDownSlowly Turn on notifications to ...",
      "image":"https://i.ytimg.com/vi/PwsbuzLgIZM/hq720.jpg",
      "thumbnail":"https://i.ytimg.com/vi/PwsbuzLgIZM/hq720.jpg",
      "seconds":167,
      "timestamp":"2:47",
      "duration":{
         "seconds":167,
         "timestamp":"2:47"
      },
      "ago":"1 day ago",
      "views":31284,
      "author":{
         "name":"Royal Music",
         "url":"https://youtube.com/@royalmusicyt"
      }
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   },
   {
      ...
   }
]
```
---
