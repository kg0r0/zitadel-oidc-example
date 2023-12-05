# zitadel-oidc-example

## Usage

```
$ export CLIENT_ID=XXX
$ export CLIENT_SECRET=XXX
$ go run main.go
```

### Docker

```
$ docker build . -t zitadel-oidc-example
$ docker run -p3000:3000 -it zitadel-oidc-example
```

## References
- https://github.com/zitadel/oidc
- https://openid.net/developers/certified-openid-connect-implementations/
- https://docs.docker.com/language/golang/build-images/
