# Helix Index Big Tree

> Like [`helix-index-tree`](https://github.com/adobe/helix-index-tree), but for big trees

## Status
[![codecov](https://img.shields.io/codecov/c/github/adobe/helix-index-big-tree.svg)](https://codecov.io/gh/adobe/helix-index-big-tree)
[![CircleCI](https://img.shields.io/circleci/project/github/adobe/helix-index-big-tree.svg)](https://circleci.com/gh/adobe/helix-index-big-tree)
[![GitHub license](https://img.shields.io/github/license/adobe/helix-index-big-tree.svg)](https://github.com/adobe/helix-index-big-tree/blob/master/LICENSE.txt)
[![GitHub issues](https://img.shields.io/github/issues/adobe/helix-index-big-tree.svg)](https://github.com/adobe/helix-index-big-tree/issues)
[![LGTM Code Quality Grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/adobe/helix-index-big-tree.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/adobe/helix-index-big-tree)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

## Installation

## Usage

```bash
wsk action invoke helix-services/index-big-tree@v1
```

This service is meant to be invoked from [helix-index-tree](https://github.com/adobe/helix-index-tree), so it won't be made available as a web action.

For more, see the [API documentation](docs/API.md).

## Development

### Deploying Helix Service

Deploying Helix Service requires the `wsk` command line client, authenticated to a namespace of your choice. For Project Helix, we use the `helix-index` namespace.

All commits to master that pass the testing will be deployed automatically. All commits to branches that will pass the testing will get commited as `/helix-index/index-big-tree@ci<num>` and tagged with the CI build number.
