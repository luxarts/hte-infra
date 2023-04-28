# hte-infra

# Run
```
docker compose up --build -d
```
_Note: On MacOS you must set `DOCKER_BUILDKIT=0` before the command as mentioned [here](https://stackoverflow.com/a/66695181)._

# Run specific file
```
docker compose -f <filename> up --build -d
```