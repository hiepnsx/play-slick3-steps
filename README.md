# play-slick3-steps example
[![Codacy Badge](https://api.codacy.com/project/badge/grade/740e586f17964c779ce3c146c272c560)](https://www.codacy.com)
[![Build Status](https://travis-ci.org/pedrorijo91/play-slick3-steps.svg)](https://travis-ci.org/pedrorijo91/play-slick3-steps)

Simple working app using play 2.4 and slick 3.1.0 with mysql. Step by step tutorial at [https://pedrorijo91.github.io/blog/play-slick/](https://pedrorijo91.github.io/blog/play-slick/)

Created since the [available demos](https://github.com/playframework/play-slick/tree/master/samples) have too much irrelevant code to who wants to integrate slick 3.1.0 with a play app.

Based on [bhavyalatha26/play-scala-slick-example](https://github.com/bhavyalatha26/play-scala-slick-example).

Removed some code such as:

* Dependency Injection with [guice](https://github.com/google/guice)
* Traits and implementation classes
* Useless controllers
* Support for i18n
* activator

=== Getting Started ===

To run this demo using activator:

 1. `git clone` this repository
 2. Update the MySQL server url, username and password in `conf/application.conf`
 3. Create a `playScalaSlickExample` database on your MySQL server.

    CREATE DATABASE playScalaSlickExample;

 4. Launch the demo using `activator ~run`
 5. Open the Play web server at http://localhost:9000
 6. You should be prompted to apply the evolution script. Apply the script.
 7. You should now see the app running.