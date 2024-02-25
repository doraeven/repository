# Motu Maven Repository

![Static Badge](https://img.shields.io/badge/build-passing-brightgreen)
![GitHub License](https://img.shields.io/github/license/doraeven/commons)

Motu Maven Repository (releases + snapshots).

## Introduction

We set up a repository on github to store the jar packages we publish.

## Usage

Modify **pom.xml** add Motu remote repository.

```xml
<repository>
	<id>motu</id>
	<name>Motu Repository</name>
	<url>https://raw.github.com/doraeven/repository/maven/</url>
</repository>
```

## Repository

The repository support multiple versions.

| name      | url                                                   | remark               |
| --------- | ----------------------------------------------------- | -------------------- |
| maven     | https://raw.github.com/doraeven/repository/maven/     | releases + snapshots |
| releases  | https://raw.github.com/doraeven/repository/releases/  | stable               |
| snapshots | https://raw.github.com/doraeven/repository/snapshots/ | test                 |

## License

The project is released under version 2.0 of the [Apache License](https://www.apache.org/licenses/LICENSE-2.0).
