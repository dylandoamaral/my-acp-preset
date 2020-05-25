# my-qush-preset

## Description

this is my personnal preset for [qush](https://github.com/dylandoamaral/qush).

## Preset

```json
{
  "name": "dymoji",
  "contributors": ["dylandoamaral"],
  "actions": {
    "a": {
      "value": "add",
      "description": "to use when you add something new"
    },
    "d": {
      "value": "delete",
      "description": "to use when you delete something old"
    },
    "r": {
      "value": "refactor",
      "description": "to use when you change an intern structure"
    },
    "f": {
      "value": "fix",
      "description": "to use when you fix a bug"
    },
    "s": {
      "value": "setup",
      "description": "to use when you setup something"
    },
    "u": {
      "value": "update",
      "description": "to use when you update something"
    }
  },
  "targets": {
    "d": {
      "value": "📕",
      "description": "to use when you comment some functionnalities"
    },
    "t": {
      "value": "👓",
      "description": "to use when you make some tests"
    },
    "p": {
      "value": "💻",
      "description": "to use when you do something for the project"
    },
    "e": {
      "value": "⭐",
      "description": "to use when a big change happened"
    }
  },
  "template": "<target> <action>: <message>"
}

```