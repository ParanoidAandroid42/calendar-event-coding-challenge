# Daily Calendar Code Challenge 

This project implements a function to render events on a single day calendar, similar to popular calendar applications like Outlook, Calendar.app, and Google Calendar. The function ensures no events overlap visually and calculates the maximum possible width for colliding events without breaking layout invariants.

## Requirements

- Renders events in a single day calendar view.
- Ensures no events visually overlap.
- Colliding events have the same maximum possible width.
- Events are represented by JavaScript objects with `start` and `end` attributes (minutes since 9am).
- The container is 620px wide and 720px long (9am to 9pm).
- Language must be javascript

## Function

The main function provided by this project is `layOutDay(events)`.

### Usage

The `layOutDay` function takes an array of events and lays them out according to the described rules. Here is an example input:

   <pre>
     layOutDay([
        { id: 1, start: 0, end: 30 },
        { id: 2, start: 30, end: 100 },
        { id: 3, start: 80, end: 160 },
        { id: 4, start: 110, end: 240 },
        { id: 5, start: 110, end: 180 },
        { id: 6, start: 170, end: 230 },
        { id: 7, start: 170, end: 240 },
        { id: 8, start: 170, end: 220 },
        { id: 9, start: 190, end: 260 },
        { id: 10, start: 230, end: 300 },
        { id: 11, start: 240, end: 280 },
        { id: 12, start: 250, end: 290 },
        { id: 13, start: 300, end: 330 },
        { id: 14, start: 330, end: 400 },
        { id: 15, start: 330, end: 390 },
        { id: 16, start: 330, end: 380 },
        { id: 17, start: 400, end: 500 },
        { id: 18, start: 400, end: 620 },
        { id: 19, start: 600, end: 650 },
        { id: 20, start: 660, end: 720 },
        { id: 21, start: 670, end: 720 },
        { id: 22, start: 680, end: 720 },
        { id: 23, start: 690, end: 720 },
        { id: 24, start: 650, end: 680 },
        { id: 25, start: 650, end: 690 },
      ];);
    </pre>

## Preview
<img width="536" alt="image" src="https://github.com/ParanoidAandroid42/Calendar-Event-Coding-Challenge/assets/13114945/8debf4c8-b4d8-44c4-9ee7-f6d3b015e7af">


## Project setup

`npm i`

## Project run
`npm run dev`
