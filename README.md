# ci-sample

CIツールでdocker buildするサンプルです。

| CI Tool   | Build Status |
|-----------|--------------|
| TravisCI  | [![Build Status](https://travis-ci.com/sotoiwa/ci-sample.svg?branch=master)](https://travis-ci.com/sotoiwa/ci-sample) |
| CircleCI  | [![CircleCI](https://circleci.com/gh/sotoiwa/ci-sample.svg?style=svg)](https://circleci.com/gh/sotoiwa/ci-sample) |
| CodeBuild | ![CodeBuild](https://codebuild.ap-northeast-1.amazonaws.com/badges?uuid=eyJlbmNyeXB0ZWREYXRhIjoiOVAraGVpRlIrTGxYUUZnQy9qSzFtUFFTdVViNm5JOHlvS3hQb3Z2TXVvUWtZRWNrNWZveVF0YXphK2N2ajZWSDg1ZVIxbTAzUVR1dTJ1MEdpeWFwdTNzPSIsIml2UGFyYW1ldGVyU3BlYyI6Im9pSVJBQ3l5RmYxR1VpSE4iLCJtYXRlcmlhbFNldFNlcmlhbCI6MX0%3D&branch=master) |

## Slack通知

TravisCIの場合、Slack Appのトークンを各リポジトリのymlに書く。トークンを暗号化する場合は各リポジトリ毎に暗号化する必要がある。
CircleCIの場合、Slack AppのWebhook URLをコンソールから各リポジトリに設定する。

CodeBuildの場合、SNSトピックに通知可能で、そこからAWS ChatBotか、Lambdaで通知する。
CloudEventsでも可能。

- [【開発者必見】Codeシリーズに最適化された通知サービスNotificationsがリリースされました！](https://dev.classmethod.jp/cloud/aws/new-code-series-notification/)
