## TEST
#### test `hw`
export the function `hw` that returns the string `'Hello, World!'`

#### test `isNumber`
export the function `isNumber` that should return true if the given value is
a number

#### test `isString`
export the function `isString` that should return true if the given value is
a string

#### test `capitalize`
export the function `capitalize` that should [capitalize](http://www.grammarbook.com/punctuation/capital.asp) a word

#### test `isWhiteSpace`
export the function `isWhiteSpace` that takes one character and tell if it's a 
white space.

#### test `repeat`
export the function `repeat` that should work just like
[`String.prototype.repeat`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/repeat)
except it should not be a method but be given the string as first arguments

```js
// Wrinting Methods as normal functions
'pouet'.repeat(5)

// should be called like so :
repeat('pouet', 5)

// so they all need one more argument, the first (the base string in this case)
```

#### test `reverse`
export the function `reverse` that takes a string and return it's reversed
value.
```js
// Such as:
reverse('abc') // => 'cba'
```

#### test `match`
export the function `match` that takes 3 arguments a string, a substring and
an index and return `true` or `false` if the substring was found from the given
index in the given string.

#### test `indexOf`
export the function `indexOf` that should work just like
[`String.prototype.indexOf`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/indexOf)
except it should not be a method but be given the string as first arguments

#### test `includes`
export the function `includes` that should work just like
[`String.prototype.includes`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/includes)
except it should not be a method but be given the string as first arguments

#### test `padStart`
export the function `padStart` that should work just like
[`String.prototype.padStart`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padStart)
except it should not be a method but be given the string as first arguments

#### test `replace`
export the function `replace` that should work just like
[`String.prototype.replace`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replace)
except it should not be a method but be given the string as first arguments
and not handle `RegExp`.

#### test `slice`
export the function `slice` that should work just like
[`String.prototype.slice`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/slice)
except it should not be a method but be given the string as first arguments

#### test `trim`
export the function `trim` that should work just like
[`String.prototype.trim`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/trim)
except it should not be a method but be given the string as first arguments

#### test `before`
export the function `before` that take strings arguements and return the value
the part of the first string before the second string.

#### test `after`
export the function `after` that work like `before`, but `after`.

#### test `replaceAll`
export the function `replaceAll` that should work just like replace but for all
occurences of the string.

#### test `padEnd`
export the function `padEnd` that should work just like
[`String.prototype.padEnd`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/padEnd)
except it should not be a method but be given the string as first arguments

#### test `lastIndexOf`
export the function `lastIndexOf` that should work just like
[`String.prototype.lastIndexOf`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/lastIndexOf)
except it should not be a method but be given the string as first arguments
