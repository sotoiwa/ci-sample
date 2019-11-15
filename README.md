# ci-sample

CIツールでdocker buildするサンプルです。

TravisCI: [![Build Status](https://travis-ci.com/sotoiwa/ci-sample.svg?branch=master)](https://travis-ci.com/sotoiwa/ci-sample)
CircleCI: [![CircleCI](https://circleci.com/gh/sotoiwa/ci-sample.svg?style=svg)](https://circleci.com/gh/sotoiwa/ci-sample)

## Slack通知

TravisCIの場合、Slack Appのトークンを各リポジトリのymlに書く。トークンを暗号化する場合は各リポジトリ毎に暗号化する必要がある。
CircleCIの場合、Slack AppのWebhook URLをコンソールから各リポジトリに設定する。
