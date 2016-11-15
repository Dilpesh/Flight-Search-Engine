# Flight-Search-Engine
Flight Search Engine, based on source  and destination it shows flights, both one way and round trip. 


Input is in ./assets/flightDb.json

Input format: [flightObject1,flightObejct2];

flightObject:

 {
    "src": "Pune", (Origin City)
    "dest": "Delhi", (Destination City)
    "depTimeMs": 28800000, (Time as Milliseconds passed on that day, eg. 1:00 AM will be shown as 3600000ms, )
    "arrTimeMs": 36000000, (10:00 AM)
    "day": [
      0,
      1,
      2,
      3,
      4,
      5,
      6
    ], (SUNDAY - 0, Saturday - 6)
    "seatCount": 120,
    "price": 4500,
    "name": "AL-202"
  }
