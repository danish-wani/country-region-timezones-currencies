
# Country Region Timezones and Currencies

This repo contains JSON dump of all region specific timezones throughout all the countries, along with currency and daylight saving info.


## Usage/Examples

```json
"America/Los_Angeles": {
    "country": "United States of America",
    "timezones": [
        {
            "local_timezone": "PDT",
            "timezone_name": "Pacific Daylight Time",
            "timezone": "UTC-07:00",
            "is_dst": true
        },
        {
            "local_timezone": "PST",
            "timezone_name": "Pacific Standard Time",
            "timezone": "UTC-08:00",
            "is_dst": false
        }
    ],
    "currencies": {
        "USD": {
            "name": "United States dollar",
            "symbol": "$"
        }
    },
    "country_code": "US"
}
```


