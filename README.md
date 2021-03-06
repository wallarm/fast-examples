# Wallarm FAST - Integration examples

## What is FAST?

Wallarm's Framework for Automated Security Testing (FAST) is a purpose-built tool that allows you to reveal vulnerabilities in applications and APIs by generating and executing security tests in an automatic way. SQL injections and XSS are examples of such vulnerabilities.

Below you can find links to several examples of FAST usage, from manual script testing to full integration with common CI tools.

Learn more about FAST:
* [FAST website](https://wallarm.com/products/fast) 
* [FAST documentation](https://docs.fast.wallarm.com/en/)

## Manual 

* Testing a minimalistic and vulnerable Ruby on Rails application with Selenium:
https://github.com/wallarm/fast-example-rails
* Automated testing of [Damn Vulnerable Web Application - DVWA](http://www.dvwa.co.uk/) with Selenium:
https://github.com/wallarm/fast-example-dvwa

## Jenkins

* Autotesting DVWA in a Jenkins freestyle pipeline:
https://github.com/wallarm/fast-example-jenkins-dvwa-integration
* Plugin for the freestyle Jenkins projects:
https://github.com/jenkinsci/wallarm-fast-plugin (also at https://github.com/wallarm/FastJenkinsPlugin)

## CircleCI

* Example of running DVWA with FAST in the CircleCI environment:
https://github.com/wallarm/fast-example-circleci-dvwa-integration
* Similar setup with the Ruby on Rails example:
https://github.com/wallarm/fast-example-circleci-rails-integration
* The same example, but using FAST as an Orb ([featured here](https://circleci.com/orbs/):
https://github.com/wallarm/fast-example-circleci-orb-rails-integration
* Link to the Orb itself: https://github.com/wallarm/fast-orb
* Example of integration directly into existing specs via wallarm API: https://github.com/wallarm/fast-example-api-circleci-rails-integration

## Gitlab

* Testing DVWA in Gitlab CI/CD:
https://gitlab.com/wallarm/fast-example-gitlab-dvwa-integration

## Azure
* DVWA testing in Azure DevOps pipeline: https://github.com/wallarm/fast-example-azure-dvwa-integration

## Bamboo
* An example of a Bamboo pipeline testing DVWA: https://github.com/wallarm/fast-example-bamboo-dvwa-integration