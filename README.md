# Testing @ Linode

Hello Linode candidate! We are constantly looking for the best candidates, and we have found that, for QA related roles, the usual technical aptitude tests are not indicative of a candidate's success in the role. Instead, we've come up with a small project that will allow you to more freely demonstrate your abilities as a test engineer!

# The Challenge

Weather -- it's all the rage these days. Kids, teenagers, adults and even old folks are finding themselves checking it out. At Linode we've discovered that, occassionally,
weather (RESTful) services aren't entirely accurate. We think they are in dire need of TESTING!

# Instructions 

* In a programming language of your choice, implement a test framework with a spec that tests the below test cases for the Dark Sky API. The API documentation is found [here](https://darksky.net/dev/docs). (*Note*: You will need to [register](https://darksky.net/dev/register) first in order to receive an API Key). 

* Do not spend more than 2 hours on this challenge, and do not publish it to public Github.

* Please provide a script/dockerfile or written instructions on how to run your test suite.

* When you have completed the challenge, Submit your project in a zip file attachment to kwilson@linode.com. 

## Test Case 1:

* Test that a Forecast request returns the expected fields

## Test Case 2:

* Test that the temperature is returned in celcius. 

## Test Case 3

* Test that a Time machine request three days in the past returns the expected fields

## Test Case 4

* Test that the Response Time for a forecast request is less than 750ms

## Test Case 5

* Think about how you might test forecast request errors and create a test accordingly.
