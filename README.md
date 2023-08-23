# text_adventure

Create a [text-based adventure game](https://en.wikipedia.org/wiki/Text-based_game#Text_adventure). You can find inspiration [here](https://textadventures.co.uk/).

The goal of the project is to practice the very basics of programming:
- variable creation and using (`let`, `const`)
- primitive types (`number`, `string`, `boolean`)
- simple control structures (`if`, `else`, `else if`, maybe `switch`)

## How to setup

1. Download the files and save them into a folder
2. Open the folder in VSCode (File->Open Folder...)
3. Open the integrated terminal (Terminal->New Terminal - the Terminal menu can be hidden under `...` if the window is too narrow)
4. Install dependencies (type the following command into the terminal)  
   `npm install`
5. Open `main.js` (click on it in the Explorer)
6. Code :)  
   Don't remove the first two lines of the `main.js`. This code is responsible for allowing `prompt`. You can use input from the user with the following command:  
   `const answer = prompt('Please, give me a number between 1 and 10: ');`  
   This line will block the execution until the user types their answer and presses ENTER. After that, the variable `answer` will contain the inputted text _as a string_. (Even if we requested a number. You should convert the value into other types if necessary.)
