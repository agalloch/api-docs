# Errors

The Fidor API uses the following error codes:


Error Code | Meaning
---------- | -------
400 | Bad Request
401 | Unauthorized -- Your API key is wrong
403 | Forbidden
404 | Not Found
405 | Method Not Allowed
406 | Not Acceptable
409 | The request was unsuccessful due to a conflict in the state of the resource
410 | Gone -- The resource requested has been removed from our servers
422 | Unprocessable Entity -- Your request is malformed
429 | Too Many Requests -- You exceeded the rate limit
500 | Internal Server Error
503 | Service Unavailable