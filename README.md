# 2025-02-06-docker

```bash

docker run \
    --rm \
    -it \
    -e password="password" \
    -p 8787:87878 \
    -v \$(pwd):/home/rstudio/pizza \
    rocker/rstudioL4.4.2