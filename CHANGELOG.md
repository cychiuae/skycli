## 2.2.0 (2020-03-02)

### Features

- Support multiple contexts #180
- Support deploying static assets #190
- Support domain reverification

## 2.1.2 (2020-01-22)

### Bug Fixes

- Fix skycli config set-cluster --cluster option
- Make some command options mutually exclusive

### Internals

- Run runtime and dev dependencies

## 2.1.1 (2020-01-21)

### Bug Fixes

- Stub unused storage methods

### Internals

- Run prettier,lint,typecheck,test before deploy

## 2.1.0 (2020-01-21)

### Breaking Changes

- Update skygear.yaml format
- Apply API versioning

### Features

- Add custom domain commands (#181)
- Implement k8s credential commands
- Strict command line options (#96)
- Remove signup invitation flow

### Internals

- Upgrade skygear node client
- Update dependencies
- Replace gulp with rollup

## 2.0.0-alpha.7 (2019-11-29)

### Features

- Support pre-built docker image deployment

### Bug Fixes

- Fix app name validation by checking app name in controller

### Breaking Changes

- Update for new controller template API

## 2.0.0-alpha.6 (2019-11-26)

### Breaking Changes

- Update controller API endpoints
- Update artifact upload with asset gear

## 2.0.0-alpha.5 (2019-11-20)

### Features

- Add template commands
- Allow providing password & setting cluster using parameters

## 2.0.0-alpha.4 (2019-11-13)

### Features

- Update secret commands
- Update microservice environment payload
- Support setting custom cluster server

### Other notes

- Update signup copywriting to ask for email verification
- Update SDK
- Update staging and production api key
- Remove examples

## 2.0.0-alpha.3 (2019-10-24)

### Other notes

- Fix skygear sdk version
- Update scaffolding template and config file path

### Bug Fixes

- Buffer build log JSON properly
- Display API key of first client and make wording consistent

## 2.0.0-alpha.2 (2019-10-09)

### Features

- App list command
- Collaborator commands
- Support microservice template
- Support upload artifact to minio with form POST

### Other notes

- Integrate Skygear SDK

### Bug Fixes

- Fix configuration resolution when context key is not "default"


## 2.0.0-alpha.1 (2019-08-29)

### Breaking Changes

- Update global config attributes to use underscore instead CamelCase

### Features

- View and update user config

## 2.0.0-alpha.0 (2019-08-19)

### Features

- Initial release
