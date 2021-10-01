# number-prettier 
Pretty a number and shortened it to make it look more pretty and simple.

## Number Commas 🌠
```js
const { commas } = require('number-prettier')
commas(1000000) // 1,000,000
```

## Number Formatting 📲
```js
const { format } = require('number-prettier')
format(1000, 2) // 1k
```
## Available Values
```json
{
"k": "thousands",
"M": "millions",
"B": "billions",
"T": "trillions",
"Q": "quadrillions",
"QT": "quintillions"
}
```
### Note
```
You can add more values by accessing the index.js file from the package file , and added the values on your own!
Below are the list of the scientifc notations for the values! Thank you 😄
```
# https://clickerheroes.fandom.com/wiki/Units

