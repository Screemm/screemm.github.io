---
layout: home
title: Version 2 Feature List
tags: changelog proctor
permalink: /proctor/dev_notes/changelog/version-2-feature-list
---

# Version 2 Feature List

Up until now, I haven't really been keeping a changelog for Proctor, however I have had some inspiration to change that. Concequently, as I don't know what has changed between version 1 and version 2, the following is more of a feature list.

### Slash commands

- `/stats` - This is intended to be a command that gives a bunch of stats about the quizzes taken, users and terms seen, however is currently broken at the time of posting.
- `/support` - This will DM the executor of the command an embed and button to open a support ticket with the Proctor Dev Team. All messages then sent to this bot from then on will be sent through to the Proctor Dev Team until the ticket is closed.

### Misc.

- Starting a quiz is done via select menus. The message for this may be posted anywhere, however the threads all get created under `#exam-room` regardless.
- The quizzes utilise the [Kotoba](https://kotobaweb.com) bot as the supplier and for an output of stats once a quiz has been completed.
- Proctor gives specified roles to people once they finish a quiz.
- The `#exam-room` channel also has it's messages nuked from orbit by Proctor to keep this channel squeeky clean and clutter free.

Going forward, there will be a defined format and recurring implementation day for bug fixes, enhancements, new features, etc. The only exception to this rule is if there is a `CRITICAL` bug that needs squashing ASAP.