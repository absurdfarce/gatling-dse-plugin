# Gatling DSE Plugin

This project is a plugin for the Gatling load injector.
It adds CQL support in Gatling for Datastax Enterprise.
It allows for benchmarking Datastax Enterprise features, including DSE Graph Fluent API.

## Building

### Requirements 

- Java 1.8
- Gradle 4.1+
- Gatling 2.3.0+

### Steps

Run `./gradlew build`.  The plugin jar will be in the `build/libs/` directory.

## Installation

Get a release tarball.  Copy the plugin jar into Gatling `lib` folder.

## More Information on Usage

See [CHANGELOG.md](CHANGELOG.md) for release notes and updates.
A stand-alone distribution that wraps the plugin is also available at https://github.com/datastax/gatling-dse-stress.

Gatling documentation is available at the following locations:

- [Gatling Quickstart](http://gatling.io/docs/current/quickstart/)
- [Gatling Cheatsheet](http://gatling.io/docs/current/cheat-sheet/)

## Contributions

This project was inspired by Mikhail Stepura ([Mishail](https://github.com/Mishail)'s project [GatlingCql](https://github.com/gatling-cql/GatlingCql/commits/master)).

It has been developped by Brad Vernon ([ibspoof](https://github.com/ibspoof)) and improved by the following contributors:

* Matt Stump ([mstump](https://github.com/mstump))
* James Kavanagh ([jkds](https://github.com/jkds))
* Robert Stupp ([snazy](https://github.com/snazy))
* Pierre Laporte ([pingtimeout](https://github.com/pingtimeout))
