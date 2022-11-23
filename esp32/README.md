# Learn ESPHome

## On Local Machine

### 1 Prepare

```
pip3 install esphome
```

### 2 Build and Flash

```
esphome run matrix.yaml
```

## On Docker

```
docker run --rm -v "${PWD}":/config -it esphome/esphome wizard matrix.yaml
```

## Get GitHub Repo Stars

```sh
curl --silent 'https://api.github.com/repos/ThaddeusJiang/mojito-admin' -H 'Accept: application/vnd.github.preview' | jq ".stargazers_count"
```
