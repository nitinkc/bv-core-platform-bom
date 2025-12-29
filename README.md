# bv-platform-bom

Using [Jitpack](https://jitpack.io/) to avoid publishing the artifact

Create a release via [https://github.com/nitinkc/bv-core-platform-bom/tags](https://github.com/nitinkc/bv-core-platform-bom/tags) 
and let `maven-publish` from github action do the rest.

### Check Effective POM
```sh
mvn help:effective-pom
```