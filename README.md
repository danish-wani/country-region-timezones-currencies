# country-region-timezones-currencies

This repo contains JSON dump of all region specific timezones throughout all the countries, along with currency and daylight saving info.


example:
{
  "America/Montreal": {
        "country": "Canada",
        "timezones": [
            {
                "local_timezone": "EDT",
                "timezone_name": "Eastern Standard Time",
                "timezone": "UTC-05:00",
                "is_dst": true
            }
        ],
        "currencies": {
            "CAD": {
                "name": "Canadian dollar",
                "symbol": "$"
            }
        },
        "country_code": "CA"
  }
}
