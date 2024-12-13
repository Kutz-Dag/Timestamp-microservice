# Timestamp Microservice

### Description

// coming soon

### Preview Render:

![time-stamp microservice](https://github.com/user-attachments/assets/360861ff-a0fa-41e5-8c5b-2a47caa1e9c8)

### User stories/tests to pass:

- [x] You should provide your own project, not the example URL.
- [x] A request to /api/:date? with a valid date should return a JSON object with a unix key that is a Unix timestamp of the input date in milliseconds (as type Number)
- [x] A request to /api/:date? with a valid date should return a JSON object with a utc key that is a string of the input date in the format: Thu, 01 Jan 1970 00:00:00 GMT
- [x] A request to /api/1451001600000 should return { unix: 1451001600000, utc: "Fri, 25 Dec 2015 00:00:00 GMT" }
- [x] Your project can handle dates that can be successfully parsed by new Date(date_string)
- [x] If the input date string is invalid, the API returns an object having the structure { error : "Invalid Date" }
- [x] An empty date parameter should return the current time in a JSON object with a unix key
- [x] An empty date parameter should return the current time in a JSON object with a utc key
