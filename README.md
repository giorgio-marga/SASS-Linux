
# Guide to compile SCSS into CSS automatically on Linux Ubuntu / Mint

## by using the Terminal

1. open your Terminal
2. download Node.js
3. cd to project folder
4. '$ npm init' then go through the questions --> creates a package.json file
5. install Node-Sass with '$ npm install node-sass'
6. open the json file with your prefered editor
  1. inside the script section right after the test command add this:
  > "scss": "node-sass --watch scss -o css"
  2. syntax: where you see the second 'scss' it is the folders name, where you have put all your .scss files
  3. where you see the 'css' in the syntax it is the path where the css output will be generated
7. with '$ npm run scss' you run the script
