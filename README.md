# install registry
 npm install @louisnguyen707/git-registry

# helpers

This helpers is a utility collection that focus on helping javascript developer resolving daily task faster.

## Tech stacks

- JavaScript

## Install

1. create `.npmrc` and add Scoped Package
    **Scoped Packages** are simply put as the packages grouped under a namespace. You might have seen @angular/core or @react/something. So, these are the scoped packages.
    ```
    @louisnguyen707:registry=https://npm.pkg.github.com
    //npm.pkg.github.com/:_authToken=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
    ```

2. Install library
  - Define script

    ```
     "hepler-config": "rm -rf node_modules/@louisnguyen && npm install git+https://github.com/louisnguyen707/git-registry.git --no-save && cd node_modules && mv @louisnguyen707/git-registry @louisnguyen"
    ```
and enter terminal run cli

 `npm run hepler-config`

## Benefits

- Small bundle size
- Work with all frameworks
- Simple to use

## Features

## Usage

Guide to use the library.
