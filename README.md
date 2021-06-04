# Takes a screenshot of the given page

A simple web service that takes screenshot of the given URL.

Run with `docker run -p 8080:8080 gcr.io/as-a-service-dev/screenshot`

## API

### URL parameters:

* `url`: The URL of the website to screenshot

Example: `/?url=https://steren.fr`

## Running the server locally

* Build with `docker build . -t screenshot`
* Start with `docker run -p 8080:8080 screenshot`
* Open in your browser at `http://localhost:8080/?url=https://steren.fr`

## Screenshot
![Screenshot](https://user-images.githubusercontent.com/26526913/120745075-cbda5280-c515-11eb-8bd6-f8e400a3c058.png)


