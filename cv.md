#Yana Lesina
Junior Frontend Developer
-------------------------------------------------------------------------
##Contacts:
E-mail: yanalesina3@gmail.com
Telegram: @yanalesina
-------------------------------------------------------------------------
###About myself
I’m a 3rd year student of a specialty related to management and IT. Also I finished JavaScript courses and tried myself in teamwork on a student project to create a website. During my studies and self-learning I managed to work with HTML/CSS, JS, Webpack, Browserify, Git & Github, Trello, Scrum methodology. Good communication skills.
-------------------------------------------------------------------------
##Skills:
*HTML/CSS(intermediate)
*JavaScript(intermediate)
*React(novice)
*C++(novice)
*Figma(intermediate)
*Webpack(novice)
*Browserify(novice)
Development Environment: VS Code, Atom
OS: Windows10
-------------------------------------------------------------------------
##Code example
####Convert string to camel case (picked from Codewars)
Complete the method/function so that it converts dash/underscore delimited words into camel casing. The first word within the output should be capitalized only if the original word was capitalized (known as Upper Camel Case, also often referred to as Pascal case).
#####Examples: 
"the-stealth-warrior" gets converted to "theStealthWarrior"
"The_Stealth_Warrior" gets converted to "TheStealthWarrior"
#####My Solution
```
function toCamelCase(str){
  if (str.includes('_')) return str.replace(/\_[a-zA-Z]/g, w => w[1].toUpperCase())
  return str.replace(/\-[a-zA-Z]/g, w => w[1].toUpperCase());
}
```
