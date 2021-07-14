# Instagram API

In order to be able to get specific instagram posts, I'd have to query the Graph API for every single one of them.
It's the whole feed (with a specific maximum) or a specific post

Could I? :

-   send a request for all posts when admin clicks "edit feed"
-   display those results with select buttons
    -   Will need to extract images of carousel albums, skip any video media
-   send a list of image urls/link urls to the database
-   call the list from the database when ig-feed page loads

    -   could use a custom hook `useInstagram`

    ```js
    [
        {
            "id": xxxx,
            "media_type": xxxx,
            "media_url": xxxx,
            "permalink": xxxx,
        },
        ...
    ]
    ```

    media_type can be IMAGE, VIDEO, or CAROUSEL_ALBUM
