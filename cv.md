![Аватар](https://github.com/markot-1/resources/blob/main/1.jpg?raw=true)
# Marina Kotova

## Contact information: 
+ **E-mail:** [m.klementyeva@mail.ru](mailto:m.klementyeva@mail.ru)
+ **Phone:** \+382 68 791 339
+ **Discord:** mar-kot#3243
+ [LinkedIn](https://www.linkedin.com/in/marina-kotova-49ab65199/) | [Telegram]( https://t.me/mar_kotova) | [GitHub]( https://github.com/markot-1) 

*****

## General information
I’m hardworking and responsible person. My key strengths are perseverance, ability to work in multitasking mode, deep interest in new knowledge and a strong desire to become a professional in new field.

I have 4 years of experience in implementing various projects in international teams (from 5 to 30 people). I believe that this experience will be beneficial to my future projects related to web development.

*****

## Skills 

+ HTML
+ CSS 
+ JavaScript 
+ TypeScript 
+ Git/GitHub

*****

## Code examples

Solution for “Adding values of arrays in a shifted way” kata from [CodeWars](https://www.codewars.com/kata/57c7231c484cf9e6ac000090): 
```
function addingShifted(arrayOfArrays, shift) {
    let currentArr = [...arrayOfArrays[0]];
    let innerShift = shift;

    for (let i = 1; i < arrayOfArrays.length; i++) {
        let nextArr = arrayOfArrays[i];

        for (let index = 0; index < nextArr.length; index++) {
            let elemFromNextArr = nextArr[index];
            let elemFromCurrentArr = currentArr[index + innerShift];
            if (elemFromCurrentArr !== undefined) {
                currentArr[index + innerShift] = elemFromCurrentArr + elemFromNextArr;
            } else {
                currentArr.push(elemFromNextArr);
            }
        }
        innerShift += shift;
    }
    return currentArr;
}
```
*****
## Education

+ Saint Petersburg State University of Economics (UNECON). Faculty: Management, specialization: International business;
+ Europa-Universität Viadrina Frankfurt (Oder), Germany. Faculty of Business Administration and Economics (Summer semester);
+ Ural State University of Economics (USUE). Faculty: Management; specialization: International management

*****

## Courses

+ Code-basics: TypeScript Basics
+ Hexlet: JavaScript Basics
+ Udemy: Intensive immersion in JavaScript
+ IT Fundamentals (EPAM) (86% completed)
+ Skyeng: Business English 

*****

## Languages

+ Russian – native
+ English – upper-intermediate (B2)
+ German – elementary (A2)
