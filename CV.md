# rsschool-cv

### 1.Abbos Amritdinov
![My photo]()
  

### 2.Contact Info:
  * E-mail: abbos6264258@gmail.com
  * Phone: +998 (94) 6264258
  * Telegram: [@rON2_webdev](http://t.me/rON2_webdev)

### 3.Summary:
  Passionate about programming, hope to work on interactive apps and web-program implementation. Ambitious and a quick learner.

### 4.Skills:
  * HTML
  * CSS
  * SASS
  * Bootstrap
  * JavaScript
  * VSCode
  * GIT
  * WebPack
  * EsLint

### 5.Code examples: 
```JS
import data from './data/cards'; // Данные
import menu from './menu' // Боковое меню
import cards from './cards'

function mainPage() { // Отрисовка главной страницы с категориями
  const container = document.querySelector('.container.main-container');
  data[0].forEach((element, index) => {
    const a = document.createElement('a');
    a.className = 'main-card green';
    a.onclick = () => { localStorage.setItem('page', index); };
    a.innerHTML = `${element}`;
    a.href = './cards.html';
    container.append(a);
    const img = document.createElement('img');
    img.src = `./data/${data[index + 1][0].image}`;
    a.prepend(img);
  });
}import data from './data/cards'; // Данные
import menu from './menu' // Боковое меню
import cards from './cards'

function mainPage() { // Отрисовка главной страницы с категориями
  const container = document.querySelector('.container.main-container');
  data[0].forEach((element, index) => {
    const a = document.createElement('a');
    a.className = 'main-card green';
    a.onclick = () => { localStorage.setItem('page', index); };
    a.innerHTML = `${element}`;
    a.href = './cards.html';
    container.append(a);
    const img = document.createElement('img');
    img.src = `./data/${data[index + 1][0].image}`;
    a.prepend(img);
  });
}
```

### 6.Experience:
 Completed a 6-month-long web-devepment course at CodeClass Coding School in Tashkent. Have completed online courses at HTMLacademy and created a wordpress site as a freelance project.
 At this moment attending [Rolling Scopes School](http://rs.school)
 

### 7.Education:

- [Rolling Scopes School](http://rs.school)
- CodeClass school of Programming
- HTML Academy (HTML/CSS)
- 42-public school 

### 8.English:
 Intermidiate level - Wise Training Centre
 
### 9.Projects:
[Virtual Keyboard](http://abbos-ron2.github.io/virtual-keyboard)
[Gem Puzzle](http://abbos-ron2.github.io/gem-puzzle)
[Singolo](https://abbos-ron2.github.io/singolo)
[English for Kids](https://abbos-ron2.github.io/english/)

### 10. Reference:
Munira Begmuratova 
Mentor at Rolling Scopes School
+46 76786 5557






