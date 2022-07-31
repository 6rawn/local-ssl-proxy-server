# local-ssl-proxy-server

# Prerequisites

```sh
mkcert (https://github.com/FiloSottile/mkcert)
```

# Prepare for certificates

```sh
mkcert -install
mkcert localhost
```

# Launch local-ssl-proxy-server

```sh
npm run start
or
npm run start -- --target "your local port"
```
