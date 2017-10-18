# docker-typescript

Docker typescript image.

Add the following to your .bashrc:

```
alias node="docker run --rm -it --volume \$(pwd):/app prinsmike/docker-typescript node"
alias npm="docker run --rm -it --volume \$(pwd):/app prinsmike/docker-typescript npm"
alias tsc="docker run --rm -it --volume \$(pwd):/app prinsmike/docker-typescript tsc"
alias gulp="docker run --rm -it --volume \$(pwd):/app prinsmike/docker-typescript gulp"
alias webpack="docker run --rm -v \$(pwd):/app prinsmike/docker-typescript webpack"
alias create-react-app="docker run --rm -v \$(pwd):/app prinsmike/docker-typescript create-react-app"
alias yarn="docker run --rm -p 3000:3000 -v \$(pwd):/app prinsmike/docker-typescript yarn"
```
