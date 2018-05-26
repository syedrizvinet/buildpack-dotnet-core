# .NET Core Buildpack Changelog

## 2018-05-26

- Added tests
- Added Appveyor CI
- Added heroku-18 stack support

## 2018-05-13

- Updated .NET Core SDK 2.1.200

## 2018-04-18

- Updated .NET Core SDK 2.1.105

## 2018-04-06

- Updated .NET Core SDK 2.1.104

## 2018-03-30

- Updated .NET Core SDK 2.1.103

## 2018-03-15

- Updated .NET Core SDK 2.1.101

## 2018-01-13

- Updated .NET Core SDK 2.1.4

## 2018-01-01

- Added .NET Core 1.1.5 LTS support (Thanks @bolorundurowb)
- Updated .NET Core SDK 2.1.3

## 2017-11-04

- Removed `dotnet restore` step because it is run implicitly as part of `dotnet publish`
- Extremely optimized slag size (`DOTNET_SKIP_FIRST_TIME_EXPERIENCE:1`)
- Updated .NET Core SDK 2.0.2

## 2017-11-03

- Added support `PROJECT_FILE` and `PROJECT_NAME` environment variables ([#23](https://github.com/jincod/dotnetcore-buildpack/pull/23))