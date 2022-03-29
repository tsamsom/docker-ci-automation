# Automation with Docker for CI/CD Workflows

[![Lint Code Base](https://github.com/BretFisher/allhands22/actions/workflows/call-super-linter.yaml/badge.svg)](https://github.com/BretFisher/allhands22/actions/workflows/call-super-linter.yaml)

> For Docker Community All Hands 2022

See this repositories [`.github/workflows`](.github/workflows) directory for the blow example workflows, ordered by number, simple to complex.

These examples are focused on five of Docker's [official GitHub Actions](https://github.com/marketplace?type=actions&query=publisher%3Adocker+).

These examples are based on three workflow diagrams on progressivly more complex automation pipelines:

1. [Basic code PR automation workflow](diagrams/basic-code-pr.png)
2. [Intermediate code PR automation workflow](diagrams/intermediate-code-pr.png)
3. [Advanced code PR automation workflow](diagrams/advanced-code-pr.png)

## Example Workflows

1. Basic Docker build
2. Adding BuildKit cache
3. Adding multi-platform builds
4. Adding metadata to images
5. Adding comments with image tags to PRs
6. Adding CVE scanning
7. Adding CVE security reporting
8. Adding unit testing
9. Adding integration testing
10. Adding Kubernetes smoke tests
11. Adding job parallelizing for mucho speed

This repository is part of a group of my sample repos on GitHub Actions:

* [bretfisher/github-actions-templates](https://github.com/BretFisher/github-actions-templates) - Main repository
* [bretfisher/super-linter-workflow](https://github.com/BretFisher/super-linter-workflow) - Reusable linter workflow
* [bretfisher/docker-build-workflow](https://github.com/BretFisher/docker-build-workflow)- Reusable docker build workflow
* (you are here) [bretfisher/allhands22](https://github.com/BretFisher/github-actions-templates) - Step by step example of a Docker workflow

## More reading

[Docker Build/Push Action advanced examples](https://github.com/docker/build-push-action/tree/master/docs/advanced)
[My full list of container examples and tools](https://github.com/bretfisher)

## Join my container DevOps community!

* [My "Vital DevOps" Discord server](https://devops.fan)
* [My weekly YouTube Live show](https://bret.live)
* [My courses and coupons](https://www.bretfisher.com/courses)