# lima-fast-mode-benchmark

## Prepare

### ARM
```bash
$ limactl start ./lima/docker-arm64.yaml
$ export DOCKER_HOST=$(limactl list docker-arm64 --format 'unix://{{.Dir}}/sock/docker.sock')
```


## Run benchmark

```bash
$ docker build -t nextjs .
```