# Lambda Admin Module

A module for Lambda Players that allows Lambdas to become admins and enforce certain rules.

## Voice Types

This module adds two new Voice Types:

* adminscold  |  This Voice Type is used when an Admin scolds an offender
* sitrespond  |  This Voice Type is used when an offender responds to a Admin

## Text Types

This module adds two new Text Types:

* adminscold  |  This Text Type is used when an Admin scolds an offender
* sitrespond  |  This Text Type is used when an offender responds to a Admin

Literally the same thing.

You can add custom punishment lines as well via the text panel. All punish lines are labeled as punishreason

![image](https://user-images.githubusercontent.com/109770359/222877231-7f19aa7c-aee1-4f59-ba3a-86073c25d084.png)

## Profile Panel Integration

![image](https://user-images.githubusercontent.com/109770359/222877109-09c138fa-3713-46c3-8ce6-fa769ef6d1e5.png)

Admin Module Settings

![image](https://user-images.githubusercontent.com/109770359/222876669-8a1b783b-111e-4fec-9805-e4a87052e164.png)

## Custom Bad Words

You can add your own words to be against the "No Bad Words" rule by editing admin-bannedwords.json, located in garrysmod/data/lambdaplayers.

Example JSON

```json
[
    "hello",
    "sorry",
    "goodbye"
]
```
