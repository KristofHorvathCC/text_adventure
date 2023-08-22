# text_adventure

Create a text-based adventure game. You can find inspiration [here](https://textadventures.co.uk/).

The goal of the project is to practice the very basics of programming:
- variable creation and using (`let`, `const`)
- primitive types (`number`, `string`, `boolean`)
- simple control structures (`if`, `else`, `else if`, maybe `switch`)

## How to setup

1. Clone the repository to your computer (don't forget to navigate into the desirable parent directory with `cd` command before that).  
   `git clone URL_OF_THIS_REPO`
2. Navigate into the created folder  
   `cd text_adventure`
3. Install dependencies  
   `npm install`
4. Code :)  
   Don't remove the first line of the `main.js`. This code is responsible for allowing `prompt`. You can use input from the user with the following command:  
   `let answer = prompt('Please, give me a number between 1 and 10: ');`  
   This line will block the execution until the user types their answer and presses ENTER. After that, the variable `answer` will contain the inputted text _as a string_. (Even if we requested a number. You should convert the value into other types if necessary.)
