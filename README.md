# Used as a Fake API for Testing

## Place format
```json
{
  "title": "",  *required
  "desc": "",
  "id": "",  *required
  "lat": 0,  *required
  "lng": 0,  *required
  "type": "",
  "term": "",
  "url": "",
  "thumb": "",
  "address ": {
    "street": "",
    "city": "",
    "state": "",
    "zip": 0,
    "country": ""
  },
  "offices": [
    {
      "roomNumber": "",
      "phone": 0,
      "url": ""
    }
  ],
  "restrooms": [
    {
      "location": "",
      "sex": "",
      "roomNumber": ""
    }
  ]
}
```

## Additional objects for specific building types

### Dining Hall
```json
"restaurants": [
  {
    "names": [
      ""
    ],
    "schedule": [
      {
        "day": "",
        "openTime": "",
        "closeTime": ""
      }
    ]
  }
]
```