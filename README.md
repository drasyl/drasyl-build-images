# drasyl Build Images

This repository is used to build docker images that are used to build and test
various parts of drasyl.

```bash
docker build --tag drasyl/drasyl-build-images:jdk-11-maven-3.6.3-gpg-pinentry-tty --file Dockerfile.jdk-11-maven-3.6.3-gpg-pinentry-tty --pull .
docker build --tag drasyl/drasyl-build-images:jdk-11-maven-3.6.3-graalvm-ce-21    --file Dockerfile.jdk-11-maven-3.6.3-graalvm-ce-21    --pull .
```