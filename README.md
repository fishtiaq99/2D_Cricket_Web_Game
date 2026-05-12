# 2D Cricket Web Game

A probability-based 2D cricket batting game developed using React, JavaScript, HTML, and CSS.

## Features

- 2D cricket ground interface
- Aggressive and Defensive batting modes
- Probability-based power bar system
- Moving slider for shot timing
- Bowling and batting animations
- Dynamic scoreboard updates
- Match progression with overs and wickets
- Restart game functionality
- Commentary system

## Technologies Used

- React
- JavaScript
- HTML5
- CSS3

## Game Rules

- Total Overs: 2
- Total Balls: 12
- Total Wickets: 2

Each shot outcome depends on the slider position on the probability power bar.

## Probability System

Different batting styles use different probability distributions:

### Aggressive Mode
- Higher chance of boundaries
- Higher wicket probability

### Defensive Mode
- Lower wicket probability
- Safer scoring options

The power bar visually maps probabilities into segments.  
The slider position at the moment of clicking determines the result.

## How to Run

```bash
npm install
npm start
