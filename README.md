# Intent format
```
##intent:INTENT_NAME
- user response example
- …
```

# Domain format
```
FORMAT
intents:
  - intent_name1

utter_can_policy:
  - text: sentence one

```
# Story format

```
FORMAT
## STORY NAME
* user_intent_name1
  - bot_response(utter_*name*)
* user_intent_name2
  - bot_response(utter_*name*)

```