# Wallarm FAST - Integration examples

## What is FAST?

Wallarm's Framework for Automated Security Testing (FAST) is a purpose-built tool that allows you to reveal vulnerabilities in applications and APIs by generating and executing security tests in an automatic way. SQL injections and XSS are examples of such vulnerabilities.

Below you can find links to several examples of FAST usage, from manual script testing to full integration with common CI tools.

More information on FAST can be found [here](https://wallarm.com/products/fast) and [here](https://docs.fast.wallarm.com/en/).

## Manual 

* Testing a minimalistic, yet vulnerable [Ruby on Rails](https://rubyonrails.org/) application with [Selenium](https://selenium.dev/):
https://github.com/wallarm/fast-example-rails
* Automated testing of [DVWA](http://www.dvwa.co.uk/) with Selenium:
https://github.com/wallarm/fast-example-dvwa

## Jenkins

* Autotesting DVWA in a [Jenkins](https://jenkins.io/) freestyle pipeline:
https://github.com/wallarm/fast-example-jenkins-dvwa-integration
* Plugin for the freestyle Jenkins projects:
https://github.com/jenkinsci/wallarm-fast-plugin (also at https://github.com/wallarm/FastJenkinsPlugin)

## CircleCI

* Example of running DVWA with FAST in the [CircleCI](https://circleci.com/) environment:
https://github.com/wallarm/fast-example-circleci-dvwa-integration
* Similar setup with the Ruby on Rails example:
https://github.com/wallarm/fast-example-circleci-rails-integration
* The same example, but using FAST as an Orb ([featured here](https://circleci.com/orbs/):
https://github.com/wallarm/fast-example-circleci-orb-rails-integration
* Link to the Orb itself: https://github.com/wallarm/fast-orb

## Gitlab

* Testing DVWA in [Gitlab CI/CD](https://docs.gitlab.com/ee/ci/):
https://gitlab.com/wallarm/fast-example-gitlab-dvwa-integration
