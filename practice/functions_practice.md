# JavaScript Functions Practice

Complete the coding exercises [here](https://www.teaching-materials.org/javascript/exercises/functions)

# All Solutions


```js


const tellFortune = function(numOfChildren,partnerName,location,jobTitle){
    return `You will be a ${jobTitle} in ${location}, and married to ${partnerName} with ${numOfChildren} kids`
}

const calculateDogAge = function(dogsAge){
    return `Your doggie is ${dogsAge/7} years old in dog years!`
}

const calculateSupply = function(age,amountPerDay){
    const maxAge = 89
    let amountPerYear = amountPerDay * 365
    return `You will need ${amountPerYear * (maxAge - age)} to last you until the ripe old age ${maxAge}`
}

const calcCircumfrence = function(radius){
   const Circumfrence =  2 * Math.PI * radius 
   return Circumfrence
}

const calcArea = function (radius){
    const Area = Math.PI * Math.pow(radius, 2)
    return Area
}

const celsiusToFahrenheit = function (degreesCelsius){
    const degreesFahrenheit =  32 + (1.8 * degreesCelsius)
    return `${degreesCelsius}Celsius is ${degreesFahrenheit}Fahrenheit`
}

const fahrenheitToCelsius = function (degreesFahrenheit){
    const degreesCelsius = .5556 * (32 - degreesFahrenheit)
    return `${degreesFahrenheit}Fahrenheit is ${degreesCelsius}Celsius`
    
}
```
