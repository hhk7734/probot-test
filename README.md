## 프로젝트 생성

```shell
yarn create probot-app probot-test

Let's create a Probot app!
Hit enter to accept the suggestion.

? App name: probot-test
? Description of app: A Probot app
? Author's full name: Hyeonki Hong
? Which template would you like to use? basic-ts => Comment on new issues - written in TypeScript
```

## Github App 생성

Github -> Settings -> Developer settings -> Github Apps -> New Github App

- Github App name: `<app name>`
- Webhook URL: `<probot server url>`
- Permissions
  - Issues: Read and write
  - Metadata: Read-only
- Subscribe to events
  - Isuues

Save

## Github App 설치

Github -> Settings -> Developer settings -> Github Apps -> 생성된 앱 edit

- Install App

## Github App 연동

Github -> Settings -> Developer settings -> Github Apps -> 생성된 앱 edit

- General
  - App ID
  - Private keys
    - Generate a private key

https://probot.github.io/docs/configuration/

```
APP_ID=
PRIVATE_KEY_PATH=
```
