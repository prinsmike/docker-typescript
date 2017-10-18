# docker-typescript

Docker typescript image.

Add the following to your .bashrc:

```
alias node="docker run --rm -it --volume \$(pwd):/app prinsmike/typescript node"
alias npm="docker run --rm -it --volume \$(pwd):/app prinsmike/typescript npm"
alias tsc="docker run --rm -it --volume \$(pwd):/app prinsmike/typescript tsc"
alias gulp="docker run --rm -it --volume \$(pwd):/app prinsmike/typescript gulp"
alias webpack="docker run --rm -v \$(pwd):/app prinsmike/typescript webpack"
alias create-react-app="docker run --rm -v \$(pwd):/app prinsmike/typescript create-react-app"
alias yarn="docker run --rm -p 3000:3000 -v \$(pwd):/app prinsmike/typescript yarn"
```
