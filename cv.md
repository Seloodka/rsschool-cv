# Nikita Tikhonov

![Profile avatar image.](https://avatars.githubusercontent.com/u/85653195?v=4&size=64)

## Contacts

- Location: [Moscow, Russia](https://maps.app.goo.gl/MpAqM9YdRTGTmLKX7)
- Phone: +8 999 999 99 99
- Email: seloodka@gmail.com
- Github: [Seloodka](https://github.com/Seloodka)
- Discord: @seloodka_40121

## About me

Intern JavaScript Developer. Actively developing my knowledge and skills in web development. Currently studying JavaScript and related technologies. Throughout my learning process, I focus on applying the knowledge I gain in practice and use various techniques to develop a deeper understanding and better retention of the material.

## Skills

### Technologies

- HTML
- CSS/SASS
- JavaScript (Basic)
- Git

### Development instruments

- VS Code
- Figma
- Generative AI
- DevTools
- Pixel-Perfect layout
- Responsive layout

## Code snippets

```
function createBalance (amount) {
  let balance = amount;

  return function deductFromBalance (spend) {
    if (balance <= 0 || spend > balance) {
      throw new Error('Деньги кончились')
    }
    if(spend === undefined) {
      return balance;
    }
    balance -= spend;

    return deductFromBalance;
  };
};

let wallet = createBalance(5000);

wallet(10)(10)(5)(0)() // spend money from balance
```

## Experience

- ### [Christmas Shop](https://seloodka.github.io/Christmas-Shop/)
  - Adaptive layout, basic JS, import data from JSON.
  - [Source code](https://github.com/Seloodka/Christmas-Shop/tree/christmas-shop-part3)
