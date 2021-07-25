# Task

Implement a HTTP service providing the following API:

## `POST /<key>`

### Description

Stores the given POST data under `key`.

### Return Codes

- `200 OK`: The data was stored.

## `GET /<key>`

### Description

Retrieves the value previously stored at `key`, if one exists.

### Return Codes

- `200 OK`: The data was retrieved.
- `404 Not Found`: No value has been stored at this key.

## `DELETE /<key>`

### Description

Removes any value stored at `key`.

### Return Codes

- `200 OK`: The value was deleted.
