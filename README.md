# woocommerce-test
A simple WooCommerce Rest API test app

## Install

```
    $ yarn install
```

## Run

```
    $ yarn dev
```

You'll need an instance of Redis running. To test this with a real WooCommerce store, you'll need
something like ngrok to expose your localhost to the internet.

For styling purposes there's a static page that can be accessed at this url: `/return?fake=1`

## Config variables

```
    REDIS_CONNECTION_STRING
    ENFORCE_HTTPS = wether to force https
    BASE_URL = overrides the localhost base url
```
