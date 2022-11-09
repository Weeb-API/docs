---
permalink: /weeb
layout: page
title: Weeb
---
# Weeb
![Weeb](https://telegra.ph/file/52355be7fdd16b3c8d2c9.jpg)

## /anime
### HTTP Request
`GET https://weeb-api.up.railway.app/anime?search=rent-a-girlfriend`

### Query Parameters

| Parameter | Required | Description |
|    ---    |    ---   |     ---     | 
| search    | true     | Anime information from Anilist | 

> The response schema would be like this:

```JSON
[
   {
      "id":113813,
      "idMal":40839,
      "title":{
         "romaji":"Kanojo, Okarishimasu",
         "english":"Rent-a-Girlfriend",
         "native":"彼女、お借りします"
      },
      "status":"FINISHED",
      "hashtag":"#彼女お借りします #かのかり",
      "format":"TV",
      "isAdult":false,
      "season":"SUMMER",
      "nextAiringEpisode":null,
      "averageScore":69,
      "popularity":191825,
      "source":"MANGA",
      "duration":24,
      "episodes":12,
      "genres":[
         "Comedy",
         "Drama",
         "Romance"
      ],
      "countryOfOrigin":"JP",
      "startDate":"11-7-2020",
      "endDate":"26-9-2020",
      "studios":"TMS Entertainment, DMM pictures, Kodansha, Mainichi Broadcasting System",
      "trailer":{
         "id":"jZFEtc3CKHs",
         "site":"youtube",
         "thumbnail":"https://i.ytimg.com/vi/jZFEtc3CKHs/hqdefault.jpg"
      },
      "siteUrl":"https://anilist.co/anime/113813",
      "imageUrl":"https://img.anili.st/media/113813",
      "bannerImage":"https://s4.anilist.co/file/anilistcdn/media/anime/banner/113813-Al8VofQuNQHV.jpg",
      "coverImage":{
         "extraLarge":"https://s4.anilist.co/file/anilistcdn/media/anime/cover/large/bx113813-UCgSIGyWvLgl.jpg"
      },
      "description":"In today’s Japan, “rental” services can deliver an afternoon with a “friend,” a “parent,” even a fake girlfriend! After a staggering betrayal by his girlfriend, hapless freshman Kazuya gets just desperate enough to give it a try. But he quickly discovers how complicated it can be to “rent” an emotional connection, and his new “girlfriend,” who’s trying to keep her side hustle secret, will panic when she finds out her real life and Kazuya’s are intertwined in surprising ways! Family, school, and life all start to go wrong, too…\n<br><br>\n(Source: Kodansha USA)"
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

## /character 
### HTTP Request
`GET https://weeb-api.up.railway.app/character?search=mizuhara`

### Query Parameters

| Parameter | Required | Description |
|    ---    |    ---   |     ---     | 
| search    | true     | Character information from Anilist | 

> The response schema would be like this:

```JSON
{
   "characters":[
      {
         "id":128106,
         "name":{
            "first":"Chizuru",
            "last":"Ichinose",
            "full":"Chizuru Ichinose",
            "native":"一ノ瀬ちづる"
         },
         "age":"19-20",
         "gender":"Female",
         "bloodType":null,
         "dateOfBirth":{
            "year":null,
            "month":4,
            "day":19
         },
         "image":{
            "large":"https://s4.anilist.co/file/anilistcdn/character/large/b128106-zSTsuULvz6PX.png"
         },
         "siteUrl":"https://anilist.co/character/128106",
         "description":"__Height:__ 162 cm\n\nChizuru Ichinose, alternatively known as Chizuru Mizuhara in her \"rental girlfriend\" persona, is a college student at Nerima University who is majoring in Literature and she currently lives in Room 204 of Royal Hills Nerima, just next to [Kazuya Kinoshita](https://anilist.co/character/128105/Kazuya-Kinoshita)."
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
}
```

## /manga
### HTTP Request
`GET https://weeb-api.up.railway.app/manga?search=rent-a-girlfriend`

### Query Parameters

| Parameter | Required | Description |
|    ---    |    ---   |     ---     | 
| search    | true     | Manga information from Anilist | 

> The response schema would be like this:

```JSON
[
   {
      "id":99943,
      "idMal":108407,
      "title":{
         "romaji":"Kanojo, Okarishimasu",
         "english":"Rent-A-Girlfriend",
         "native":"彼女、お借りします"
      },
      "status":"RELEASING",
      "format":"MANGA",
      "isAdult":false,
      "averageScore":63,
      "source":"ORIGINAL",
      "genres":[
         "Comedy",
         "Drama",
         "Romance"
      ],
      "countryOfOrigin":"JP",
      "startDate":"12-7-2017",
      "endDate":"null-null-null",
      "volumes":null,
      "chapters":null,
      "trailer":{
         "id":"XoaOzvlf19Q",
         "site":"youtube",
         "thumbnail":"https://i.ytimg.com/vi/XoaOzvlf19Q/hqdefault.jpg"
      },
      "siteUrl":"https://anilist.co/manga/99943",
      "imageUrl":"https://img.anili.st/media/99943",
      "bannerImage":"https://s4.anilist.co/file/anilistcdn/media/manga/banner/99943-bs6PEAZgj1wy.jpg",
      "coverImage":{
         "extraLarge":"https://s4.anilist.co/file/anilistcdn/media/manga/cover/large/bx99943-0tJ6oNhn3xet.png"
      },
      "description":"In today’s Japan, “rental” services can deliver an afternoon with a “friend,” a “parent,” even a fake girlfriend! After a staggering betrayal by his girlfriend, hapless freshman Kazuya gets just desperate enough to give it a try. But he quickly discovers how complicated it can be to “rent” an emotional connection, and his new “girlfriend,” who’s trying to keep her side hustle secret, will panic when she finds out her real life and Kazuya’s are intertwined in surprising ways! Family, school, and life all start to go wrong, too… It’s sweet but naïve boy meets cute but ruthless girl in this 21st-century manga rom-com!\n<br><br>\n(Source: Kodansha USA)"
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
