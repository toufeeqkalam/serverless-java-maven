# Serverless Java Starter

A Go starter project for [Serverless Framework](https://serverless.com/framework/) with support for Maven.

### Requirements

- [Install JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
- [Install Maven](https://maven.apache.org/)
- [Install the Serverless Framework](https://serverless.com/framework/docs/providers/aws/guide/installation/)
- [Configure your AWS CLI](https://serverless.com/framework/docs/providers/aws/guide/credentials/)

### Installation

Create a new project

```sh
$ serverless install --url https://github.com/fwang/serverless-java-maven-starter --name serverless-java-maven-starter
```


### Usage

Build

```sh
$ mvn package
```

Invoke a function locally

```
$ serverless invoke local -f hello
```

### Deploying

Deploy your project

```sh
$ serverless deploy
```

Deploy a single function

```sh
$ serverless deploy function --function hello
```

### Support

- Send us an [email](mailto:frank@seed.run) if you have any questions
- Open a [new issue](https://github.com/AnomalyInnovations/serverless-java-maven-starter/issues/new) if you've found a bug or have some suggestions.
- Or submit a pull request!

### Maintainers

Maintained by [Anomaly Innovations](https://anoma.ly/). [**Subscribe to our newsletter**](http://eepurl.com/cEaBlf) for updates. Send us an [email](mailto:contact@anoma.ly) if you have any questions.
