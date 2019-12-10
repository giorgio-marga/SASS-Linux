## Compile SCSS into CSS automatically on Linux

* download Node.js
* cd to project folder
* 'npm init' and go through the questions --> creates package.json file
* install Node-Sass with 'npm install node-sass'
* open the json file in an editor
  *  in the script section after the test command add 
  > "scss": "node-sass --watch scss -o css"
  *  in the syntax where you see 'scss' it is the folder name where we put
    all our .scss files just customize your path
  * where 'css' is in the syntax it is the path where the css output will be generated
6. with 'npm run scss' you run the script
