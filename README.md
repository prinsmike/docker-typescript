# docker-typescript

Docker typescript image.

Add the following to your .bashrc:

```
alias node="docker run --rm -u=\$UID:\$(id -g \$USER) -it --volume \$(pwd):/app prinsmike/docker-typescript node"
alias npm="docker run --rm -u=\$UID:\$(id -g \$USER) -it --volume \$(pwd):/app prinsmike/docker-typescript npm"
alias tsc="docker run --rm -u=\$UID:\$(id -g \$USER) -it --volume \$(pwd):/app prinsmike/docker-typescript tsc"
alias gulp="docker run --rm -u=\$UID:\$(id -g \$USER) -it --volume \$(pwd):/app prinsmike/docker-typescript gulp"
alias webpack="docker run --rm -u=\$UID:\$(id -g \$USER) -v \$(pwd):/app prinsmike/docker-typescript webpack"
alias create-react-app="docker run --rm -u=\$UID:\$(id -g \$USER) -v \$(pwd):/app prinsmike/docker-typescript create-react-app"
alias yarn="docker run --rm -u=\$UID:\$(id -g \$USER) -p 3000:3000 -v \$(pwd):/app prinsmike/docker-typescript yarn"
```
