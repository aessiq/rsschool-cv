# CV: Ruslan Omarov
### Contacts
* Email: noriod@yandex.ru - preferred
* Telegram: @aessiq
* Phone: +7 906 255 77 88
### Summary
Back at school I liked programming (in Pascal, but it was interesting to solve problems), I really wanted to make my own website, bought a book and studied HTML, I wanted to enter a university to study computer science, but somewhere I turned the wrong way and it ended up graduating as a civil servant. I started working, but not in my specialty (*he-he, classic*), even managed to work at McDonald's (memes were right), and accidentally came across an advertisement for the free part of programming courses. I decided to try it and I really liked it. I did not buy the course, but I myself studied HTML/CSS at [W33 School](https://www.w3schools.com/) in about a month, made up the first website and started learning JavaScript at https://learn.javascript.ru/. While I was learning JS, I decided to try to submit my CV somewhere near IT and I was lucky - I got a job as a Customer Support Engineer at Saber Interactive. The new job distracted me a little from my studies, but now I took it up again and my colleague just suggested your courses to me, so I decided to try it. 
### Skills
* HTML
* CSS
* Basic Javascript
* Git and Github
* English B2
* Photoshop/Figma
* 2k+ arena rating in WoW
### Code examples
```
function isValidIP(str) {
  let arr = str.split('.');
  for (let i = 0; i < arr.length; i++) {
    if ( isNaN(+arr[i] ) ) return false;
    if (arr[i] < 0 || arr[i] > 255) return false;
    if (arr[i].length > 1 & (arr[i])[0] == 0) return false; 
    for (let j = 0; j < arr[i].length; j++) {
      if ( arr[i].codePointAt(j) < '0'.codePointAt(0) || arr[i].codePointAt(j) > '9'.codePointAt(0) ) return false;
    }  
    if (arr.length != 4 || arr[i].length == 0) return false;
  }
  return true;
}
```
### Experience
* After I learned HTML/CSS, I chose a PSD template and made a website based on it. The site itself is available via the link: https://aessiq.github.io/wooder/, and its source code is [here](https://github.com/aessiq/aessiq.github.io/tree/master/wooder).
* I also like solving katas at Codewars, my profile is available [here](https://www.codewars.com/users/aessiq).
### Education
* North-West Institute of Management of Presidential Academy of National Economy and Public Administration (NWIM RANEPA), Public and municipal administration, Bachelor, 2017.
* [W33 School (HTML/CSS)](https://www.w3schools.com/)
* [Learn.javascript.ru](https://learn.javascript.ru/)
* [Codewars](https://www.codewars.com/users/aessiq)
* [Freecodecamp](https://www.freecodecamp.org/aessiq)
* Udemy courses: [web developer](https://www.udemy.com/course/webdeveloper/) and [Javascript + React](https://www.udemy.com/course/javascript_full/)
### English
My level is B2, at the moment I work in support, where 95% of requests are in English. My writing and listening skills are good, but my speaking skills need some practice.
