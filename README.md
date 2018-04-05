This is a fork of [fayimora/basic-scala-project.g8](https://github.com/fayimora/basic-scala-project.g8) - a [giter8](https://github.com/n8han/giter8) template for generating a new scala project. It comes bundled with:

* `main` and `test` source directories
* [Specs2](http://etorreborre.github.io/specs2/)
* SBT configuration for `0.13.0` and `Scala 2.10.3` dependencies
* project `name`, `organization` and `version` customizable as variables


## USAGE

If you have giter8 installed:

```
g8 fernandoacorreia/basic-scala-project
```

Using Docker, without installing giter8:

```
docker run --rm -it -v $PWD:/g8out fernandoacorreia/g8 fernandoacorreia/basic-scala-project
```

## CHANGELOG

### 0.3
* specs2 3.8.3
* sbt 0.13.11
* Scala 2.11.8

### 0.2
* specs 2.3.7 in place of Scalatest

### 0.1.2
* Scala 2.10.3

### 0.1.1
* Scalatest 1.9.2 for testing
* Sbt 0.13.0

### 0.1.0 (Initial release!)
* Scalatest 1.9.1 for testing
* Sbt 0.12.4
* Scala 2.10.2
