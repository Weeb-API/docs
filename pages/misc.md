---
permalink: /misc
layout: page
title: Misc Endpoints
---

---
## /gisearch
### HTTP Request
`GET https://weeb-api.vercel.app/gisearch?query=cat`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| query     | true     | `string` | item you are looking for |

> The response schema would be like this:

```json
[
   "https://i.natgeofe.com/n/548467d8-c5f1-4551-9f58-6817a8d2c45e/NationalGeographic_2572187_square.jpg",
   "https://upload.wikimedia.org/wikipedia/commons/1/15/Cat_August_2010-4.jpg",
   "https://cdn.britannica.com/39/7139-050-A88818BB/Himalayan-chocolate-point.jpg",
   "https://upload.wikimedia.org/wikipedia/commons/4/4d/Cat_November_2010-1a.jpg",
   "https://media-cldnry.s-nbcnews.com/image/upload/rockcms/2022-08/220805-domestic-cat-mjf-1540-382ba2.jpg",
   "https://i.natgeofe.com/n/548467d8-c5f1-4551-9f58-6817a8d2c45e/NationalGeographic_2572187_3x4.jpg",
   "https://static01.nyt.com/images/2021/09/14/science/07CAT-STRIPES/07CAT-STRIPES-mediumSquareAt3X-v2.jpg",
   "https://i.guim.co.uk/img/media/26392d05302e02f7bf4eb143bb84c8097d09144b/446_167_3683_2210/master/3683.jpg?width=1200&quality=85&auto=format&fit=max&s=a52bbe202f57ac0f5ff7f47166906403",
   "https://th-thumbnailer.cdn-si-edu.com/bZAar59Bdm95b057iESytYmmAjI=/1400x1050/filters:focal(594x274:595x275)/https://tf-cmsv2-smithsonianmag-media.s3.amazonaws.com/filer/95/db/95db799b-fddf-4fde-91f3-77024442b92d/egypt_kitty_social.jpg",
   "https://icatcare.org/app/uploads/2018/07/Thinking-of-getting-a-cat.png",
   "https://cdn.britannica.com/25/7125-050-67ACEC3C/Abyssinian-sorrel.jpg",
   "http://www.alleycat.org/wp-content/uploads/2019/03/FELV-cat.jpg",
   "https://media.npr.org/assets/img/2021/08/11/gettyimages-1279899488_wide-f3860ceb0ef19643c335cb34df3fa1de166e2761.jpg",
   "https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Cat03.jpg/1200px-Cat03.jpg",
   "https://media.wired.co.uk/photos/60c8730fa81eb7f50b44037e/16:9/w_2560%2Cc_limit/1521-WIRED-Cat.jpeg",
   "https://res.cloudinary.com/dk-find-out/image/upload/q_70,c_pad,w_1200,h_630,f_auto/DCTM_Penguin_UK_DK_AL697473_RGB_PNG_namnse.jpg",
   "https://www.sfspca.org/wp-content/uploads/2023/03/8e593161-0fe0-4af5-ac2d-f90ff1998ca2.jpg",
   "https://i.guim.co.uk/img/media/c5e73ed8e8325d7e79babf8f1ebbd9adc0d95409/2_5_1754_1053/master/1754.jpg?width=1200&quality=85&auto=format&fit=max&s=4219f64fafe19d101f92e0eba0181f6a",
   "https://cdn.theatlantic.com/thumbor/yHhIvkBiGvKKubxVHTNXvU4nCKQ=/1x122:2554x1452/1200x625/media/img/mt/2017/06/shutterstock_319985324/original.jpg",
   "https://petharbor.com/get_image.asp?RES=Detail&ID=A575674&LOCATION=TACM",
   "https://www.thesprucepets.com/thmb/uQnGtOt9VQiML2oG2YzAmPErrHo=/5441x0/filters:no_upscale():strip_icc()/all-about-tabby-cats-552489-hero-a23a9118af8c477b914a0a1570d4f787.jpg",
   "https://www.daysoftheyear.com/cdn-cgi/image/dpr=1%2Cf=auto%2Cfit=cover%2Cheight=650%2Cq=70%2Csharpen=1%2Cwidth=956/wp-content/uploads/international-cat-day1-scaled.jpg",
   "https://g.petango.com/photos/859/39421a52-6a7b-4977-804b-db844f880ca7.jpg",
   "https://www.alleycat.org/wp-content/uploads/2023/04/Homepage_MarchTornadoRelief2_1400x847-320x180.jpg",
   "https://www.sfspca.org/wp-content/uploads/2023/04/625bc6ed-8b44-451a-92f0-56432b134d2f.jpg",
   "https://cdn.britannica.com/25/172925-050-DC7E2298/black-cat-back.jpg",
   "https://petharbor.com/get_image.asp?RES=Detail&ID=A575665&LOCATION=TACM",
   "https://media.4-paws.org/5/b/4/b/5b4b5a91dd9443fa1785ee7fca66850e06dcc7f9/VIER%20PFOTEN_2019-12-13_209-2890x2000-1920x1329.jpg",
   "https://image.cnbcfm.com/api/v1/image/107072184-1654616434858-pixel-selfie.jpg?v=1654616443",
   "https://petharbor.com/get_image.asp?RES=Detail&ID=A575609&LOCATION=TACM"
]
```
---

## /genius
### HTTP Request
`GET https://weeb-api.vercel.app/genius?query=let me down slowly`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| query     | true     | `string` | song name you are looking for |

> The response schema would be like this:

```json
[
   {
      "title":"Let Me Down Slowly",
      "fullTitle":"Let Me Down Slowly by Alec Benjamin",
      "artist":"Alec Benjamin",
      "image":"https://images.genius.com/26cc95e3e957cb78a2a1ba70db277536.1000x1000x1.png",
      "url":"https://genius.com/Alec-benjamin-let-me-down-slowly-lyrics"
   },
   {
      "title":"Let Me Down Slowly",
      "fullTitle":"Let Me Down Slowly by Tinashe",
      "artist":"Tinashe",
      "image":"https://images.genius.com/5fd109fc1571b20e5351909571e7bb08.1000x1000x1.png",
      "url":"https://genius.com/Tinashe-let-me-down-slowly-lyrics"
   },
   {
      "title":"Let Me Down Slowly",
      "fullTitle":"Let Me Down Slowly by Nightcore",
      "artist":"Nightcore",
      "image":"https://images.genius.com/11b4d99dbb5e4725e90aa87257dbe414.600x600x1.jpg",
      "url":"https://genius.com/Nightcore-let-me-down-slowly-lyrics"
   },
   ...
]
```
---

## /lyrics
### HTTP Request
`GET https://weeb-api.vercel.app/lyrics?url=https://genius.com/Alec-benjamin-let-me-down-slowly-lyrics`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| url     | true     | `string` | genius lyrics url |

> The response schema would be like this:

```
[Verse 1]

This night is cold in the kingdom
I can feel you fade away
From the kitchen to the bathroom sink and
Your steps keep me awake

[Pre-Chorus]

Don't cut me down, throw me out, leave me here to waste
I once was a man with dignity and grace
Now I'm slipping through the cracks of your cold embrace
So please, please

[Chorus]

Could you find a way to let me down slowly?
A little sympathy, I hope you can show me
If you wanna go, then I'll be so lonely
If you're leaving, baby let me down slowly
Let me down, down
Let me down, down
Let me down, let me down
Down, let me down, down
Let me down
If you wanna go, then I'll be so lonely
If you're leaving, baby let me down slowly

[Verse 2]

Cold skin, drag my feet on the tile
As I'm walking down the corridor
And I know we haven't talked in a while
So I'm looking for an open door

[Pre-Chorus]

Don't cut me down, throw me out, leave me here to waste
I once was a man with dignity and grace
Now I'm slipping through the cracks of your cold embrace
So please, please

[Chorus]

Could you find a way to let me down slowly?
A little sympathy, I hope you can show me
If you wanna go, then I'll be so lonely
If you're leaving, baby let me down slowly
Let me down, down
Let me down, down
Let me down, let me down
Down, let me down, down
Let me down
If you wanna go, then I'll be so lonely
If you're leaving, baby let me down slowly[Bridge]

And I can't stop myself from falling down
And I can't stop myself from falling down
And I can't stop myself from falling down
And I can't stop myself from falling down

[Chorus]

Could you find a way to let me down slowly?
A little sympathy, I hope you can show me
If you wanna go, then I'll be so lonely
If you're leaving, baby let me down slowly
Let me down, down
Let me down, down
Let me down, let me down
Down, let me down, down
Let me down
If you wanna go, then I'll be so lonely
If you're leaving, baby let me down slowly
If you wanna go, then I'll be so lonely
If you're leaving, baby let me down slowly
```
---

## /mediafiredl
### HTTP Request
`GET https://weeb-api.vercel.app/mediafiredl?url=https://www.mediafire.com/file/9hdis59jmukz9t4/Your_Name_Anime_Movie_In_Hindi.mp4`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| url     | true     | `string` | MediaFire file url |

> The response schema would be like this:

```json
{
   "filename":"Your Name Anime Movie In Hindi.mp4",
   "size":"917.8MB",
   "url":"https://download1588.mediafire.com/aq7jby4t36jgKNBR1FJF1VS2zRUIMAkfZrnvIWfqhfN9rHViQL6vQu2aNa8kyPbzhjv1EId6xo-eRQH0tFBFKFflMeYSN-uqSYh4HOlX_uo3ev5EZmg5Qb7dLmd1_EkgU9v2g_avKFtYs2_UrEK_vo3bFoZmjtktjtIBUDtIG_c/9hdis59jmukz9t4/Your+Name+Anime+Movie+In+Hindi.mp4",
   "mimetype":"video/mp4"
}
```
---

## /npm
### HTTP Request
`GET https://weeb-api.vercel.app/npm?query=axios&limit=1`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| query     | true     | `string` | search query in npmjs |
| limit     | false    | `number` | number of results |

> The response schema would be like this:

```json
{
   "total":5296,
   "limit":1,
   "results":[
      {
         "name":"axios",
         "scope":"unscoped",
         "version":"1.4.0",
         "description":"Promise based HTTP client for the browser and node.js",
         "keywords":[
            "xhr",
            "http",
            "ajax",
            "promise",
            "node"
         ],
         "date":"2023-04-27T23:05:52.716Z",
         "links":{
            "npm":"https://www.npmjs.com/package/axios",
            "homepage":"https://axios-http.com",
            "repository":"https://github.com/axios/axios",
            "bugs":"https://github.com/axios/axios/issues"
         },
         "author":{
            "name":"Matt Zabriskie"
         },
         "publisher":{
            "username":"jasonsaayman",
            "email":"jasonsaayman@gmail.com"
         },
         "maintainers":[
            {
               "username":"mzabriskie",
               "email":"mzabriskie@gmail.com"
            },
            {
               "username":"nickuraltsev",
               "email":"nick.uraltsev@gmail.com"
            },
            {
               "username":"emilyemorehouse",
               "email":"emilyemorehouse@gmail.com"
            },
            {
               "username":"jasonsaayman",
               "email":"jasonsaayman@gmail.com"
            }
         ]
      }
   ]
}
```
---

## /pinterest
### HTTP Request
`GET https://weeb-api.vercel.app/pinterest?query=Hinata`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| query     | true     | `string` | search query |

> The response schema would be like this:

```json
[
   {
      "title":"Hinata icon by yaszvx",
      "type":"image",
      "pinner":{
         "name":"Emily Aimee",
         "username":"emilyyyyaimee",
         "image":"https://i.pinimg.com/140x140_RS/31/3f/b8/313fb85859fb57629b23d7f852ff0979.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/a1/2a/77/a12a778daa03f8f4e156f8aff7473954.jpg"
   },
   {
      "title":"🖤Hinata Hyuga🤍",
      "type":"image",
      "pinner":{
         "name":"J'zer",
         "username":"JAP897",
         "image":"https://i.pinimg.com/140x140_RS/0d/81/1d/0d811d353f7e91dc2478776b7d035d6e.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/a3/35/e7/a335e79d1289177a5101d2ee0ccd16e7.jpg"
   },
   {
      "title":"Naruto girls icons",
      "type":"image",
      "pinner":{
         "name":"Daniela Barbolini",
         "username":"danielabarbolin",
         "image":"https://i.pinimg.com/140x140_RS/54/77/14/547714f3df53b2b08a58a6cbeaff6b0f.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/55/b2/02/55b2026f06e377f6aaee7271d5c509db.jpg"
   },
   {
      "title":"",
      "type":"image",
      "pinner":{
         "name":"Rafael Oliveira",
         "username":"rafaeruparker",
         "image":"https://i.pinimg.com/140x140_RS/09/5f/85/095f856a9a3348058104942d7f3041b1.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/10/4f/81/104f81fe9760caeaceef39fe2848cb5a.jpg"
   },
   {
      "title":"Hinata hyuga By minusleto in devianart",
      "type":"image",
      "pinner":{
         "name":"Masa Ota",
         "username":"masa7755",
         "image":"https://s.pinimg.com/images/user/default_140.png"
      },
      "imageUrl":"https://i.pinimg.com/originals/b2/a3/5c/b2a35c5c27fea83c5bfdfe01c23cca1c.jpg"
   },
   {
      "title":"Hinata hyuga",
      "type":"image",
      "pinner":{
         "name":"Joshua Hall",
         "username":"2007Subie",
         "image":"https://i.pinimg.com/140x140_RS/4a/38/f9/4a38f94466f3958e6e311f88f5798caa.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/e8/96/4a/e8964af98d47b6185e53073b39aab50b.jpg"
   },
   {
      "title":"「 hinata icon  」",
      "type":"image",
      "pinner":{
         "name":"Noir Rose",
         "username":"ReaperScythe15",
         "image":"https://i.pinimg.com/140x140_RS/44/d9/a0/44d9a0a8912e85a9c095b13f07b3fb04.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/6f/7e/6c/6f7e6cc5f8348aa83429c1531df61e58.jpg"
   },
   {
      "title":"",
      "type":"image",
      "pinner":{
         "name":"Mayara Hellena Alves",
         "username":"May_souza88",
         "image":"https://i.pinimg.com/140x140_RS/dc/0f/ff/dc0ffff1780544a4b29bc7c3a646fadc.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/3b/57/b3/3b57b3ef59f3c37117db61b2c0a9ab38.jpg"
   },
   {
      "title":"",
      "type":"image",
      "pinner":{
         "name":"meryem",
         "username":"meryemlachachi",
         "image":"https://s.pinimg.com/images/user/default_140.png"
      },
      "imageUrl":"https://i.pinimg.com/originals/9c/62/f1/9c62f147cc465c20dab48d825c34dae8.jpg"
   },
   {
      "title":"𝑫𝒂𝒊𝒍𝒚 𝑾𝒂𝒊𝒇𝒖𝒔 on X",
      "type":"image",
      "pinner":{
         "name":"Richard",
         "username":"u2rml9515",
         "image":"https://s.pinimg.com/images/user/default_140.png"
      },
      "imageUrl":"https://i.pinimg.com/originals/ec/62/9e/ec629ee79581933a863a24d018b0cdc2.jpg"
   },
   {
      "title":"Hinata icon by yaszvx",
      "type":"image",
      "pinner":{
         "name":"jivotnoeeee",
         "username":"jivotnoeeee",
         "image":"https://i.pinimg.com/140x140_RS/b2/90/76/b290763b6642c127d6d11ec4e92a0752.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/96/ec/ef/96ecef8bd5d459f7e86c0abf08d7896e.jpg"
   },
   {
      "title":"Twitter",
      "type":"image",
      "pinner":{
         "name":"¿MARIA?",
         "username":"AvaAvaRava",
         "image":"https://i.pinimg.com/140x140_RS/97/7d/1d/977d1d723bc474aa15eb6dc2701c77a5.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/af/e9/07/afe907c95cc10c630088090c026c98de.jpg"
   },
   {
      "title":"The most beautiful images - NARUTO - Hinata",
      "type":"image",
      "pinner":{
         "name":"JKS GAARA",
         "username":"AlexSilva0017",
         "image":"https://s.pinimg.com/images/user/default_140.png"
      },
      "imageUrl":"https://i.pinimg.com/originals/88/6b/6a/886b6acbd265811cfcbac500640b2215.jpg"
   },
   {
      "title":"Semidioses y Dioses reaccionan a Naruto",
      "type":"image",
      "pinner":{
         "name":"Miguel Magdaleno Rosales",
         "username":"MikeSchweni7",
         "image":"https://i.pinimg.com/140x140_RS/b8/b1/95/b8b1955cdaac1480e86d4a725dbf5b0e.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/73/ee/a2/73eea20763891dd0f7aca3e3d6767bb9.jpg"
   },
   {
      "title":"Hinata Hyuuga",
      "type":"image",
      "pinner":{
         "name":"João M",
         "username":"jomarcosfernand",
         "image":"https://s.pinimg.com/images/user/default_140.png"
      },
      "imageUrl":"https://i.pinimg.com/originals/df/84/7d/df847df4f3f93e07e629d0d8a8192318.jpg"
   },
   {
      "title":"issei el príncipe del sueño (Finalizada) - harem de issei",
      "type":"image",
      "pinner":{
         "name":"Nayeli Flores",
         "username":"nayeflores1124",
         "image":"https://s.pinimg.com/images/user/default_140.png"
      },
      "imageUrl":"https://i.pinimg.com/originals/0e/05/10/0e05107820676186e416207b84c66d88.jpg"
   },
   {
      "title":"Hinata (The LAST) by MasonENGINE on DeviantArt",
      "type":"image",
      "pinner":{
         "name":"nainaa",
         "username":"nainaa193",
         "image":"https://s.pinimg.com/images/user/default_140.png"
      },
      "imageUrl":"https://i.pinimg.com/originals/02/cb/11/02cb115a85201a2729a142008ee6a252.png"
   },
   {
      "title":"[🍨☀]\n༺♡༻  ʜɪɴᴀᴛᴀ ʜʏᴜɢᴀ 🍨 ɪᴍᴘᴇʀᴀᴛʀɪᴢ 🍓☀",
      "type":"image",
      "pinner":{
         "name":"Mónica Ribeiro",
         "username":"moonikitas",
         "image":"https://s.pinimg.com/images/user/default_140.png"
      },
      "imageUrl":"https://i.pinimg.com/originals/71/7f/08/717f08e61aa373912323203f54c20aa9.jpg"
   },
   {
      "title":"[| 🍓 |]\n✎✐\nHyuga hinata 🌸 top Model\n⌨︎︎",
      "type":"image",
      "pinner":{
         "name":"VIRIYA V",
         "username":"viriyav",
         "image":"https://s.pinimg.com/images/user/default_140.png"
      },
      "imageUrl":"https://i.pinimg.com/originals/f0/6e/0d/f06e0d543a6689c9c5a4b68eab31cc4c.jpg"
   },
   {
      "title":"*sasuhina*Mi verdadera fuerza",
      "type":"image",
      "pinner":{
         "name":"Orena Guillaume",
         "username":"guillaumeorena03",
         "image":"https://s.pinimg.com/images/user/default_140.png"
      },
      "imageUrl":"https://i.pinimg.com/originals/eb/ea/81/ebea813032b0b74f8666ebd4826102c1.jpg"
   },
   {
      "title":"Hinata Hyuuga - Naruto",
      "type":"image",
      "pinner":{
         "name":"Mónica Soto",
         "username":"monicasotho",
         "image":"https://i.pinimg.com/140x140_RS/b6/ff/ad/b6ffad64323f8904717859353811ad75.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/84/33/d6/8433d664ee4fb81fda70a2579065e542.png"
   },
   {
      "title":"# HINATA HYUGA",
      "type":"image",
      "pinner":{
         "name":"Natalia Palomares",
         "username":"nataliavpalomar",
         "image":"https://i.pinimg.com/140x140_RS/5a/48/99/5a48992be97e7d7cf76ded9b5d0042d4.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/c8/92/22/c892228f4d7401d225d7b08fd46e0957.jpg"
   },
   {
      "title":"Hinata Hyuga vector by YubiwaNatsumi on DeviantArt",
      "type":"image",
      "pinner":{
         "name":"Alexandra",
         "username":"Salty_Weeb5",
         "image":"https://i.pinimg.com/140x140_RS/46/0b/61/460b617e2fb946f5e9ecd02455e16619.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/e8/6c/f1/e86cf14e8caa08ea41136e154d3e792c.jpg"
   },
   {
      "title":"[Hinata Hyuga] fanart/Gacha/Naruto ○°•●•",
      "type":"image",
      "pinner":{
         "name":"✰Miภi๖ۣۜƊiosa✰",
         "username":"MiniDiosa_",
         "image":"https://i.pinimg.com/140x140_RS/b4/13/66/b4136638a80c380d7913c9ce191deda7.jpg"
      },
      "imageUrl":"https://i.pinimg.com/originals/38/06/3f/38063ff96fbb42ea9894aba8d1210a15.jpg"
   }
]
```
---

## /reddit
### HTTP Requests
**Parameter Query:**
`GET https://weeb-api.vercel.app/reddit?query=ProgrammerHumor`

**Parameter URL:**
`GET https://weeb-api.vercel.app/reddit?url=https://www.reddit.com/r/ProgrammerHumor/comments/13leyq3/taking_one_for_the_team_oh_wait_why_is_production`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| query     | true     | `string` | Get Random Post from Subreddit |
| url       | true     | `string` | Fetch Reddit Post by URL |

**Note: It can handle reddit multiple media including (image, gif, video, gallery)**
> The response schema would be like this:

```json
{
   "title":"Taking one for the team. Oh wait, why is production down?",
   "author":"_pizza_and_fries",
   "subreddit":"ProgrammerHumor",
   "nsfw":false,
   "spoiler":false,
   "imageUrl":"https://i.redd.it/657946nhyp0b1.jpg",
   "siteUrl":"https://reddit.com/13leyq3",
   "subscribers":3013443
}
```
---

## /telegram
### HTTP Request
`GET https://weeb-api.vercel.app/telegram/anime_news`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| username  | true     | `string` | Telegram channel username to Scrap Data |

> The response schema would be like this:

```json
[
   {
      "id":8215,
      "type":"image",
      "caption":"\"Rekishi ni Nokoru Akujo ni Naru zo\" TV anime adaptation is scheduled for 2024.",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8215",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/qsjIfHK2RLWFvstRC0ufS0ybSpRQjOKu8HW11i0Jo4Wp6Oe36mVmsKqAOym3qdTBxMXXhdUxXhrM-LDh35VRZJ0XTCzRffblkr3LDmdpodZn1ouiiHnUAWUA-O9Fkq-RYCS7RGG66Kbkap4gAax8AoMmPNA9mI_iyLej5KMeFzlC2ijteGvQK0hJAwqGFud9RLlb6AvQSOR6BYm-hMUWnpwyY2IIVFCRaWW4UhvDGRiyyFH8NRGoKVdS9xQWPT3bWZ79u0aPcTR10J4W-E85cwYI3WPomFomX11sewd5opoW-E_QbgJ52C02FWZ6JQAZYKcnbT42xdVq0u4Hd9vW4Q.jpg"
   },
   {
      "id":8216,
      "type":"text",
      "caption":"Original TV anime \"Metallic Rouge\" PV. The anime begins broadcasting in January and is being produced in celebration of studio BONES' 25th Anniversary.\"Metallic Rouge\" new teaser PV.The anime begins broadcasting in January and is being produced in celebration of studio BONES' 25th Anniversary",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8216"
   },
   {
      "id":8217,
      "type":"image",
      "caption":"https://bit.ly/3gdI0U6\"Bye Bye, Earth\" anime adaptation new visual and PV. Broadcasting is scheduled for 2024.  (LIDENFILMS)",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8217",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/T50itLEuG3XKGrJiUZKzLJ23WB7lVkZLiPJ5Ir0-gzqvxMqaj97nA5AfSeHNfoCByQK9SPQ5VtB2kiBC4w3ACJJEXbO2oZ2JCzbMOCMlK_G6juzKRdaJRfCyAGmUSW1uw2xa5GXGb96X4FTj73cy62KlPbE_ZbztUXBm9p76s2bo2nPNdERY9FcEbdXJ8T78XoncA5R9Qvl-HtuMsKwx1ZAnnS2DhGwVQD-pE5q9dcK9jqEO-Ll_tBCryO53B4efzoqNt0P3C1D3FPfd09aV-A_mIGnY4RUS3no0G-q5-MZC7ogZyvR_iWmdqaF0qjZFRDhECVl15Yc_uPRi5i65ow.jpg"
   },
   {
      "id":8218,
      "type":"text",
      "caption":"\"Our Last Crusade or the Rise of a New World\" Season 2 new PV. Broadcasting begins in 2024 (studio palette × SILVER LINK)",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8218"
   },
   {
      "id":8219,
      "type":"text",
      "caption":"\"I Got a Cheat Skill in Another World and Became Unrivaled in The Real World, Too\" TV anime new PV. Broadcasting begins on April 6.“I Got a Cheat Skill in Another World and Became Unrivaled in The Real World, Too”new animation project confirmed",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8219"
   },
   {
      "id":8220,
      "type":"image",
      "caption":"\"Private Tutor to the Duke's Daughter\" anime adaptation announced.",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8220",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/irbhueQzz9gwI1XX86FVX5YDftpdf8u2odSI-5HezDDyE767hsUUGVpB853HLEHVNmpjIHizBo0rSnTLWfHGGugSFId5mS0elF9zG_tw4UPzOoFiPhacaSHNxpi16GAYn22-HdTqlkhpNyMSF6l8CtCsE4xQCx-03LTClLzZNAFVB7DItXOMCvd-9aymriTyjzUJrbwTzugL0_FIMCCQPQUM22tZBSmFIEdvKRURv8OrkBoXMA-n4pw7voftDgmu9FP6bthek87m-Qr6AZGnnt5IUX8y_dEbXLvUWeVrTgbeL_aGdEvt2v4B8cT2akdmeaKoi8Vghl96KGobfpQoTg.jpg"
   },
   {
      "id":8221,
      "type":"image",
      "caption":"\"7th Time Loop: The Villainess Enjoys a Carefree Life Married to Her Worst Enemy!\" new visual and PV. Broadcasting begins in January. (Studio KAI × HORNETS)",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8221",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/mSZo1Nxux-FyVrYnAxehgwxBvkwXOIUBQl_0EpB9gVNrFHaDKwfo8O1AVfwKXt3-oKE6YqX1s2bsDn3acEei43PfDKLRCwfIXC86vkZFLxZ4bT1XBjoUkMS01ww7ff3x9MO1AOF4TGtWwRkq5PWj-LGRZEyfuDu_kxtdL7SXcS5gy-HomPRIcp9GGMH6mVsfpx-Buc7nbSNzDFNbUJxhgxQ9VIudU0BY24KjugmtWgH4SNQtvYsrFcWCp7FuEjE8KH-cXqc3cUe2UJlQR-o237rySqVfsd7DQfmz66TsLWNOGN_g6wGMLWb0yy3DEI-MRCgW-OrfPi8Tt9oK1g_8Lw.jpg"
   },
   {
      "id":8222,
      "type":"image",
      "caption":"\"Chillin' in Another World with Level 2 Super Cheat Powers\" TV anime adaptation announced for 2024. (J.C.STAFF)",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8222",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/TtEjpidqKLDlta295fqKIQl4Db-oJIUP2akeElla4AqszNmyv79_BQWv0Fvcoe_0GVc8Unb_yJXOyopiHFoeg8rWEUtdq4so81fg1U8_ihdwSE9JT4-ttxd0SmBEnavpBBQ8ybbCYijFCLdHAGIBMLBPZ8MxrwvKo5FaQ_vPjDg-7Ld5z3fUeYgA0aCLJpMtIL6yizcK-VDBDHqBzP7a6YoRNZRQryPp2cQAcS6HRi9SWsqEK-cdCL1WUt6FmWJ418La905pPD0YU09kB1sHx0lVD9iSMq5MSCOymFfWh4Sfl5cI1WGDwhLSoq_kZzDfYWw_KbsSOpmlaCceBpOKOA.jpg"
   },
   {
      "id":8223,
      "type":"text",
      "caption":"\"The Unwanted Undead Adventurer\" new PV. Broadcasting begins in January. (CONNECT)",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8223"
   },
   {
      "id":8224,
      "type":"text",
      "caption":"\"The Dangers in My Heart\" Season 2 PV. Broadcasting begins in January. (Shin-Ei Animation)",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8224"
   },
   {
      "id":8225,
      "type":"image",
      "caption":"\"The Dangers in My Heart\" Season 2 PV. Broadcasting begins in January. (Shin-Ei Animation)\"The Dangers in My Heart\" spin-off \"Twi-Yaba\" anime adaptation confirmed.",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8225",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/aTKtr6GQABYCMoDSS9rBjVxwDb5AQ7oBZd5Afb91ringriTYQKVtsyYxVeD2teQi6Zr4iyJxYO0epf4vRK8weRkDB0tHIG92NK6n9orYYWKSlq_HOaOjGsoh5GrkPpzRQvT7-UBO9AUHgchzGL8BKIY2aRWpkiETuGUTJAF7WPd-RYLUDDXrSJHhg45UoUu4GSEPd41expuq52nJNw6OtQI2XpBlmjK-9MDmfWhruaiGArn5lMf6ssF2dRw21ZMV5U52ks2hi5Gguu-2Q8-qWQWxRH8UCNcGsGzIVwdVOEJ7VIPUbsymqUehGt77gk_P7XIWARI2gg__0jC3lj1QMg.jpg"
   },
   {
      "id":8226,
      "type":"text",
      "caption":"\"A Sign of Affection\" TV anime 1st PV.Broadcasting begins in January. (Ajia-do)",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8226"
   },
   {
      "id":8227,
      "type":"image",
      "caption":"\"WIND BREAKER\" new visual and PV. Broadcasting begins in April. (CloverWorks)",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8227",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/drW6Cvn9v2-UpvcXFnjLLglFxD6xvTjPhUPQ0i5Nwl5myE82qZ2KW3UP_PNIcMC1FnkR1OHp8buKYSeWXcUnznLXoiJ4_Lsnqb6edqWnV_dpwQ2iwS2hXLKg2cZMGXKzG3v7vktx4KAchY8GE4jLeQ9PEP4X4f9eODDCA0sodnGGAihq-6uzl7rssdh2R40thYOq-9PJjrVtx26gw6anilpyHx2OheJFjCC1P96EJTxLmFjqzqVTgV946Nnfw8MNFKhdGraDDbckKt78_fWRLrddnK9cbjsr8SRANaveQyhJXSsV6-FXvgUIYXmEZ-zjJgQjeY_-aqEmexjBjdreDg.jpg"
   },
   {
      "id":8228,
      "type":"image",
      "caption":"\"Rascal Does Not Dream of a Knapsack Girl\" special visual and main trailer.Screening in Japan begins on December 1. (CloverWorks)",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8228",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/jK1vhOE3etg322mnel5krnbvm4rxloxXl2RJYaJR1O9Ot0LWAUsGnasrXn0S_IJvs39tM_eQnrXW7AD4cwQcyaPlKQd_DO_MAON5_8OTbn7WpDjwjv6Ut78QG5AxoQ5fA_WWlGaIYHmT_FzUk6VX-_Q8mGDS5O_rn9DzJDvGi0bd-9zlZ_UPwIwK8Vuw6TuA1NPug6I0KV9nwyIfETLa_V9kYXRPZCqEqHnaftxYDJYuBWDljaXuWWlbWoXiLKSjBDfEIdhuvTuocoMikA2fz04jQihgo7P--JG46Sljv9fWJgFfIbHXLpHLHwJFcV_O3Qo7WCYl6o6nwYjIWRo5nQ.jpg"
   },
   {
      "id":8229,
      "type":"image",
      "caption":"\"Yakuza Fiancé: Raise wa Tanin ga Ii\" anime adaptation announced.",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8229",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/P-sr3iMSHqtROMYya3-Qtb0xR5LP9CGa0MiTkuvfVPgffY1aMcXfiecOcbNuLt3C8mSAlshL06lZmNxPXl-cove2c0ClOzUEIpN309MgSPmDn8zf88-CeMYqWTIvdM0nj-v74r8JksI4JIISX4T4JbfFYQZ_NxMvH_c7iOvbQiLkkPbAIu5OIhd6pVHGtOARHn8hOG2Pz1ZhYWv9AgalpIiJbl1z6WwjzKkMvYabAjLO4Co68hsb_m7xnq38232jH2B79y5BKDdS_XqSqpZ5vQRrBB9WMLYJvx2zZh92yV2C0jsjCCb5AmUMlutunaPaHwBE9eGLqYbn49HTMnk1wQ.jpg"
   },
   {
      "id":8230,
      "type":"image",
      "caption":"\"Laid-Back Camp\" Season 3 teaser PV. Broadcasting begins in 2024. (eightbit)\"Laid-Back Camp\" Season 3 begins in April. (eightbit)",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8230",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/JeQqlqnnDdmyBIcTRYGDgXpLiJ_6TOq-JMybb9ofvmqW9BTSB4oXO5-9tphrfnHdq_oZvIRxtTYVqoyZ51EJTLzdp-PUO9abofFyrQjnokksa6HMCSBZvvBBzC4w9WTABqG598y9eoneSGWAYawDZvipWW_b-9ABibyEN97_km2igrx1zcr4yLBbWV_1oq87w7fEWj5VRrcpBgu1TkCDmfYliBoL99_tkYP_ByJjKaUzULkazehV-bGFIFCpaA4pAl1WBCUW9DD0w3VmqrMrhlY0P47I5M2bxSzIR_JUEMQrGgJSBC9xNyM5Ug9hhTbPfzvqjTypytLP4faCE2zqoA.jpg"
   },
   {
      "id":8231,
      "type":"image",
      "caption":"\"Jellyfish Can't Swim in the Night\" original TV anime new visual and PV. Broadcasting is scheduled for 2024. (Doga Kobo)",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8231",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/KuMDZTvr6BItV7VUHOw1t50LDIOM2e7SeXFxXpDptXhec01KQacT3BKIAdd4jp5Mx4ZV99kip3pYXRCJXrZIzDeD0bK4kzpQaPu0ixxeXxOpXaQ7fjYaUA6jV08pZ0HaNUgPF-DbAr6DBXHgtsTY1SlcuMYqAX8kTCJWCIunZ6sgvMC8Lj4KEUujRpieDW25CWSe5O3j4DQclbNqnkZU8izATLnPTIdBCV0CeEhEeK6WXkAzbIwXbOr-EATPqG7ayR1DNIGye4cgZi339QznwCMwrkO__-mVhbK9rddo7e-llze0uCVbFCZuotLFOK1YJ4l9NKrbbbQxZO-7O_Y1TA.jpg"
   },
   {
      "id":8232,
      "type":"image",
      "caption":"\"The Foolish Angel Dances with the Devil\" new visual and PV. Broadcasting begins in January. (Children's Playground Entertainment)",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8232",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/Y2Fv_0ppNcy5M5qagrhyZJ8Q0slcON-7Tc8Ul0oc15Kz0XJA7VnetxfquuKonI_4RcsECwvReRqSQ7Bp2dpXzuNLNADnrV_IDivH_Qv4ij_V3Al4leAbgTuCV2qrty5rZB-e6BhUaeAsC51IE1vE6VOlyneb_QzrbOoqkV7pqTXlOK54gk-V982yMUpmN0iYgp3Ho5QMKQF_wzazG7hMh5S0bY1kWIJTOUk0OPjGUX5Xe1xQ7ja84ZSGYzmsWg3MDT5HHeVAOD06jA0890SGPpVqfogwRYd2LqQvp-vExR-_PmLbPzsG-TspZ9WVjCoB59kixtCR8DPSmFW9HSZA2w.jpg"
   },
   {
      "id":8233,
      "type":"image",
      "caption":"\"Sentenced to Be a Hero\" anime adaptation announced.\"Sentenced to Be a Hero\" anime adaptation is scheduled for 2025.",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8233",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/kzCNY9BsZ0e2S2DnmdL0KWyPm_2XSvDHT_0YscLgyuWTTGyqlF-0q_usyDiiT9T1RU4nLhN2-fwXQAwXGN-LmxRDWb5bEc0f5iAdQHqjQpF3Jl_mwgVhggGV2fG7HCMLih3RtVUkCWquMTOdw1qWIuM2A0ZQiXlI3S90551_Kv1nD8KmeFf1phPqPLFd5usLNe8WeDAbq4TWLHTv6qvizrxTzEVxHNh7EbG1XM68raExfn1cE4GzsyF0KLjOnYlO0-bojlyBK1wKckkpj2Q4qwkVLsdTq4AJdpuODpZVA4arl9e4gEh1MTWDVZ6jfb4Tygu8Kag_pL-2kbPczDetlQ.jpg"
   },
   {
      "id":8234,
      "type":"image",
      "caption":"\"BURN THE WITCH #0.8\" anime adaptation announced.\"BURN THE WITCH #0.8\" new visual and PV. The anime releases worldwide on December 29.",
      "views":"5.1K",
      "time":"2023-10-13T06:18:12+00:00",
      "url":"https://t.me/anime_news/8234",
      "mediaUrl":"https://cdn4.telegram-cdn.org/file/AmO7NW4M6ptChE_ToT0TuimmilBxW9jZvMotX3QOogcQYAIEgc94d3ZMRrPEee3EIJApND7lj7KG0H86Vi2ca5Y2L0QnQRMQU-Zeq9Q9kFOFF7Z3GmlNvV72yX1BgOP5Ojxud1jbQYzfSchtXvFQmBfLSK47Mg9YyFrjJ78UUqVhBiAM7LdWb5Hs-32G8syC7zRNQ9tOheOnKnV7jBm8gwSrA7FlsTwBjtJ6uht2obBgx_pSHrMe7zhwG1IC8rCKFKe8QYyyGvnF2D-FZMrSPMInLWiRtQ0-5agifRsMyZHPuNkUh31gIFmPOj4AQaJSiNGW9_ZtaQJHDdulp4WjoQ.jpg"
   }
]
```
---

## /ytaudio
### HTTP Request
`GET https://weeb-api.vercel.app/ytaudio?query=https://youtu.be/m-el0pQLQE4`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| query     | true     | `string` | YouTube video url or video name you are looking for |

### Response Buffer:
[![Play audio](https://telegra.ph/file/ec6d0a0d4480593adf273.jpg)](https://weeb-api.vercel.app/ytaudio?query=https://youtu.be/m-el0pQLQE4)

---

## /ytsearch
### HTTP Request
`GET https://weeb-api.vercel.app/ytsearch?query=let me down slowly`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| query     | true     | `string` | YouTube video name you are looking for |

> The response schema would be like this:

```json
[
   {
      "type":"video",
      "videoId":"50VNCymT-Cs",
      "url":"https://youtube.com/watch?v=50VNCymT-Cs",
      "title":"Alec Benjamin - Let Me Down Slowly [Official Music Video]",
      "description":"Director: Matt Swinsky Follow Alec Benjamin http://alecbenjamin.com https://www.facebook.com/AlecBenjaminMusic ...",
      "image":"https://i.ytimg.com/vi/50VNCymT-Cs/hq720.jpg",
      "thumbnail":"https://i.ytimg.com/vi/50VNCymT-Cs/hq720.jpg",
      "seconds":178,
      "timestamp":"2:58",
      "duration":{
         "seconds":178,
         "timestamp":"2:58"
      },
      "ago":"4 years ago",
      "views":472865148,
      "author":{
         "name":"Alec Benjamin",
         "url":"https://youtube.com/channel/UCtWBCzqucZXq0M8jsqunM0g"
      }
   },
   ...
]
```
