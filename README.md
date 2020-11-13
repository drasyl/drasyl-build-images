# drasyl Build Images

This repository is used to build docker images that are used to build and test
various parts of drasyl.

```bash
docker build -t drasyl/drasyl-build-images:jdk-11-maven-3.6.3-gpg-pinentry-tty -f Dockerfile.jdk-14-maven-3.6.3-gpg-pinentry-tty .
```