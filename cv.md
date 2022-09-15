# Illia Rodchenko  
## Contacts  
Phone number: +38 063 634 11 64  
Skype: sergey3948576  
Email: asadar34@gmail.com

## About me
I'm a student at IAPM on 2nd course, studying on Software Engineering. My goal is to finish the University and have working experience by graduation, so i could progress in learning Front-end while gaining benefit from my knowledge as soon as possible.

My last job was as content manager at Ensof Group company. There I was downloading lessons for online school for 1 year.

After the war started, applied as call-center operator to another company.

## Skills
HTML  
CSS, SASS  
JS - Beginner  
Git, GitHub  
C++ - Basic  
Photoshop

## Code Example
'Stop gninnipS My sdroW!' from codewars.com  
Write a function that takes in a string of one or more words, and returns the same string, but with all five or more letter words reversed (Just like the name of this Kata). Strings passed in will consist of only letters and spaces. Spaces will be included only when more than one word is present.

```function spinWords(string){
  if(string == 0) {
    return '';
  };
  let count;
  let buffer;
  string = string.split(" ");
  for (let i = 0; i < string.length; i++) {
    console.log(string[i]);
    string[i] = string[i].split("");
    count = string[i].length;
    if (string[i].length >= 5) {
      while (count > 0) {

        string[i].unshift(string[i][string[i].length - count]);
        count -= 1;
        console.log(string[i]);
      };
      for (j = string[i].length / 2; j > 0; j--) {
        string[i].pop();
        console.log(string[i]);
      };
    };
    while (string[i].length > 1) {
      string[i][0] += string[i][1];
      buffer = string[i].shift();
      string[i] = string[i].slice(1);
      string[i].unshift(buffer);
    };
  };
  if (string.length - 1) {
    for (i = string.length - 1; i > 0; i--) {
        string[0][0] += ' ' + string[1];
        buffer = string.shift();
        string = string.slice(1);
        string.unshift(buffer);
        console.log(string);
      };
    };
  return string[0][0];
};```
## Completed Projects
CV for rsschool course https://github.com/Wuattt/rsschool-cv/tree/main

## Education
Kyiv Gymnasium of Oriental languages №1  
Lexicogrammatical english course in local school  
IAPM - 2nd course on Software Engineering   
Codecademy - HTML, CSS, JS course (finished)  
freecodecamp - JS course (in progress)  
RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)  

## Languages
English - Intermediate (B1)  
Ukrainian - Native  
Russian - Fluent  
Japanese - Basic  
