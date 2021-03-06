# prologic - todo

The official container and documentation was made by [prologic](https://hub.docker.com/r/prologic/todo).

## Volumes

Set the following volumes with the -v tag.

| Outside mount/volume name | Container mount        | Description            |
| ------------------------- | ---------------------- | ---------------------- |
| `todo`                    | `/go/src/todo/todo.db` | Database for todo list |

## Ports

Set the following ports with the -p tag.

| Container Port | Recommended outside port | Protocol | Description |
| -------------- | ------------------------ | -------- | ----------- |
| `8000`         | `8000`                   | TCP      | WebUI       |

## rebuild.sh

```shell
#!/bin/sh
docker stop todo
docker rm todo
docker pull prologic/todo
docker run --name todo \
    -p 8000:8000 \
    --restart unless-stopped \
    -v todo:/go/src/todo/todo.db \
    -d prologic/todo
```
