# Rollercoaster API

Code along from [this code-along by @kubucation on youtube](https://www.youtube.com/watch?v=2v11Ym6Ct9Q).

Ideally, zero dependencies, it'll rely entirely on Go standard lib

## Requirements

* [x] `GET /coasters` return list of coasters as JSON
* [x] `GET /coasters/{id}` returns coaster with specific id
* [x] `POST /coasters` accepts a new coaster to be added. 415 if not `application/json`
* [x] `GET /admin` required basic auth
* [ ] `GET /coasters/random` redirects (302) to random coaster id
