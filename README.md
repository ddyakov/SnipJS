# SnipJS 

![alt text](https://github.com/mdyakov/SnipJS/blob/master/logo.png "SnipJS logo")

### A collection of common javascript statement snippets for faster development in [Visual Studio Code](https://code.visualstudio.com/).

***

* [Assignments](#assignments)
* [Functions](#functions)
* [Conditions](#conditions)
* [Validations](#validations)
* [DOM manipulations](#dom-manipulations)
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
 let ${1:obj} = {
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

#### `ac =>` and condition

```js
${1:condition1} && ${2:condition2}
```

#### `oc =>` or condition

```js
${1:condition1} || ${2:condition2}
```

#### `co =>` condition operator

```js
let ${1:name} = ${2:condition} ? ${3:value1} : ${4:value2}
```

***

## Validations

#### `lv =>` length validation

```js
${1:value}.length === ${2:0}
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

#### `cv =>` contains validation

```js
${1:value}.indexOf(${2:value2}) > -1
```

#### `dcv =>` doesn't contain validation

```js
${1:value}.indexOf(${2:value2}) === -1
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

#### `ce =>` create element

```js
document.createElement("${1:element}")
```

#### `gei =>` get element by id

```js
document.getElementById("${1:id}")
```

#### `gec =>` get element by class name

```js
document.getElementsByClassName("${1:class}")
```

#### `qs =>` query selector

```js
document.querySelector("${1:selector}")
```

#### `qsa =>` query selector all

```js
document.querySelectorAll("${1:selector}")
```

***

## Others

#### `od =>` object destructuring

```js
const { ${1:name} } = ${2:value}
```

#### `cl =>` console log

```js
console.log(${1:value})
```

***

## Questions, problems or something else?

##### There is a bug? Leave an issue on the [issues](https://github.com/mdyakov/SnipJS/issues) page or send a [pull request](https://github.com/mdyakov/SnipJS/pulls) with new features.

##### For questions, do not hesitate to write me an email - *dimitar.dyakov98@gmail.com*

##### Leave a star if you like and find the snippets helpful!

*** 

**Code by Dimitar Dyakov. Copyright 2019**