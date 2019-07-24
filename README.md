# Honorific Title

A Slack applicaiton, written in Kotlin, running as an AWS Lambda

The idea is that a random title will be given to a user.

## Usage

    /award-title @user
    The user @user has been give the honorific title of @title

    /assign-title @user "title"
    The user @user has been give the honorific title of "title"

    /show-titles
    @user @title
    @user2 @title2
    ...

## Additonal features

Store assigned titles, so that /show-titles returns a list of users and their titles.


## Title sources

https://en.wikipedia.org/wiki/List_of_Kim_Jong-il%27s_titles

## How to create slack app

https://api.slack.com/start/overview

https://api.slack.com/start/planning

https://api.slack.com/slash-commands

https://docs.aws.amazon.com/toolkit-for-eclipse/v1/user-guide/lambda-tutorial.html

https://github.com/aws-samples/lambda-kotlin-groovy-example

https://git.forge.lmig.com/projects/GUADE/repos/diomedes-bot/browse

## Example Slack Apps

Shuttle List: https://lmbnewtech.slack.com/apps/A9Z3847EV-shuffle-list?next_id=0
Usage:
/shuffle word1 word2 word3 word4

CloudForge Console: https://console.forge.lmig.com/artifact/e64786d7-3db8-4323-92e3-9e8f530a0052

## Creating AWS Lambda

* https://docs.aws.amazon.com/cloud9/latest/user-guide/lambda-functions.html?icmpid=docs_ac9_console_or_ide#lambda-functions-prepare
