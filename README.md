A fork of Circle CI Demo app for Go. Added functionality to config.yml to test for env vars, download ghr, and upload compiled binary release to github releases section using ghr.

How to:

Fork this repo, go to github and issue yourself a personal token, go to Circle CI add github repo,  add environment variable in CircleCI for GITHUB_TOKEN with value of your github token, and then edit version in line 78 in config.yml to trigger CircleCI build. Watch the build stages and the outpit in CircleCI.

Edit line 78 in .circleci/config.yml to set version or path of release etc.

Original readme below:

# CircleCI 2.0 Demo Application: Go (Golang) [![CircleCI Build Status](https://circleci.com/gh/CircleCI-Public/circleci-demo-go.svg?style=shield)](https://circleci.com/gh/CircleCI-Public/circleci-demo-go) [![MIT Licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/CircleCI-Public/circleci-demo-go/master/LICENSE.md)

This is an example application showcasing how to run Go on CircleCI 2.0.

You can follow along with this project by reading the following doc: https://circleci.com/docs/2.0/language-go/
