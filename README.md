# Totally Fair RNG!

A 100% fair random number generator, every day of the year!

## Installation

```sh
npm add totally-fair-rng
yarn add totally-fair-rng
```

## Usage

```js
const rng = require('totally-fair-rng')

if (rng.bool()) {
    console.log('Heads!')
} else {
    console.log('Tails!')
}

console.log('cash on hand: ' + rng.number(3.50, 10))
```

## Uninstallation

```sh
npm remove totally-fair-rng
yarn remove totally-fair-rng
```
