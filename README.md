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
	  "name": ""
      "roomNumber": 0,
      "phone": 0,
	  "email": "",
      "url": ""
    }
  ],
  "restrooms": [
    {
	  "roomNumber": 0,
      "location": "",
      "sex": ""
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