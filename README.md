# Flutter CI/CD Demo

Demo for a Flutter app ci/cd pipeline

## Features

- [x] CI service integration for Android and iOS app
    - [x] Travis CI: [.travis.yml](.travis.yml) (Jobs: https://travis-ci.org/mobiledevops/flutter-ci-demo)
    - [x] CircleCI: [.circleci/config.yml](.circleci/config.yml) (Jobs: https://circleci.com/gh/MobileDevOps/flutter-ci-demo)
    - [x] GitLab CI/CD: [.gitlab-ci.yml](.gitlab-ci.yml) (Pipelines: https://gitlab.com/mobiledevops/flutter-ci-demo/pipelines)
        - Public shared runner doesn't support macOS build server

## Planned Features

- [ ] Unit / ui testing
- [ ] Different app configuration (bundle id)
- [ ] Signing the Android app with different key stores
- [ ] Signing the iOS app with different certificates and provisioning profiles
- [ ] Crash reporting integration
- [ ] Analytics integration
- [ ] Upload to Fabric.io Beta
- [ ] Upload to Google Play Store
