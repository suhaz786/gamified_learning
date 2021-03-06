# Gamified Learning
![Nodejs](https://img.shields.io/badge/-Nodejs-43853d?style=flat-square&logo=Node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github)

HTML5 E-Learning game on basis of Multiple Choice Questions. This game has 5 levels and 5 different topics. By playing the game the user will definely reach in nearby point of snake and ladder. At that time a question will be asked to the user. If he/she attempts question correctly then the tick will go up with the ladder. And if attempted incorret then snake will bite and the tick will fall to the snake's tail. What are you waiting for? Let's play!

## Browser Support
- IE 10+
- Chrome
- Safari
- Firefox


## Short Description
- 5 Different Level
- 5 Different Topic
- Pure client side


## Configure questions
Customize questions from `js/sl.config.js`. You can add many questions as you like on same level. Question will be opt from these range randomly.

```
{
    level: "1",
    theme: "greetings",
    question: "What is the arabic translation of - 'Good Morning ?",
    answers: ["مع السلامة", "صباح النور", "صباح الخير", "لو سمحت"],
    correct: 2,
}
```

##Screenshots

![Game screen](https://rx4hvn.github.io/snakes-and-ladders/img/game-2.jpg)
![Game screen](https://rx4hvn.github.io/snakes-and-ladders/img/game-1.jpg)