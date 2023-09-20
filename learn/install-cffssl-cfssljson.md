https://github.com/cloudflare/cfssl

```
go version

git clone git@github.com:cloudflare/cfssl.git
cd cfssl
make
tree bin

sudo chown -R $(whoami) $GOPATH/bin

go install github.com/cloudflare/cfssl/cmd/...@latest
```