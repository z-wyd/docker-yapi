# docker-yapi

## start

```bash
    docker run  -d \
    -v /yapi/mongodb/data:/app/mongodb/data \
    --name yapi   -p 3000:3000  wydcn/yapi:latest
```