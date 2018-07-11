# Who Wants to Be a Millionaire

Who Wants To Be A Millionaire is a trivia game in which contestants are given a series of trivia questions, with the level of the question's difficulty increasing with each question. Each question is assigned a dollar value amounting to the total value of the player's winnings if they get that particular question correct. The 15th question has the value of $1,000,000, hence the name of the game.


## Gameplay

There are 15 questions per game. The value of each question is as follows:

1. $100
2. $200
3. $300
4. $500
5. $1,000
6. $2,000
7. $4,000
8. $8,000
9. $16,000
10. $32,000
11. $64,000
12. $125,000
13. $250,000
14. $500,000
15. $1,000,000

Each question is presented in multiple choice format. The player has 4 options to choose from. The player's purse if is worth the value of their most recently correctly answered question. 

Questions are separated into three tiers of five questions (1-5, 6-10, 11-15). If a player answers the last question in a tier (5, 10 or 15), they are guaranteed that value, even if they get a question in the next tier wrong. For example, if a contestant correctly answers questions 1-6, but gets question 7 wrong, they will still walk away with the highest value of tier 1, which is $1,000. Similarly, if they answer questions 1-12 correctly answer question 13 incorrectly, they will walk away with $32,000.

The player may choose to walk away with the value in their purse instead of answering a question. This decision would be made after the question is read but before they attempt an answer. If this is the case, their winnings are the value in their purse, which is the value of the last question they answered correctly.

## The Application

Given a set of questions provided in this repo, set up the game with multiple choice questions to present to the player. Keep track of the value that the player earns by answering the questions correctly. Calculate the value that the player will walk away with if they answer a question incorrectly.

## Stretch

### Timer
Include a timer to provide a maximum amount of time the player has to answer a particular question. Tier 1 questions should have a 15 second timer. Tier 2 questions should have 30 seconds. Tier 3 questions are given 45 seconds.

### Lifelines
Lifelines are helpful utilities available for the player to use during the game. There are three lifelines and each can only be used once per game.

- **50/50**: Eliminate two random incorrect answers from the 4 options

- **Ask the audience**: There is no audience in the app version of the game, but the internet can be your audience. Try interacting with Google or another service to return a response to help the player answer the question. For example, with answers.com, you can add the question to the url, like so: http://qa.answers.com/Q/what_is_the_square_root_of_4. Use the web crawling skills you learned last week to pull the answer from the body text:
```html
<div class="answer_text js--ad-injector-root">The two square roots are -2 and +2.</div>
```

- **Phone a friend**: In the gameshow, the contestant literally made a phone call to someone. You can implement literal calling/messaging functionality, or this could mean asking someone sitting around you. However you want to implement this is up to you.
