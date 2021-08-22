# My Personal VPS Proxy

## Contribution

### Getting started

```sh
make start
```

### Automated Git Deployment Setup

```sh
git remote add live ssh://<username>@<ip>/home/<username>/repositories/vps.git
```

### VPS Setup

```sh
docker network create proxy
```

### Deployment

```sh
git push live main
```
