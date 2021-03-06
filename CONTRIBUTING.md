# Contributing to Service Mocker

Thanks for contributing to Service Mocker!

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

## Submitting an issue

### 1. Search for Duplicates

Before you submit an issue, please search the issue tracker as it may already exist or even have been fixed.

### 2. Use a clear and descriptive title

A good title may catch our attention and therefore, your issue may be resolved quickly.

### 3. Include as much information as possible

If you are logging a bug, make sure to include the following:

- The version of Service Mocker
- The browser you are running on
- Steps to reproduce the behavior

### 4. Be patient

We want to fix all the issues as soon as possible, but we can't make guarantees about how fast your issue can be resolved. Your understanding and patience is greatly appreciated.

## Submitting a pull request

### 1. Make your changes in a new git branch

```
git checkout -b my-fix-branch develop
```

### 2. Follow the code style

Run `npm run lint` before committing.

### 3. Test your code

Make sure `npm test` passes. If you are fixing an bug or adding new features, please add appropriate test case if possible.

### 4. Don't include unrelated changes

### 5. Don't submit PRs against the `master` branch

The `master` branch is considered as a snapshot of the latest release. All development should be done in the `develop` branch.

### 6. Use a clear and descriptive title for your PR

### 7. Write a convincing description

- If you are fixing a bug:

    - Provide detailed description of the bug, or links to the related issues.

- If you are adding new features:

    - Provide convincing reason to add this reason.


## Development setup

Before starting, make sure you are using [Node.js](http://nodejs.org/) 6+.

After cloning the repo, run:

```bash
npm install
```

Then run:

```bash
npm start
```

to start a dev server at `http://localhost:3000`.

If you are editing the documentations, run:

```bash
npm run doc
```

The docs will be served at `http://localhost:8080`.

### Running the Tests

To run unit tests in browser with live reloading, simply run `npm start` then navigate your browser to `http://localhost:3000`.

To run unit tests with karma, use:

```bash
npm run test
```

This task will lint your code and start a session with chrome.

To run cross browser tests with karma, use:

```bash
npm run test:full
```

This task will run tests in Chrome, Firefox and Safari.

It's recommended to **run tests locally before you submit a pull request**, though all the tests will be executed again on the CI server.
