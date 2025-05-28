# PoC 01

Expose an HTTP endpoint and redirect the call to a backend that requires mTLS.

This also print the request payload for debugging purposes (not recommended for production).

*Note:* SSL verify configuration will make HAProxy to return 503 when server certicate is not valid (e.g when some certificate in the chain expired)

## Running the example

- Get backend certificates to stablish mTLS connection
- Run docker compose
