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
  * jQuery
  * WordPress
  * VSCode
  * GIT

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
 Completed a 6-month long web-devepment course at CodeClass coding school in Tashkent. Have completed online courses at HTMLacademy and created a wordpress site as a freelance project.
 At this moment attending to [Roling Scope School](http://rs.school)
 

### 7.Education:
 Currently attending 42-school as a 10-th grade student.

### 8.English:
 Currently studying at intermidiate level. 
 
### 9.Projects:
[Virtual Keyboard](http://abbos-ron2.github.io/virtual-keyboard)
[Gem Puzzle](http://abbos-ron2.github.io/gem-puzzle)
[Singolo](https://abbos-ron2.github.io/singolo)
[English for Kids](https://abbos-ron2.github.io/english/)






