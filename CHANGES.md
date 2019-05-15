# amon-common Changelog

## not yet released

- The `err` returned from RelayClient.sendEvents has changed from being
  a `restify.RestError` to a `VError`. Before one could inspect
  `err.statusCode`, now one needs to use `VError.info(err).statusCode`.
    XXX test this

## 1.0.0

Copy of state from sdc-amon.git:common/
