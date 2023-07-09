---
permalink: /entertainment
layout: page
title: Entertainment Endpoints
---

---
## /quotly 
### HTTP Request
`GET https://weeb-api.vercel.app/quotly?pfp=https://telegra.ph/file/e991bb4b535a0f1425aa0.jpg&username=Texas&text=Hello_World`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| pfp       | true     | `string` | profile pic url |
| username  | true     | `string` | your username |
| text      | true     | `string` | your text message | 

### Response Buffer
> The response Buffer would be like this:
![Buffer.png](https://telegra.ph/file/ceff40e9d9d0c3f8c3a50.png)
---

## /stickerly
### HTTP Request
`GET https://weeb-api.vercel.app/stickerly?url=https://sticker.ly/s/8QURB5`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| url       | true     | `string` | stickerly pack url |

> The response schema would be like this:

```json
{
   "title":"Xiao Li Zi",
   "author":"nyaughh",
   "animated":false,
   "stickers":[
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1679183512308.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1679183513727.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1679183514481.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1679183515308.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1679183516554.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1679183517282.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1679183517989.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1679183518780.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1679183520259.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1886130073.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1887832010.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/-1611182082.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681750409570.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681750410891.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681750411504.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681750412260.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681750413060.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681750413736.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681750414644.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681750415446.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681750734989.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681750735484.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681750735913.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681751050187.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681751050888.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/1681751051616.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/468254801.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/527452586.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/554076939.png",
      "https://stickerly.pstatic.net/sticker_pack/ZNxQnuKljwMjq6MOz72LA/8QURB5/45/604849415.png"
   ]
}
```
---
