# Quickstart for Node.js in the App Engine flexible environment

This is the sample application for the
[Quickstart for Node.js in the App Engine flexible environment][tutorial]
tutorial found in the [Google App Engine Node.js flexible environment][appengine]
documentation.

gounna:
- 관련 quick Lab
- app.js에 hello world를 app.yaml 에 설정파일을 넣어서 gcloud 커맨드로 배포하는 시나리오
~~~
gcloud app start
gcloud app browse
~~~

https://qwiklabs.com/focuses/657?parent=catalog


* [Setup](#setup)
* [Running locally](#running-locally)
* [Deploying to App Engine](#deploying-to-app-engine)
* [Running the tests](#running-the-tests)

## Setup

Before you can run or deploy the sample, you need to do the following:

1.  Refer to the [appengine/README.md][readme] file for instructions on
    running and deploying.
1.  Install dependencies:

    With `npm`:

        npm install

    or with `yarn`:

        yarn install

## Running locally

With `npm`:

    npm start

or with `yarn`:

    yarn start

## Deploying to App Engine

With `npm`:

    npm run deploy

or with `yarn`:

    yarn run deploy

## Running the tests

See [Contributing][contributing].

[appengine]: https://cloud.google.com/appengine/docs/flexible/nodejs
[tutorial]: https://cloud.google.com/appengine/docs/flexible/nodejs/quickstart
[readme]: ../../README.md
[contributing]: https://github.com/GoogleCloudPlatform/nodejs-docs-samples/blob/master/CONTRIBUTING.md
