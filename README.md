# Many Notes Theory
[Link to Application](https://many-notes-theory.web.app/)

## Description
Many Notes Theory is an application to jot down multiple notes. Users can save their notes for future use.
## Technologies
- JavaScript
- Firebase

## How It Works
When the user jots down a note and click 'create,' the program makes several HTML elements including a textarea. The user can also save their work which takes the content of each "card" and store it as a string in local storage which uses a key-pair method of storage. A general overview of how saving works is that it gets an array of elements matching a certain class name. This array represents all the content and value that the users have written on the web application. This prototype array is then sliced and pushed into local storage. Loading is slightly more complicated. When the user access the web application, it checks to see if local storage contains anything. If it does, it takes whatever is in local storage and stores it in the cards variable. A for each loop is executed where every element of cards initiates the creation of certain HTML elements and the value of the card is stored in it.

## Challenges and Unique Elements
It has been quite a while since I touched this project. From what I recall, the most difficult part of this project was figuring out how saving/loading works. 

## Conclusion and Future Plans
All in all, this was one of my earliest projects. I still occasionally use it to quickly jot down things I need to remember. I do not foresee myself building on this app. There are plenty of alternatives for a "notes" application. What I felt was unique about my application was that it allowed users to see multiple notes on the screen at the same time instead of having to scroll through multiple pages or clicking through buttons to get to what they want.