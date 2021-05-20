# RoboAdvisor
---
The below code utilises Amazon Web Services and Amazon Lex to create a bot that can recommend an investment portfolio for a retirement plan.  

Our bot was created by the following steps:
1. **Initial Robo Advisor Configuration** - Define an Amazon Lex bot with a single intent that establishes a conversation about the requirements to suggest an investment portfolio for retirement.

2. **Build and Test the Robo Advisor** - Make sure that your bot is working and responding accurately along with the conversation with the user, by building and testing it.

3. **Enhance the Robo Advisor with an Amazon Lambda Function** - Create an Amazon Lambda function that validates the user's input and returns the investment portfolio recommendation. This task includes testing the Amazon Lambda function and making the integration with the bot.

## Features
---
Our bot has the following features:
1. **Personalised customer service** - Able to take user input, name and age, to provide a more personalised experience for the user
2. **Tailored investment portfolio recommendation** - Respond with investment recommendation dependent on user's appetite for risk level
3. **Instand validation framework** - Enhanced with Amazon Lambda to be able to validate user input

## Conditions
---
Our bot service requires:
1. User to be under the age of 65
2. Initial investment amount of at least $5000