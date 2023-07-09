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

## /scraptg
### HTTP Request
`GET https://weeb-api.vercel.app/scraptg?username=anime_news`

### Query Parameters

| Parameter | Required |   type   | Description | 
|    ---    |    ---   |   ---    |     ---     |
| username  | true     | `string` | Telegram channel username to Scrap Data |

> The response schema would be like this:

```json
[
   {
      "image":"https://cdn4.telegram-cdn.org/file/Sbm_YLPSSMNScgbGHKpm_pjed5_19Qfcg84Jblexd3YXsNLNP4LVj2RrscUxC2oRtg0Ub0u9SCyBCBSKCv9ZD7M0lXqZvkzQ-_Tzpi0perNkmuN6AsVJ4KyQvFpl1POdBpqb4Tvk5rYC4o_kQNKijxrKn14cWjpD07O2vHdOqncT4FuchtbNtGvz_gZQVEAauJJARbSUWQVz1wBH_ZddGKB8mUBwf3TnoM0vFg9Zmimxl_MpY1QUKnUF7bvhIGa-6gNKyP8mFp1Ume0rodC7e5HGml1lGUrrs2D_Xt8VQ1H0RG9R7_vRp_ABxpbGER8O-Fuxrji1gaske_9FCSqBlg.jpg",
      "url":"https://t.me/anime_news/7988",
      "caption":"\"Hokkaido Gals Are Super Adorable!\" new key visual and PV. Broadcasting begins in January. (SILVER LINK. × BLADE)",
      "views":"4.2K",
      "time":"2023-07-03T15:44:18+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/f0jIsUkkfxz-kijro3UMlBVTzWamqUESTDX6BuVd8nMx3EuYuHwF_RcrRdxEPKICgAbYDMfTgH5h8z8Jd4exraBI5_rkViu0-91DmlPvOMknY6hbbAX0ArGE1cBuMtxxwxYjAY_j7xcLCrehZmJieQpQKJr1KV7WZqkph5OX4fE09KXoKSUipb_YiYiHe59ccgNGcV2KFmhmbtRFwjge15SAweIzyDOJW0GSA9dS-0PLJcUUsi4Gn0XSEu_gDv3YDVqAOhbVQ-dbBqJkr27J5P_vW2x4ChIHeEKzdXjWy3c0gHCgmcdeA0f9VRJvSrmy7xi3mZE-GtlOAUWZavrqmQ.jpg",
      "url":"https://t.me/anime_news/7989",
      "caption":"SUICIDE SQUAD ISEKAI, an all-new original anime series collaboration with Warner Bros. Japan and WIT Studio.",
      "views":"6.2K",
      "time":"2023-07-03T18:08:22+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/Zx4n2-MkbKGRBpr8ouJgyVlD1fCQALMoc1naz-I5xDhmuXS3mukjeg4-FZiGFyCZn8UAzPnXp6wcukrXdVImUlJf8FR2Jqr064kwvXx9goXKkyCvsWdDE-HF2LFozgaG2y0SRg3EjnDLLbS_i2wKoWrlQrRg7pcvuMECLHBeFPmF9WrWwehOvpbBhzlhMLPQfpwS6SwacalDmFjmhO_9E3vg2VrhTSgWwM4XsCMYUKMekNmYl5D0NoB_F4nUpmAfyDgpVWR6ZezlnRY6M6h9-L4Dr_q9Cm7JwT9_fnQner4Tj9Kgh39uWETz8qGlOxCWCSB8NzZpo14-mrdFlOojVw.jpg",
      "url":"https://t.me/anime_news/7990",
      "caption":"\"The Rising of the Shield Hero\" Season 3 new key visual.\nBroadcasting begins in October. (Kinema citrus)",
      "views":"3.8K",
      "time":"2023-07-04T05:00:31+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/RdpCHEjskVbmzFXSaYHwFY2JDb3bVxgUvRI6JzlZK7jWkgqLykMYM7ZAiz0erXeTACWKDaXiQqLwb4WPGWe_CxrrwpRJq4cZpqiEFXeMJyrgsT9BgVa1AmCOI6oBnXpRddsn8iJEfKa9h1vTOx5O4Ad8Yt7MAFPhpd3YR4Ru6s8HYBTTu4GnpbaEAtJOoGEDbQOm2vbiFRN0peE1y9I-z7nLNngd8wjn7ZcaPy8ZM-ivRTheqjVqRAMANqSIkxzj1sud4NhRVbiYlD-l4SRkiSno3eSaWu-ESnWR4uUcxnm-kdf_-DbjYS5bgEOlES64zhA4ymDWXPU0DNqVDkaB8Q.jpg",
      "url":"https://t.me/anime_news/7995",
      "caption":"\"Undead Murder Farce\" new visual. Broadcasting begins tomorrow, July 5. (Lapintrack)",
      "views":"4.6K",
      "time":"2023-07-04T09:25:04+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/hyZsvmrBwJJrbBriP6_iTZrqDMWuZki3UqubH-sidW6PGllBUgvRrJZubiiENqoXTIaA_k6nAaUbdsMm5-7-efoUj3R66Q36AyOFGtV7vFPVvHRuCczgnJQ1EvwA0qrTn5tHZcccqQswgt1vpHsC0jkUzylipiv5etZQKqZwY16EJhyRB86GNVKwgWzDpz3Iu-UVksGKbxznUkgTXjfa2VdTnlAbejlW6iCnvL0p-_mc8wgrWXhbQRoW1K_DnxE-Iknn3dbMYP_qjCM4DzY4CMysrOfV2NlprDwK57xJk_1_KsrQp6EhYrZEizSKrFz1co0MvKreQlUGf9AsZYCzJQ.jpg",
      "url":"https://t.me/anime_news/7996",
      "caption":"\"A Sign of Affection\" TV anime adaptation announced for January 2024.",
      "views":"4.1K",
      "time":"2023-07-05T10:11:59+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/Knj5wDMHncISDNHSXFM3iyU4aIAan-hRO7HT0Fez2RF3BqQQwLfrvNVp4X-TeEoio7LiHA6GCxbwZLi44etB75mPRVZfB2c0W0U4Tmrh29oGsZ2ityKoqEQtbSnEqeewqsT2KOS1hNysRhYWHZE5k2D5yLyWJ_ZuchLMcbE-UOX8_dmGnmn8wFXEZ6HZYCg9QfgZrlerSc5bnZpZ5bn_29pUaLk8JcVYaaPrZqVBIZMuEHC-9-nTRTyyH6rL8YixPV71v5Ojls_WTO45hHw61BLipcZCEkdHKimlA3j4-BO9x3UXEXx9_6rSQJ0q0ecB5n9UdtgLkMb-qFQ_WXKyiA.jpg",
      "url":"https://t.me/anime_news/7998",
      "caption":"\"The Vexations of a Shut-In Vampire Princess\" TV anime news key visual and PV. Broadcasting begins in October. (project No.9)",
      "views":"4.1K",
      "time":"2023-07-06T05:57:25+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/nzvRAgPP3SdetYbxDsuHqEqiHqW_1RGmkI5InsSt6IBeml37IFzLe6krzyh_PMwCnoFTSg1a3duSqXWoQlsx1QhMW2DGtk-vDOrZ6if6ctY0EhhI4ynaqmB_XtMvGQLCXU07cHu0o68oXNTqyE7avXdNihkzJh6lx6mCCMpM3k9J6Rrkzml2_9YqtOUkaiJA9qHKbrGvguxuDqf3O2joV_zxpS7xD3YUq2z46_Y11pC-6zqBl3GaPHWdDTsL7q0D8E98igKMSgUh6kxtavS-3_pdabKVNXPNKObNvO4IfudkfYfo236P4VMS2Xg_N7ZVyfdoiFnTx5FJXeHRHs924A.jpg",
      "url":"https://t.me/anime_news/7999",
      "caption":"\"Henjin no Salad Bowl\" (Salad Bowl of Eccentrics) TV anime adaptation announced.",
      "views":"3.9K",
      "time":"2023-07-06T09:08:01+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/Zx5VY8BtS5rXIYFdLCf9KOvDl0Fr0r6DqigZ-nUTzGuX-gbyZSVPvyDbL6Ibe2xO-QntYt3u2rdxMPNqRDW_3G7sUzYHiJNoB6-uqIc0PbpKjCJ-Km8H5qaVkGxKRTjmlTc_jH1LEtGM01gz2nrYnv8ttcyqYk_VUQDSKymgWJWXn35bn8zJiCOpNEdXkDrClUwfDbO3KvpOLERUF6cIi2geuaw61VWb7HwOBPW5y-10ST9P163fXHc7YNF6eve4CzYVFR9_ag0I2akZ-HOvYirUF7RXR65HtU4SgNV9Pz-hwwNaaDCjP0k6ZZeKOjUXu5B-rZXuf_xH_JT3n8_Jmw.jpg",
      "url":"https://t.me/anime_news/8000",
      "caption":"\"Mushoku Tensei: Jobless Reincarnation\" Season 2 will have 25 episodes total.\nCour 1: July–September 2023\nCour 2: April–June 2024",
      "views":"3.8K",
      "time":"2023-07-07T09:45:33+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/f7u2eK-t0hAfK4WYCMomFKYq-ctVndRtHjcrKmrDRaSHrcKHJE-ZbSgEIa9DwPMspKYfb76yO4Dowt9G6u5DDt6nRuceiLM1HgtUZAnI-ujRo4DMKjlnH1MuqPNMKrf6bfwsKiDbrn2L9GA1Ekpe6MosDEb9ZUlACsgWePTV2aq73ymmmnYEq58lEE48aueTnXyRgSugHCbmlpQgteOhn71ggIdO2-7A7JdcRZ10TKikP3dvHzSrTYcz9hEbAhFExK7bhZPzAQcfGqJ7XPYzvs_j8Z4aDJ5X5lZYe_HJ2ilzc3LPtCyXLduqr_ZFgQUYCp5WvnNVwLJkRNNDyOMz0w.jpg",
      "url":"https://t.me/anime_news/8001",
      "caption":"\"365 Days to the Wedding\" TV anime adaptation confirmed.",
      "views":"3.8K",
      "time":"2023-07-07T09:46:04+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/jo-7XEek8ym3vYCAYu3JJ76W017j2wzFkpZQK6wKr_b-BvR_tTHR7m48u9oGXlOonGmvECiAHZw2uwHQxGR1KUeK-x8UmBse76tUOkaL3oXOF9UzjHr-PjZ8N1VHGgjJH9piy2k0Kw0SYAc_GHoUPcSiTZIASHs_NQXvYmO3Y4ntMPzwnbpM01JofyCW782U1egNJQRV0NSVLMQj_WlxKRw2PQ45rPxOKZ6Ttg6-pd-NrdqX80nvcFQ_nt0FkFhhDaEis5Jjx-5fcg8HKSGgS0QGhfC85jpD9gJTASC4WJclyo6TEke0ICKH-xMPg3_d8lgqvvwMCav_ZMpEZnsclQ.jpg",
      "url":"https://t.me/anime_news/8002",
      "caption":"\"The Apothecary Diaries\" new visual and PV. Broadcasting begins in October. (TOHO animation STUDIO × OLM)",
      "views":"3.8K",
      "time":"2023-07-07T14:37:48+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/HsnTRNeBJpU0jqk4kPoIA85NXYF9yKMQYeMYJx9IVVt1wudBmUPaGJxOVia8pi_nJ518KziVw1aUE7UvwivEoGZNu1Vl2t-_rI-wlDkfI-n9xcf072bbGTEfZ4uwE0w_zHTp5U1EYDr28O-f0XA5sfttjZmkFIdG1T0vfgO54DErmOOTIUsyjrxpqej_ofug8gjiPFooJKte_p4tvbKCZpzaxGwmYJa6EE1OZ0BU0rop5aLhlT2Alqm1LMqTZeLnXM3xz_mZOBOOuK98ofVWziZPu1bCxVzioAZHdwZPMDy6ZghChglplxINcRHb4eHbx7N535haJwnI2XokubVSoA.jpg",
      "url":"https://t.me/anime_news/8003",
      "caption":"\"Our Rainy Protocol\" original TV anime announced for October. (Quad)",
      "views":"3.3K",
      "time":"2023-07-08T05:59:56+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/mzv-iMW3epurVV_IeKz-G3NJ4p5RYHkx1T_bTpCrx1J5DEe9Jon2xwomKgxV0vOJBscpngHzeyyhTHhN6Au8s1sprCLqORjaXbtUKjywm407dPWjy-Fe6OAn5vvxpQyFfzvHTO1mavVLh9JKGe-TI39uKjfctjVt7Qsdd2xKWe_skk2dLQn5B8WdzSCajQVg-N2KWIjbyVvBWKjTcUMDKz3S_x_8jCVGw3hs003hSJbVLyjTRpPfErWubyQHgjj6ogqDZMxsUqIwkg6FrgD7zS0ctCoe5t7TbY3rFp98kSnVB3NuIjWUvuY-yHMWq7YJORPFL4j7qrpR0hk8iwtsew.jpg",
      "url":"https://t.me/anime_news/8004",
      "caption":"\"Laid-Back Camp\" Season 3 is scheduled for 2024.",
      "views":"2.8K",
      "time":"2023-07-09T10:56:24+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/fPsIM97ied3yYLsJL3a7DlxAGwmprJvCPlMaT2fwIBUxYoLeXzKyP0jKwFPPFTjpAj4khUEFUO3UJmosdBnx3azC6fT3Q__m4gH_Eg0J8ByRczkv1Yuw_p7Qc9D67bYSqxUU3ZF3b7y3mFCNGiFqXDM-2EBSTX1bui69zFF_OPu2RbPlweT9Pqi8UmTwI1qd59XvSiMVKNy6Z-qbhRZFDhxew4Cr2qb7nEP4St8mRy82ijYPlu-hneTjBfSm32POiTkM3-ipLRmO46B7c4ZpZ58_NHYVuDFUNqc_ja0h05iaUPUzxxAIwGPD8g8yAPtA8pMpF41MX4xNlFTiesw7Bw.jpg",
      "url":"https://t.me/anime_news/8006",
      "caption":"\"Mysterious Disappearances\" begins broadcasting in 2024.",
      "views":"1.7K",
      "time":"2023-07-09T15:17:49+00:00"
   },
   {
      "image":"https://cdn4.telegram-cdn.org/file/d_ayo7G4QXs3QA8Zz7aUaCJNlZg-lH9-DiMWKR_ZYTJJ2AH2FOEeD3cNNGbPi8_GQkQAx0vh0NV7kzGwME8Z-SU4SnEdCc1AYbnVz9xR3s2ycDw9haHyw-FmSQQ9lJWNkF257b0GhLNr5YKBWYS1rhjxmAJYFU9TPCrXYRmUS0hzTOnmI_CcI1TbNgG_f3pnR1fXJBUfocB1sk8-1tSK3Kv-qK8A3aLT_4g1jsfCQn3R4vOxKqWvjQM83zjY0Mh_F0wpaZiP2HCWIzGsQUlotHgxl124bRSEag0ih99pOXPbYbKMCbHXy_IMxvsW0SLRda6Gj3VhDmL11CU8U8Y0OA.jpg",
      "url":"https://t.me/anime_news/8007",
      "caption":"\"The Fable\" TV anime adaptation announced.",
      "views":"1.8K",
      "time":"2023-07-09T15:19:04+00:00"
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
