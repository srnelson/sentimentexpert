# sentimentexpert
Alexa skill to use Expert.ai sentiment analysis in an interactive challenge

This repository contains the node.js code for a Lambda backend and a json interaction model that can be used to create Sentiment Expert, an interactive excercise challenging the user to match sentiment targets by speaking sentences which Expert.ai will analyze and score.

The skill may be implemented by using the ask-sdk cli, or with the Lambda and Alexa consoles.

Note that the backend code makes use of three environment variables: Expert.ai username and password, and an s3 bucket where hiScores are kept.
