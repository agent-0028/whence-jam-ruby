# Technical Specification

## General guidelines

* The code should be as simple as possible to achieve the Product Specifications
* There should be some kind of end to end test
  * For the command line app, a markdown test plan for a human to follow will be sufficient
* There should be unit tests

## Architecture and Framework guidelines

* `rbenv` should be used to manage what version of Ruby is supported
* A Gemfile and versioned Gemfile.lock should be used to manage dependencies
* The web application and API should use the Sinatra framework

