# Buber Breakfast API

- [Buber Breakfast API](#buber-breakfast-api)
    - [Create Breakfast](#create-breakfast)
        - [Create Breakfast Request](#create-breakfast-request)
        - [Create Breakfast Response](#create-breakfast-response)
    -[Get Breakfast](#get-breakfast)
        -[Get Breakfast Request](#get-breakfast-request)
        - [Get Breakfast Response](#get-breakfast-response)
    -[Update Breakfast](#update-breakfast)
        -[Update Breakfast Request](#update-breakfast-request)
        - [Update Breakfast Response](#update-breakfast-response)
    -[Delete Breakfast](#delete-breakfast)
        -[Delete Breakfast Request](#delete-breakfast-request)
        - [Delete Breakfast Response](#delete-breakfast-response)

## Create Breakfast

### Create Breakfast Request

```js
POST /breakfasts
```

```json
{
    "name": "Vegan Sunshine",
    "description": "Vegan everything!
    Join us for a healthy breakfast..",
    "startDateTime":"2022-04-08T08:00:00",
    "endDateTime": "2022-04-08T11:00:00",
    "savory": [
        "Oatmeal",
        "Avocado Toast",
        "Omelette",
        "Salad"
    ],
    "Sweet":[
        "Cookie"
    ]
}
```