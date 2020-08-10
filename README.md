# SnipJS 

## A collection of common javascript statement snippets for faster development in [Visual Studio Code](https://code.visualstudio.com/).

### Feel free to install the extension from VS Code or from [here](https://marketplace.visualstudio.com/items?itemName=ddyakov.snipjs).

### See the [demo](#demo).

***

* [Assignments](#assignments)
* [Functions](#functions)
* [Conditions](#conditions)
* [Validations](#validations)
* [DOM manipulations](#dom-manipulations)
* [Console](#console)
* [Destructuring](#destructuring)
* [Others](#others)

***

## Assignments

#### `la =>` let assignment

```js
let ${1:name} = ${2:value}
```

#### `va =>` var assignment

```js
var ${1:name} = ${2:value}
```

#### `ca =>` const assignment

```js
const ${1:name} = ${2:value}
```

#### `aa =>` array assignment

```js
let ${1:name} = [${2:value1}, ${3:value2}]
```

#### `oa =>` object assignment

```js
 let ${1:name} = {
     "${2:key}": ${3:value}
 }
```

***

## Functions

#### `af =>` arrow function

```js
const ${1:name} = (${2:param}) => {

}
```

#### `nf =>` named function

```js
function ${1:name} (${2:param}) {

}
```

***

## Conditions

#### `ec =>` equal condition

```js
${1:value1} === ${2:value2}
```

#### `nec =>` not equal condition

```js
${1:value1} !== ${2:value2}
```

#### `gtc =>` greater than condition

```js
${1:value1} > ${2:value2}
```

#### `ltc =>` less than condition

```js
${1:value1} < ${2:value2}
```

#### `getc =>` greater equal than condition

```js
${1:value1} >= ${2:value2}
```

#### `letc =>` less equal than condition

```js
${1:value1} <= ${2:value2}
```

#### `oc =>` or condition

```js
${1:condition1} || ${2:condition2}
```

#### `ac =>` and condition

```js
${1:condition1} && ${2:condition2}
```

#### `co =>` condition operator

```js
let ${1:name} = ${2:condition} ? ${3:value1} : ${4:value2}
```

***

## Validations

#### `zlv =>` zero length validation

```js
${1:value}.length === 0
```

#### `plv =>` positive length validation

```js
${1:value}.length > 0
```

#### `esv =>` empty string validation

```js
${1:value} === ""
```

#### `nesv =>` not empty string validation

```js
${1:value} !== ""
```

#### `nv =>` null validation

```js
${1:value} === null
```

#### `nnv =>` not null validation

```js
${1:value} !== null
```

#### `uv =>` undefined validation

```js
typeof ${1:value} === "undefined"
```

#### `nuv =>` not undefined validation

```js
typeof ${1:value} !== "undefined"
```

#### `iov =>` instance of validation

```js
${1:value1} instanceof ${2:value2}
```

#### `av =>` array validation

```js
Array.isArray(${1:value}) || ${1:value}.length
```

#### `ov =>` object validation

```js
Object.keys(${1:value}).length === 0 && ${1:value}.constructor === Object
```

#### `cv =>` contains validation

```js
${1:value1}.indexOf(${2:value2}) > -1
```

#### `dcv =>` doesn't contain validation

```js
${1:value1}.indexOf(${2:value2}) === -1
```

***

## DOM manipulations

#### `ael =>` add event listener

```js
document.addEventListener("${1:event}", (${2:param}) => {

})
```

#### `rel =>` remove event listener

```js
document.removeEventListener("${1:event}", (${2:param}) => {

})
```

#### `cel =>` create element

```js
document.createElement("${1:value}")
```

#### `ach =>` append child

```js
document.appendChild("${1:value}")
```

#### `rch =>` remove child

```js
document.removeChild("${1:value}")
```

#### `gei =>` get element by id

```js
document.getElementById("${1:value}")
```

#### `gec =>` get element by class name

```js
document.getElementsByClassName("${1:value}")
```

#### `get =>` get element by tag name

```js
document.getElementsByTagName("${1:value}")
```

#### `qs =>` query selector

```js
document.querySelector("${1:value}")
```

#### `qsa =>` query selector all

```js
document.querySelectorAll("${1:value}")
```

***

## Console

#### `cl =>` console log

```js
console.log(${1:value})
```

#### `cw =>` console warn

```js
console.warn(${1:value})
```

#### `ce =>` console error

```js
console.error(${1:value})
```

***

## Destructuring

#### `od =>` object destructuring

```js
let { ${1:value1} } = ${2:value2}
```

#### `ad =>` array destructuring

```js
let [${1:value1}, ${2:value2}] = ${3:value3}
```

***

## Others

#### `rbt =>` react bind this

```js
this.${1:name} = this.${1:name}.bind(this)
```

#### `car =>` clone array

```js
let ${1:name} = ...${2:value}
```

#### `ph1 =>` placeholder 1

```js
`${${1:value}}`
```

#### `ph2 =>` placeholder 2

```js
`${${1:value1}} ${${2:value2}}`
```

#### `ph3 =>` placeholder 3

```js
`${${1:value1}} ${${2:value2}} ${${3:value3}}`
```

***

## Demo

#### These are the results after executing each and every snippet from the collection.

```js
// Assignments

let name = value // la
var name = value // va
const name = value // ca
let name = { // oa
   "key": value
}
let name = [value1, value2] // aa

// Functions

const name = (param) => { // af
    
}
function name (param) { // nf
    
}

// Conditions 

value1 === value2 // ec
value1 !== value2 // nec
value1 > value2 // gtc
value1 < value2 // ltc
value1 >= value2 // getc
value1 <= value2 // letc
condition1 || condition2 // oc
condition1 && condition2 // ac
let name = condition ? value1 : value2 // co

// Validations

value.length === 0 // zlv
value.length > 0 // plv
value === "" // esv
value !== "" // nesv
value === null // nv
value !== null // nnv
typeof value === "undefined" // uv
typeof value !== "undefined" // nuv
value1 instanceof value2 // iov
Array.isArray(value) || value.length // av
Object.keys(value).length === 0 && value.constructor === Object // ov
value1.indexOf(value2) > -1 // cv
value1.indexOf(value2) === -1 // dcv

// DOM manipulations

document.addEventListener("event", (param) => { // ael
    
})
document.removeEventListener("event", (param) => { // rel
    
})
document.createElement("value") // cel
document.appendChild("value") // ach
document.removeChild("value") // rch
document.getElementById("value") // gei
document.getElementsByClassName("value") // gec
document.getElementsByTagName("value") // get
document.querySelector("value") // qs
document.querySelectorAll("value") // qsa

// Console 

console.log(value) // cl
console.warn(value) // cw
console.error(value) // ce

// Destructuring

let { value1 } = value2 // od
let [value1, value2] = value3 // ad

// Others 

// Specially for ReactJS developers
this.name = this.name.bind(this) // rbt
let name = ...value // car
`${value}` // ph1
`${value1} ${value2}` // ph2
`${value1} ${value2} ${value3}` // ph3
```

***

## Questions, problems or something else?

##### There is a bug? Leave an issue on the [issues](https://github.com/mdyakov/SnipJS/issues) page or send a [pull request](https://github.com/mdyakov/SnipJS/pulls) with new features.

##### For questions, do not hesitate to write me an email - *dimitar.dyakov98@gmail.com*

##### Leave a star if you like and find the snippets helpful!

*** 

**Code by Dimitar Dyakov. Copyright 2019**
