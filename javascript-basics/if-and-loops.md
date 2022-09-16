# Javascript alapok

## Tananyag

- [If statement](https://www.youtube.com/watch?v=Br7ekaB9hZI&list=PLj6t-9MtkMFklRHPJfGxGMCM_zApkMSng&index=5)
- [Loops](https://www.youtube.com/watch?v=n4vq0I_hd9o&list=PLj6t-9MtkMFklRHPJfGxGMCM_zApkMSng&index=6)
- [Opcionális ismétlés - CSAK a feltételek és a ciklusok szekció](https://www.youtube.com/watch?v=pGFPysXqgNw)

## Tananyag összefoglalás

- `if`
- `while`
- `for`
- `break`
- `continue`

### Conditionals

```javascript


const a = 13;

if (a === 13) {
  console.log('Yaaay! The value of the \'a\' variable is 13'); // This block will run
}

if (a === 8) {
  console.log('Yaaay! The value of the \'a\' variable is 8'); // This block will NOT run
}


const b = 20;

if (b < 10) {
  console.log('Yaaay! The value of the \'b\' variable is lower than 10') // This block will NOT run
} else {
  console.log('Yaaay! The value of the \'b\' variable is higher than 10') // This block will run
}


const c = 15;

if (c < 10) {
  console.log('Yaaay! The value of the \'b\' variable is lower than 10'); // This block will NOT run
} else if (c < 20) {
  console.log('Yaaay! The value of the \'b\' variable is higher than 10'); // This block will run
} else {
  console.log('Yaaay! The value of the \'b\' variable is higher than 10'); // This block will NOT run
}


const thirsty = true;
const hungry = false;

if (thirsty && hungry) {
  console.log('Lunch time!');
} else if (thirsty || hungry) {
  console.log('Snack time!');
} else {
  console.log('No food for you.');
}
```

#### Exercises

- [conditional-variable-mutation](conditional-variable-mutation/conditional-variable-mutation.js)

### Loops

```javascript


let a = 0;
while (a < 10) {
  console.log(a); // Prints the numbers from 0 to 9
  a++;
}

for (let i = 0; i < 100; i++) {
  console.log(i); // Prints the numbers from 0 to 99
}
```

#### Exercises

- [i-wont-cheat-on-the-exams](i-wont-cheat-on-the-exams/i-wont-cheat-on-the-exams.js)
- [print-even](print-even/print-even.js)
- [multiplication-table](multiplication-table/multiplication-table.js)
- [fizz-buzz](fizz-buzz/fizz-buzz.js)
- [draw-triangle](draw-triangle/draw-triangle.js)
- [draw-pyramid 💪](draw-pyramid/draw-pyramid.js)
- [draw-diamond 💪](draw-diamond/draw-diamond.js)
- [draw-square 💪](draw-square/draw-square.js)
- [draw-diagonal](draw-diagonal/draw-diagonal.js)
- [ParametricAverage 💪](parametric-average/parametric_average.js)
- [draw-chess-table](draw-chess-table/draw-chess-table.js)
