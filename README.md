# Backend Developer Coding Challenge

Welcome to Buff.
As part of the recruitment process we want to know how you think, code and structure your work. In order to do that, we're going to ask you to complete this coding challenge. 

## Some background

We already explained to you the basic idea of Buff, which is to deliver questions and possible answers during a live stream.
You will need to create a solution that will deliver this "Buffs" to the iOS Client via an API

## What we expect

* Build a performant, clean and well structured solution;
* Commit early and often. We want to be able to check your progress;
* Feel free to address the problem creatively according to your programming tastes (there are always multiple ways to achieve the same goal) and try to use elegant solutions.

## The challenge

You are the architect in charge of creating the API do display the "Buffs" to the iOS client
Consider that users are already logged in via Social Login (Google, Twitter, or FB)

* You should create a very simple web dashboard (for a content creator) that has these options
    * A question input text, where the question to be shown to the users will be entered
    * 4 input boxes for possible answers to the question (the content creator will need to enter at least 2 and up to 4 answers)
    * A timer dropdown to select when to show this "Buff" (Immediately, after 5 seconds, after 1 min and up to 5 minutes, with 30 second intervals)
    * A submit button to submit this Buff

* The API should be responsible to notify the iOS client that a Buff needs to be displayed
	* You are free of selecting the way you wish to handle this communication (i.e. use WebSockets, MQTT, APNS, etc)
    * The "Buff" question data should be delivered in JSON format

* There should be also an API endpoint to collect the users answers and deliver results 10 seconds after the "Buff" was pushed to the client
	* The Results should be in JSON format and should include the answers and the percentage each answer received

### Your task:

1. Fork this repo.
2. Produce a fully functional API in any programming language you prefer and any DB you wish that fulfils these requirements and has scalability in mind
3. Make the API public, deploy it to your service of choice (e.g. AWS, Heroku, Digital Ocean...).
4. Create a readme file explaining your technical choices, and if you have them, your ideas and suggestions.
5. Send us a PR!

You have one week!
GOOD LUCK!
