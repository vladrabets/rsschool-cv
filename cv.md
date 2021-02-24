# Vladislav Rabets

## Contact information
**Phone:** +375(44)713-28-95  
**Email:** vladrabets@icloud.com  
**Discord:** vladrabets  
- - -

## Summary
My main goal is to become a Fullstack JavaScript Developer, with the help of this course I can get closer to this. I am responsible, persistent and hardworking.
- - -

## Skills
**Languages:** HTML, CSS, JS, SQL  
**Frameworks:** Node.js, Express.js  
**Technologies:** GIT, Docker  
**Software:** Visual Studio Code, Figma 
- - -

## Code example
~~~
// Checking for closed parentheses in a sequence
function check(str, bracketsConfig) {
  let flag = true;
    while(flag){
        flag=false;
      for(config of bracketsConfig){
          let brackets = config[0]+config[1];
          while(str.includes(brackets)){
                  str = str.slice(0,str.indexOf(brackets)) + str.slice(str.indexOf(brackets)+brackets.length);
                  flag=true;
          }
      }
  }
  if(str)
      return false;
  else
      return true;
}
~~~
- - -

## Courses 
1. [JavaScript Tutorial](https://learn.javascript.ru)
- - - 

## Education
### Belarusian State University (2019 - 2023)  
Mechanics and Mathematics faculty, Bachelor
- - -

## English 
**Level:** A2+
