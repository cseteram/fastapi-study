# FastAPI Study

FastAPI 개인용 스터디 기록 w/ [UPnL] 2022 FastAPI Study

## How to run

### Docker
```console
docker run --rm -d -p 8080:80 ghcr.io/cseteram/fastapi-study
```

### Helm
```console
# Edit deploy/values.yaml appropriately
helm install [NAME] ./chart -f deploy/values.yaml
```

[UPnL]: https://github.com/upnl
