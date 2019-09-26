## Welcome to ChisdealHD API Pages

### API Paths

# Dlive API

- [https://api.chisdealhd.co.uk/dliveapi/?user=](https://api.chisdealhd.co.uk/dliveapi/?user=)

## user = Dlive.tv Username

### Response Code if Accepted / Found

`
{
"statusCode": 200,
"status": "success",
"username": "chisdealhd",
"displayname": "ChisdealHD",
"avatar": "https://images.prd.dlivecdn.com/avatar/c92cbe55-f59e-11e8-ab61-96b7bc5c96d7",
"partnerStatus": "NONE",
"online": false,
"livestream": {
"online": false,
"bg": "https://images.prd.dlivecdn.com/offlineimage/video-placeholder.png"
},
"followers": "182"
}`

![Image](https://i.imgur.com/QtOX2uc.png)

### Error Response code / User not Found

`
{
"error": "Not Found",
"message": "Channel not found.",
"statusCode": 404,
"online": false
}
`
![Image](https://i.imgur.com/QrMYTzC.png)


# Twitch API

## Docs soon!

# Mixer API

- [https://api.chisdealhd.co.uk/mixerapi/?user=](https://api.chisdealhd.co.uk/mixerapi/?user=)

## user = Mixer.com Username

### Response Code if Accepted / Found

`
{
"statusCode": 200,
"status": "success",
"username": "ChisdealHD",
"id": "35982",
"avatar": "https://uploads.mixer.com/avatar/lqj4ffev-45868.jpg",
"partnerStatus": false,
"online": false,
"livestream": {
"online": false,
"bg": "https://uploads.mixer.com/banner/e0jby155-35982.jpg"
},
"followers": "456",
"followers1": ""
}`

![Image](https://i.imgur.com/l5m9oRR.png)

### Error Response code / User not Found

`
{
"error": "Not Found",
"message": "Channel not found.",
"statusCode": 404,
"online": false
}
`
![Image](https://i.imgur.com/QrMYTzC.png)
