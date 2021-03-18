# weather-api-interface
weather-api Problem in MuleSof

--------
Overview
--------
This RAML spec provides the definition of the Weather API Interface.
The Weather Publication API allows you to query weather by Country and get weather by City and Country.

--------
Examples
----------
- Get all research publications that were modified since 2020-09-10T12:45:41.090Z:
  `https://api-sit.dice-nonprod.uow.edu.au/v1/research-publications?page=1&since=2020-09-01T12%3A45%3A41.090Z`

- Get research publication with a specific id: 52154
  `https://api-sit.dice-nonprod.uow.edu.au/v1/research-publications/52154`

- Get research publication with a issn: 2515-5091
  `https://api-sit.dice-nonprod.uow.edu.au/v1/research-publications?issn=2515-5091`

- Get research publication for author Aaron Cashmore
  `https://api-sit.dice-nonprod.uow.edu.au/v1/research-publications?authors=Aaron Cashmor`
