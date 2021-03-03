Created inside docker image `tfwnicholson/datascience`
## How to use
Start docker container:
`docker run --rm  -it -w /app -v ~/.gitconfig:/etc/gitconfig -v $(pwd):/app -v ~/.ssh:/tmp/.ssh:ro -p 8888:8888 tfwnicholson/datascience`
Inside docker container start Jupyterlab:
`jupyter-lab --allow-root --ip=0.0.0.0`
Navigate to link presented
