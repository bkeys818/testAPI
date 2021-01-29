# Used as a Fake API for Testing

## Top Obj Format
```jsonc
{
    "version": "0.0.0", // major.minor.patch
    "data": [/*place*/]
}
```

## Place format
```jsonc
{
    "title": "",  *required
    "desc": "",
    "id": "",  *required
    "lat": 0,  *required
    "lng": 0,  *required
    "type": "",
    "term": "",
    "url": "",
    "address ": {
        "street": "",
        "city": "",
        "state": "",
        "zip": 0,
        "country": ""
    },
    "offices": [
        {
        "name": "",
        "roomNumber": 0,
        "schedule": {/*schedule*/},
        "phone": 0,
        "email": "",
        "url": ""
        }
    ],
    "restrooms": [
        {
        "roomNumber": 0,
        "location": "",
        "sex": "" // male, female, both, unisex, family
        }
    ]
}
```

## Schedule
```jsonc
{
    "days": [
        {
            "day": ["all"],
            "open": [7, 0],
            "close": [20, 30]
        }
    ]
}
```

## Additional objects for specific building types

### Dining Hall
```jsonc
"restaurants": [
    {
    "names": "",
    "schedule": {/*schedule*/}
    }
]
```
