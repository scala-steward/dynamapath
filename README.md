# dynamapath - Dynamic Path Parsing [![Build Status](https://travis-ci.com/ChristopherDavenport/dynamapath.svg?branch=master)](https://travis-ci.com/ChristopherDavenport/dynamapath) [![Maven Central](https://maven-badges.herokuapp.com/maven-central/io.chrisdavenport/dynamapath_2.12/badge.svg)](https://maven-badges.herokuapp.com/maven-central/io.chrisdavenport/dynamapath_2.12)

## [Head on over to the microsite](https://ChristopherDavenport.github.io/dynamapath)

## Quick Start

To use dynamapath in an existing SBT project with Scala 2.11 or a later version, add the following dependencies to your
`build.sbt` depending on your needs:

```scala
libraryDependencies ++= Seq(
  "io.chrisdavenport" %% "dynamapath" % "<version>"
)
```

## Credits

Inspiration for this library was drawn from [path-to-regexp](https://github.com/pillarjs/path-to-regexp),
[Brandon Ros](https://github.com/brandonros) initially made me aware of the concept,
and I thought it was intriguing enough to merit translation.