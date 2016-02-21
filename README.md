# Modern Java

Example "Modern Java" build and tools.

This software is in the Public Domain.  Please see [LICENSE.md](LICENSE.md).

[![License](https://img.shields.io/badge/license-PD-blue.svg?style=flat)](http://unlicense.org)

## Features

* Strive to make maven quiet.
* Assume Github and Travis CI.
* Support gitflow style.
* Be fairly strict about code hygiene.
* Autoupdate dependencies, plugins, et al.
* Download sources and javadocs for dependencies.
* Basic logback testing support (but not logback itself).
* Prefer AssertJ to Hamcrest.  Hamcrest is quite good, however using the
  latest Hamcrest version conflicts with Spring Boot, et al.
* System rules for junit and example integration test.

## Releases

### 0

* Basic functionality for vanila Modern Java project.

## TODO

* Hook in maven-profile extension, once figure out how to set up a
  `.mvn/extensions.xml` file in the archetype
