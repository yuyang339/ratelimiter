# ratelimiter
This project is to produce a rate-limiting module that stops a particular requestor from making too many http requests within a particular period of time. The module exposes a method that keeps track of requests and limits it such that a requester can only make 100 requests per hour. After the limit has been reached, return a 429 with the text "Rate limit exceeded. Try again in #{n} seconds".
