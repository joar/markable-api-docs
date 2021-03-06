
## Supported Categories

> **Example:** Request

```http
GET https://catalog.markable.ai/category HTTP/1.1
Authorization: Bearer 123abc
```

```shell
curl -X GET https://catalog.markable.ai/category \
-H 'Content-Type: application/json' \
-H 'Authorization: Bearer 123abc'
```

> **Example:** Response

This is our current list of supported categories.

```json
{
    "data": [
        "hoodies",
        "shoes",
        "messengerbags",
        "jeans",
        "tanks_camis",
        "tunics",
        "coats_jackets",
        "suiting_blazers",
        "sweater",
        "tees",
        "tanks_camis",
        "blouses_shirts",
        "pants",
        "shorts",
        "skirts",
        "slippers",
        "leggings",
        "dresses",
        "bucket",
        "jumpsuits_rompers_overalls",
        "handbags",
        "clutches",
        "belts",
        "boots",
        "sandals",
        "glasses",
        "beanieknitcaps",
        "cowboyhats",
        "scarves_wraps"
    ]
}
```


Markable's supported categories.

<aside class="notice">
    This operation requires a valid <code>access_token</code> - see <a href="#authentication">Authentication</a>.
</aside>


### HTTP Request

`GET https://catalog.markable.ai/category`


### HTTP Headers

Header          | Description
----------        | ----------
`Authorization`     | [HTTP Bearer Token](https://tools.ietf.org/html/rfc6750) for authorizing the request. <br><br>Format is `Bearer :access_token`, where `access_token` is given by [Authentication](#authentication). **<small>required</small>**
