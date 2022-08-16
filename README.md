# Sheruta API Documentation 
Welcome To Four Anime Scraper This Is For The Sheruta API 
Build in mind of its corractions

We are not responsible for the API or it corractions. You should always keep in mind of the rules

----

## Rules

1) We Are Not Responsible for using this API use at your own risk
2) If you fork this please make sure you have change the configuration file before using this

3) If you have any questions please [Contact Us](https://sheruta.xyz/contact-us) or [Discord](https://sheruta.xyz/discord-us).

---

## EndPoints
<em style="text-align:center">

<strong> Getting Info  </strong>

```
    GET /api/v1/info?title={ANIME_NAME}
    Authorization: Bearer {TOKEN_FROM_SHERUTA_API_KEY}
    Cors_Allow: {SHERUTA_URL}
    CacheData: True

    DELETE /api/v1/info?title={ANIME_NAME}
    Authorization: Bearer {TOKEN_FROM_SHERUTA_API_KEY}

    PUT /api/v1/info?title={ANIME_NAME}
    Authorization: Bearer {TOKEN_FROM_SHERUTA_API_KEY}

```

<strong> Getting Anime Episodes Info </strong>

```
    GET /api/v1/anime?title={ANIME_NAME}
    Authorization: Bearer {TOKEN_FROM_SHERUTA_API_KEY}
    Cors_Allow: {SHERUTA_URL}
    CacheData: True

    DELETE /api/v1/anime?title={ANIME_NAME}
    Authorization: Bearer {TOKEN_FROM_SHERUTA_API_KEY}

    PUT /api/v1/anime?title={ANIME_NAME}
    Authorization: Bearer {TOKEN_FROM_SHERUTA_API_KEY}
```

<strong> Getting Anime Streaming Link </strong>

```
    GET /api/v1/stream/anime?title={ANIME_NAME}
    Authorization: Bearer {TOKEN_FROM_SHERUTA_API_KEY}
    Cors_Allow: {SHERUTA_URL}
    CacheData: True


    DELETE /api/v1/stream/anime?title={ANIME_NAME}
    Authorization: Bearer {TOKEN_FROM_SHERUTA_API_KEY}

    PUT /api/v1/stream/anime?title={ANIME_NAME}
    Authorization: Bearer {TOKEN_FROM_SHERUTA_API_KEY}
```

</em>

---

## Allowed Headers

<em style="text-align: center;">

```
   ====================
   = ALLOWED_HEADERS: =
   ====================

    Authorization: Bearer {TOKEN_FROM_SHERUTA_API_KEY}
    Cache_Data: Boolean (Will Enable Cache If Not Enabled On API)
    Cors_Allow: String (Will Allow Access To API)
    Author_ClientID: String (Must Be In .env File Or Config File)
    Disabled_Headers: Boolean (Disables Headers Not Recommended If Cache Data Is Enabled)
    Api_Docs: String (Must Be Added So We Can Display Documentation)
    Api_Themes: String (Do You Want To Display A Theme For Your API Libary?)

```

</em>