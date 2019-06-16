# Overview 

* set of opinionated tslint rules
* tries to make a fair trade-off between productivity, error avoidance and coding style
* targets side or hobby projects

## Setup

### Install

`yarn add --dev tslint-haezl-node`

### Update `tsconfig.json`:

```
{
    "extends": [
        "tslint-haezl-node"
    ],
    "rules": [
        // add/overwrite rules
    ]
}
```