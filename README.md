# my-qush-preset

## Description

this is my personnal preset for [qush](https://github.com/dylandoamaral/qush).

## Preset

```json
{
  "name": "dymoji",
  "contributors": ["dylandoamaral"],
  "version": "1.0.0",
  "template": "<target> <action>: <message>",
  "instructions": [
    {
      "name": "action",
      "description": "the kind of action you perfom inside the commit",
      "elements": [
        {
          "from": "a",
          "to": "add",
          "description": "to use when you add something new"
        },
        {
          "from": "d",
          "to": "delete",
          "description": "to use when you delete something old"
        },
        {
          "from": "r",
          "to": "refactor",
          "description": "to use when you change an intern structure"
        },
        {
          "from": "f",
          "to": "fix",
          "description": "to use when you fix a bug"
        },
        {
          "from": "s",
          "to": "setup",
          "description": "to use when you setup something"
        },
        {
          "from": "u",
          "to": "update",
          "description": "to use when you update something"
        }
      ]
    },
    {
      "name": "target",
      "description": "the domain targeted by the commit",
      "elements": [
        {
          "from" : "d",
          "to": "ðŸ“•",
          "description": "to use when you comment some functionnalities"
        },
        {
          "from": "t",
          "to": "ðŸ‘“",
          "description": "to use when you make some tests"
        },
        {
          "from": "p",
          "to": "ðŸ’»",
          "description": "to use when you do something for the project"
        }
      ]
    }
  ]
}
```