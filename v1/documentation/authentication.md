# Authentication

## API Key

Every user must obtain a public API key to make requests.
This key is sent in clear text along with every request.

The parameter name is `api_key`.

## API Secret Token

Every user receives a companion private secret token. This string is used as a
salt in generating request signatures and is never sent in clear text.

The parameter name is `secret`.
