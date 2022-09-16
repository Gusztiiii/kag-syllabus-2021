# Javascript alapok

## Tananyag

- [Alapok](https://www.youtube.com/watch?v=RBiQOlM8HpQ&list=PLj6t-9MtkMFklRHPJfGxGMCM_zApkMSng&index=3)
- [Operátorok](https://www.youtube.com/watch?v=GABLMi7Bki4&list=PLj6t-9MtkMFklRHPJfGxGMCM_zApkMSng&index=4)
- [Opcionális ismétlés 30 percig](https://www.youtube.com/watch?v=pGFPysXqgNw)

## Tananyag összefoglalás

- Kommentek
- `console`
- Változók
  - `var`
  - `let`
  - `const`
- Típusok
  - number
  - string
  - boolean
  - null
  - undefined
- Operátorok
  - arithmetic
  - logical
  - comparison
  - assignment
  - `typeof`

## Feladatok

#### Hello World

```javascript
console.log('Hello world');
```

#### Exercises

- [hello-me](hello-me/hello-me.js)
- [humpty-dumpty](humpty-dumpty/humpty-dumpty.js)
- [hello-others](hello-others/hello-others.js)

### Comments

```javascript


// single line comment

/*
 multi line
 comment block
*/
```

### Típusok

```javascript

// Prints a string to the terminal window.
console.log('Hello, World!');

// Prints an integer to the terminal window.
console.log(42);

// Prints a floating point number to the terminal window.
console.log(3.141592);
```

```javascript
// Positive, negative and zero
console.log(42); // Prints 42
console.log(-1); // Prints -1
console.log(0); // Prints 0

console.log(12341234123412341234); // 12341234123412340000
// In JavaScript numbers are rounded over a limit
// The maximal number that is not rounded (the maximum safe integer) is: 9007199254740991
// The reasoning behind that number is that JavaScript uses double-precision floating-point format numbers
// Link: http://en.wikipedia.org/wiki/Double_precision_floating-point_format
```

```javascript
// Positive, negative and zero
console.log(3.1415); // Prints 3.1415
console.log(-1.5); // Prints -1.5
console.log(0.0); // Prints 0

// Leading and closing zero is not mandatory
console.log(.5) // Prints 0.5
console.log(5.) // Prints 5
```

#### Operátorok

```javascript
// Arithmetic operations
console.log(1 + 1); // Prints 2
console.log(5 - 2); // Prints 3
console.log(3 * 4); // Prints 12
console.log(6 / 2); // Prints 3
console.log(5 / 2); // Prints 2.5
console.log(5 % 2); // Prints 1
```

#### Boolean

```javascript
// true, false
console.log(true); // Prints true
console.log(false); // Prints false

// Boolean Operators
// Negation
console.log(!true); // Prints false
console.log(!false); // Prints true

// And
console.log(true && true); // Prints true
console.log(true && false); // Prints false
console.log(false && true); // Prints false
console.log(false && false); // Prints false

// Or
console.log(true || true); // Prints true
console.log(true || false); // Prints true
console.log(false || true); // Prints true
console.log(false || false); // Prints false
```

#### Szöveg

```javascript
// String and special characters
console.log('apple'); // Prints apple
console.log('don\'t'); // Prints don't
console.log('"Everything you can imagine is real." - Picasso'); // Prints "Everything you can imagine is real." - Picasso

// String Operators
// Concatenation
console.log('tooth' + 'brush'); // Prints toothbrush

// Concat string with number
console.log('My favorite number is: ' + 8); // Prints My favorite number is: 8
```

- [introduce-yourself](introduce-yourself/introduce-yourself.js)
- [two-numbers](two-numbers/two-numbers.js)
- [coding-hours](coding-hours/coding-hours.js)

### Változók

```javascript
// String
const welcome = 'Hello, World';
console.log(welcome);

// Boolean
const isAwesome = true;
console.log(isAwesome);

// Integer
const theMeaningOfLifeAndTheUniverseAndEverything = 42;
console.log(theMeaningOfLifeAndTheUniverseAndEverything);

// Floating point number
const pi = 3.141592;
console.log(pi);

// Assigning and creating a variable, (define its value)
let number = 12;

// Mutate a variable, (redefine its value)
number = 23;
```


```javascript
let a = 12;
a += 4;
console.log(a); // Prints 16

let b = 12;
b -= 4;
console.log(b); // Prints 8

let c = 12;
c *= 3;
console.log(c); // Prints 36

let d = 12;
d /= 3;
console.log(d); // Prints 4

let e = 12;
e %= 7;
console.log(e); // Prints 5

let f = 12;
f++;
console.log(f); // Prints 13

let g = 12;
g--;
console.log(g); // Prints 11

let h = 10;
console.log(h);   // Prints 10
console.log(h++); // Prints 10
console.log(h);   // Prints 11

let i = 10;
console.log(i);   // Prints 10
console.log(++i); // Prints 11
console.log(i);   // Prints 11
```

- [favorite-number](favorite-number/favorite-number.js)
- [swap](swap/swap.js)
- [bmi 💪](bmi/bmi.js)
- [define-basic-info](define-basic-info/define-basic-info.js)
- [variable-mutation](variable-mutation/variable-mutation.js)
- [cuboid 💪](cuboid/cuboid.js)
- [seconds-in-a-day](seconds-in-a-day/seconds-in-a-day.js)

### Nothings

```javascript


undefined;
null;
NaN;

null !== undefined;
NaN !== undefined;
null !== NaN;

null == undefined;

typeof undefined; // 'undefined'
typeof null;      // 'object'
typeof NaN;       // 'number'

let apple;
apple;        // undefined
apple + 1;    // NaN
apple = null; // null
```
