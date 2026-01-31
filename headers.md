# Headers
```jsonc
GET https://www.googleapis.com/books/v1/volumes?q=Turing: {
  "Request Headers": {
    "user-agent": "PostmanRuntime/7.51.1", // The user agent for this request is PostmanRuntime/7.51.1
    "accept": "*/*", // Tells the server that the client will accept any type/subtype (wildcard)
    "postman-token": "9b0a71e8-a3d9-48f3-b0e1-c3896270335e", // Unique identifier for the request
    "host": "www.googleapis.com", // The server be contacted by the request
    "accept-encoding": "gzip, deflate, br", // The client can accept gzip, deflate, or br compression formats
    "connection": "keep-alive" // The client will keep the connection alive after the request is complete
  },
  "Response Headers": {
    "content-type": "application/json; charset=UTF-8", // The response content type is application/json with UTF-8 character encoding
    "vary": [
      "Origin",
      "X-Origin",
      "Referer"
    ], // The response headers vary based on the origin and referer of the request
    "content-encoding": "gzip", // The response is compressed using gzip compression
    "date": "Sat, 31 Jan 2026 16:58:30 GMT", // The date and time the response was generated
    "server": "ESF", // The server is running ESF software
    "x-xss-protection": "0", // Disables built-in XSS protection in the browser
    "x-frame-options": "SAMEORIGIN", // Prevents the page from being embedded in an iframe on other domains
    "x-content-type-options": "nosniff", // Prevents the browser from guessing the content type of the response
    "alt-svc": "h3=\":443\"; ma=2592000,h3-29=\":443\"; ma=2592000", // Tells the client that HTTP/3 is available and to remember that for 30 days (2592000 seconds)
    "transfer-encoding": "chunked" // The response is sent in chunks rather than all at once
  },
  "Response Body": "The console only shows response bodies smaller than 10 KB inline. To view the complete body, inspect it by clicking Open."
}
```