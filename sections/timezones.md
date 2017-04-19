Timezones
====================

* [Get all timezones](#get-all-timezones)


Get all timezones
----------------

* `GET v3/timezones` will return all the timezones of account.

```json
[
  {
    "id": 1,
    "timezone": "Eastern Time (US & Canada)",
    "time_diff": "-05:00"
  },
  {
    "id": 3,
    "timezone": "Alaska",
    "time_diff": "-09:00"
  },
  {
    "id": 4,
    "timezone": "Pacific Time (US & Canada)",
    "time_diff": "-08:00"
  },
  {
    "id": 5,
    "timezone": "Arizona",
    "time_diff": "-07:00"
  },
  {
    "id": 6,
    "timezone": "Mountain Time (US & Canada)",
    "time_diff": "-07:00"
  },
  {
    "id": 7,
    "timezone": "Central Time (US & Canada)",
    "time_diff": "-06:00"
  },
  {
    "id": 8,
    "timezone": "Indiana (East)",
    "time_diff": "-05:00"
  },
  {
    "id": 10,
    "timezone": "Midway Island",
    "time_diff": "-11:00"
  },
  {
    "id": 11,
    "timezone": "Samoa",
    "time_diff": "-11:00"
  },
  {
    "id": 12,
    "timezone": "Hawaii",
    "time_diff": "-10:00"
  },
  {
    "id": 13,
    "timezone": "Alaska",
    "time_diff": "-09:00"
  },
  {
    "id": 14,
    "timezone": "Pacific Time (US & Canada)",
    "time_diff": "-08:00"
  },
  {
    "id": 15,
    "timezone": "Tijuana",
    "time_diff": "-08:00"
  },
  {
    "id": 16,
    "timezone": "Arizona",
    "time_diff": "-07:00"
  },
  {
    "id": 17,
    "timezone": "Chihuahua",
    "time_diff": "-07:00"
  },
  {
    "id": 18,
    "timezone": "Mazatlan",
    "time_diff": "-07:00"
  },
  {
    "id": 19,
    "timezone": "Mountain Time (US & Canada)",
    "time_diff": "-07:00"
  },
  {
    "id": 20,
    "timezone": "Central America",
    "time_diff": "-06:00"
  },
  {
    "id": 21,
    "timezone": "Central Time (US & Canada)",
    "time_diff": "-06:00"
  },
  {
    "id": 22,
    "timezone": "Guadalajara",
    "time_diff": "-06:00"
  },
  {
    "id": 23,
    "timezone": "Mexico City",
    "time_diff": "-06:00"
  },
  {
    "id": 24,
    "timezone": "Monterrey",
    "time_diff": "-06:00"
  },
  {
    "id": 25,
    "timezone": "Saskatchewan",
    "time_diff": "-06:00"
  },
  {
    "id": 26,
    "timezone": "Bogota",
    "time_diff": "-05:00"
  },
  {
    "id": 27,
    "timezone": "Eastern Time (US & Canada)",
    "time_diff": "-05:00"
  },
  {
    "id": 28,
    "timezone": "Indiana (East)",
    "time_diff": "-05:00"
  },
  {
    "id": 29,
    "timezone": "Lima",
    "time_diff": "-05:00"
  },
  {
    "id": 30,
    "timezone": "Quito",
    "time_diff": "-05:00"
  },
  {
    "id": 31,
    "timezone": "Caracas",
    "time_diff": "-04:30"
  },
  {
    "id": 32,
    "timezone": "Atlantic Time (Canada)",
    "time_diff": "-04:00"
  },
  {
    "id": 33,
    "timezone": "La Paz",
    "time_diff": "-04:00"
  },
  {
    "id": 34,
    "timezone": "Santiago",
    "time_diff": "-04:00"
  },
  {
    "id": 35,
    "timezone": "Newfoundland",
    "time_diff": "-03:30"
  },
  {
    "id": 36,
    "timezone": "Brasilia",
    "time_diff": "-03:00"
  },
  {
    "id": 37,
    "timezone": "Buenos Aires",
    "time_diff": "-03:00"
  },
  {
    "id": 38,
    "timezone": "Georgetown",
    "time_diff": "-03:00"
  },
  {
    "id": 39,
    "timezone": "Greenland",
    "time_diff": "-03:00"
  },
  {
    "id": 40,
    "timezone": "Mid-Atlantic",
    "time_diff": "-02:00"
  },
  {
    "id": 41,
    "timezone": "Azores",
    "time_diff": "-01:00"
  },
  {
    "id": 42,
    "timezone": "Cape Verde Is.",
    "time_diff": "-01:00"
  },
  {
    "id": 43,
    "timezone": "Casablanca",
    "time_diff": "+00:00"
  },
  {
    "id": 44,
    "timezone": "Dublin",
    "time_diff": "+00:00"
  },
  {
    "id": 45,
    "timezone": "Edinburgh",
    "time_diff": "+00:00"
  },
  {
    "id": 46,
    "timezone": "Lisbon",
    "time_diff": "+00:00"
  },
  {
    "id": 47,
    "timezone": "London",
    "time_diff": "+00:00"
  },
  {
    "id": 48,
    "timezone": "Monrovia",
    "time_diff": "+00:00"
  },
  {
    "id": 49,
    "timezone": "UTC",
    "time_diff": "+00:00"
  },
  {
    "id": 50,
    "timezone": "Amsterdam",
    "time_diff": "+01:00"
  },
  {
    "id": 51,
    "timezone": "Belgrade",
    "time_diff": "+01:00"
  },
  {
    "id": 52,
    "timezone": "Berlin",
    "time_diff": "+01:00"
  },
  {
    "id": 53,
    "timezone": "Bern",
    "time_diff": "+01:00"
  },
  {
    "id": 54,
    "timezone": "Bratislava",
    "time_diff": "+01:00"
  },
  {
    "id": 55,
    "timezone": "Brussels",
    "time_diff": "+01:00"
  },
  {
    "id": 56,
    "timezone": "Budapest",
    "time_diff": "+01:00"
  },
  {
    "id": 57,
    "timezone": "Copenhagen",
    "time_diff": "+01:00"
  },
  {
    "id": 58,
    "timezone": "Ljubljana",
    "time_diff": "+01:00"
  },
  {
    "id": 59,
    "timezone": "Madrid",
    "time_diff": "+01:00"
  },
  {
    "id": 60,
    "timezone": "Paris",
    "time_diff": "+01:00"
  },
  {
    "id": 61,
    "timezone": "Prague",
    "time_diff": "+01:00"
  },
  {
    "id": 62,
    "timezone": "Rome",
    "time_diff": "+01:00"
  },
  {
    "id": 63,
    "timezone": "Sarajevo",
    "time_diff": "+01:00"
  },
  {
    "id": 64,
    "timezone": "Skopje",
    "time_diff": "+01:00"
  },
  {
    "id": 65,
    "timezone": "Stockholm",
    "time_diff": "+01:00"
  },
  {
    "id": 66,
    "timezone": "Vienna",
    "time_diff": "+01:00"
  },
  {
    "id": 67,
    "timezone": "Warsaw",
    "time_diff": "+01:00"
  },
  {
    "id": 68,
    "timezone": "West Central Africa",
    "time_diff": "+01:00"
  },
  {
    "id": 69,
    "timezone": "Zagreb",
    "time_diff": "+01:00"
  },
  {
    "id": 70,
    "timezone": "Athens",
    "time_diff": "+02:00"
  },
  {
    "id": 71,
    "timezone": "Bucharest",
    "time_diff": "+02:00"
  },
  {
    "id": 72,
    "timezone": "Cairo",
    "time_diff": "+02:00"
  },
  {
    "id": 73,
    "timezone": "Harare",
    "time_diff": "+02:00"
  },
  {
    "id": 74,
    "timezone": "Helsinki",
    "time_diff": "+02:00"
  },
  {
    "id": 75,
    "timezone": "Istanbul",
    "time_diff": "+02:00"
  },
  {
    "id": 76,
    "timezone": "Jerusalem",
    "time_diff": "+02:00"
  },
  {
    "id": 77,
    "timezone": "Kyev",
    "time_diff": "+02:00"
  },
  {
    "id": 78,
    "timezone": "Minsk",
    "time_diff": "+02:00"
  },
  {
    "id": 79,
    "timezone": "Pretoria",
    "time_diff": "+02:00"
  },
  {
    "id": 80,
    "timezone": "Riga",
    "time_diff": "+02:00"
  },
  {
    "id": 81,
    "timezone": "Sofia",
    "time_diff": "+02:00"
  },
  {
    "id": 82,
    "timezone": "Tallinn",
    "time_diff": "+02:00"
  },
  {
    "id": 83,
    "timezone": "Vilnius",
    "time_diff": "+02:00"
  },
  {
    "id": 84,
    "timezone": "Baghdad",
    "time_diff": "+03:00"
  },
  {
    "id": 85,
    "timezone": "Kuwait",
    "time_diff": "+03:00"
  },
  {
    "id": 86,
    "timezone": "Moscow",
    "time_diff": "+03:00"
  },
  {
    "id": 87,
    "timezone": "Nairobi",
    "time_diff": "+03:00"
  },
  {
    "id": 88,
    "timezone": "Riyadh",
    "time_diff": "+03:00"
  },
  {
    "id": 89,
    "timezone": "St. Petersburg",
    "time_diff": "+03:00"
  },
  {
    "id": 90,
    "timezone": "Volgograd",
    "time_diff": "+03:00"
  },
  {
    "id": 91,
    "timezone": "Tehran",
    "time_diff": "+03:30"
  },
  {
    "id": 92,
    "timezone": "Abu Dhabi",
    "time_diff": "+04:00"
  },
  {
    "id": 93,
    "timezone": "Baku",
    "time_diff": "+04:00"
  },
  {
    "id": 94,
    "timezone": "Muscat",
    "time_diff": "+04:00"
  },
  {
    "id": 95,
    "timezone": "Tbilisi",
    "time_diff": "+04:00"
  },
  {
    "id": 96,
    "timezone": "Yerevan",
    "time_diff": "+04:00"
  },
  {
    "id": 97,
    "timezone": "Kabul",
    "time_diff": "+04:30"
  },
  {
    "id": 98,
    "timezone": "Ekaterinburg",
    "time_diff": "+05:00"
  },
  {
    "id": 99,
    "timezone": "Islamabad",
    "time_diff": "+05:00"
  },
  {
    "id": 100,
    "timezone": "Karachi",
    "time_diff": "+05:00"
  },
  {
    "id": 101,
    "timezone": "Tashkent",
    "time_diff": "+05:00"
  },
  {
    "id": 102,
    "timezone": "Chennai",
    "time_diff": "+05:30"
  },
  {
    "id": 103,
    "timezone": "Kolkata",
    "time_diff": "+05:30"
  },
  {
    "id": 104,
    "timezone": "Mumbai",
    "time_diff": "+05:30"
  },
  {
    "id": 105,
    "timezone": "New Delhi",
    "time_diff": "+05:30"
  },
  {
    "id": 106,
    "timezone": "Sri Jayawardenepura",
    "time_diff": "+05:30"
  },
  {
    "id": 107,
    "timezone": "Kathmandu",
    "time_diff": "+05:45"
  },
  {
    "id": 108,
    "timezone": "Almaty",
    "time_diff": "+06:00"
  },
  {
    "id": 109,
    "timezone": "Astana",
    "time_diff": "+06:00"
  },
  {
    "id": 110,
    "timezone": "Dhaka",
    "time_diff": "+06:00"
  },
  {
    "id": 111,
    "timezone": "Novosibirsk",
    "time_diff": "+06:00"
  },
  {
    "id": 112,
    "timezone": "Rangoon",
    "time_diff": "+06:30"
  },
  {
    "id": 113,
    "timezone": "Bangkok",
    "time_diff": "+07:00"
  },
  {
    "id": 114,
    "timezone": "Hanoi",
    "time_diff": "+07:00"
  },
  {
    "id": 115,
    "timezone": "Jakarta",
    "time_diff": "+07:00"
  },
  {
    "id": 116,
    "timezone": "Krasnoyarsk",
    "time_diff": "+07:00"
  },
  {
    "id": 117,
    "timezone": "Beijing",
    "time_diff": "+08:00"
  },
  {
    "id": 118,
    "timezone": "Chongqing",
    "time_diff": "+08:00"
  },
  {
    "id": 119,
    "timezone": "Hong Kong",
    "time_diff": "+08:00"
  },
  {
    "id": 120,
    "timezone": "Irkutsk",
    "time_diff": "+08:00"
  },
  {
    "id": 121,
    "timezone": "Kuala Lumpur",
    "time_diff": "+08:00"
  },
  {
    "id": 122,
    "timezone": "Perth",
    "time_diff": "+08:00"
  },
  {
    "id": 123,
    "timezone": "Singapore",
    "time_diff": "+08:00"
  },
  {
    "id": 124,
    "timezone": "Taipei",
    "time_diff": "+08:00"
  },
  {
    "id": 125,
    "timezone": "Ulaan Bataar",
    "time_diff": "+08:00"
  },
  {
    "id": 126,
    "timezone": "Urumqi",
    "time_diff": "+08:00"
  },
  {
    "id": 127,
    "timezone": "Osaka",
    "time_diff": "+09:00"
  },
  {
    "id": 128,
    "timezone": "Sapporo",
    "time_diff": "+09:00"
  },
  {
    "id": 129,
    "timezone": "Seoul",
    "time_diff": "+09:00"
  },
  {
    "id": 130,
    "timezone": "Tokyo",
    "time_diff": "+09:00"
  },
  {
    "id": 131,
    "timezone": "Yakutsk",
    "time_diff": "+09:00"
  },
  {
    "id": 132,
    "timezone": "Adelaide",
    "time_diff": "+09:30"
  },
  {
    "id": 133,
    "timezone": "Darwin",
    "time_diff": "+09:30"
  },
  {
    "id": 134,
    "timezone": "Brisbane",
    "time_diff": "+10:00"
  },
  {
    "id": 135,
    "timezone": "Canberra",
    "time_diff": "+10:00"
  },
  {
    "id": 136,
    "timezone": "Guam",
    "time_diff": "+10:00"
  },
  {
    "id": 137,
    "timezone": "Hobart",
    "time_diff": "+10:00"
  },
  {
    "id": 138,
    "timezone": "Melbourne",
    "time_diff": "+10:00"
  },
  {
    "id": 139,
    "timezone": "Port Moresby",
    "time_diff": "+10:00"
  },
  {
    "id": 140,
    "timezone": "Sydney",
    "time_diff": "+10:00"
  },
  {
    "id": 141,
    "timezone": "Vladivostok",
    "time_diff": "+10:00"
  },
  {
    "id": 142,
    "timezone": "Magadan",
    "time_diff": "+11:00"
  },
  {
    "id": 143,
    "timezone": "New Caledonia",
    "time_diff": "+11:00"
  },
  {
    "id": 144,
    "timezone": "Solomon Is.",
    "time_diff": "+11:00"
  },
  {
    "id": 145,
    "timezone": "Auckland",
    "time_diff": "+12:00"
  },
  {
    "id": 146,
    "timezone": "Fiji",
    "time_diff": "+12:00"
  },
  {
    "id": 147,
    "timezone": "Kamchatka",
    "time_diff": "+12:00"
  },
  {
    "id": 148,
    "timezone": "Marshall Is.",
    "time_diff": "+12:00"
  },
  {
    "id": 149,
    "timezone": "Wellington",
    "time_diff": "+12:00"
  },
  {
    "id": 150,
    "timezone": "Nuku'alofa",
    "time_diff": "+13:00"
  },
  {
    "id": 151,
    "timezone": "South Australia",
    "time_diff": "+10:30"
  },
  {
    "id": 152,
    "timezone": "Eastern Daylight Time",
    "time_diff": "-04:00"
  }
]
```