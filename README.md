# Sources of the Swiss Blockchain Summer School 2017
See [https://blockchain-summer.epfl.ch](https://blockchain-summer.epfl.ch).

## Requirements

- [golang](https://golang.org/)
- [hugo](https://gohugo.io/)
- [make](https://www.gnu.org/software/make/)
- [rsync](https://rsync.samba.org/)

## Development and Deployment

Run a local server at [http://127.0.0.1:1313](http://127.0.0.1:1313):

```
make server
```

Build the site:

```
make build
```

Deploy the site:

```
make deploy
```
