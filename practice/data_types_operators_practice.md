# Javascript Data Types Exercises

## Data Types

For each expression, predict what you think the output will be in a comment (`//`) ***without first running the command***. Then run the expression in the console. Note the actual output in a comment and compare it with your prediction.

#### Example

```js
typeof("potato")
// Prediction: Vegetable
// Actual: String
```

What is the output of each of the expressions below?

```js
typeof(15)
// Prediction: Integer
// Actual: Number

typeof(5.5)
// Prediction:Number
// Actual:Number

typeof(NaN)
// Prediction: String
// Actual: Number

typeof("hello")
// Prediction: String
// Actual: String

typeof(true)
// Prediction: Boolean
// Actual: Boolean

typeof(1 != 2)
// Prediction: Boolean
// Actual: Boolean


"hamburger" + "s"
// Prediction: "hamburgers"
// Actual: "hamburgers"

"hamburgers" - "s"
// Prediction: "hamburger"
// Actual: NaN

"1" + "3"
// Prediction: 4
// Actual:"13"

"1" - "3"
// Prediction: -2
// Actual: -2

"johnny" + 5
// Prediction: "johnny5"
// Actual: "johnny5"

"johnny" - 5
// Prediction: NaN
// Actual: NaN

99 * "luftbaloons"
// Prediction: NaN
// Actual: NaN
```

What's going on in the second half of the previous question? Are there any "rules" we can pull from those examples?

What's going in the second half of the problems is a js operator behavior called type coercion

## Booleans & Comparison Operators

Here's an example truth table for the `!` (not) operation. In it, we're listing the values of `!a` that correspond with a given value of `a`.

|a|!a|
|---|---|
|true|false|
|false|true|

Fill out the truth tables below for `&&` (and), `||` (or) and one that uses multiple comparison operators. All you need to do is replace the `?`'s with either `true` or `false`.

> **NOTE:** Because of markdown formatting, `||` and `&&` have been replaced with `OR` and `AND` respectively.
>
> **HINT:** With the last one, it may be helpful to add additional columns to the table for each individual comparison.

| a | b | a AND b |
| --- | --- | --- |
| true | true | ? true |
| true | false | ? false |
| false | true | ? false |
| false | false | ? true |

|a|b|a OR b|
|---|---|---|
|true|true|? true |
|true|false|? true |
|false|true|? true |
|false|false|? false |

|a|b|a `!=` b|
|---|---|---|
|3|3|? false |
|1|5|? true |
|2|"2"|? false |

|a|b|!a AND (a OR b)|
|---|---|---|
|true|true|? false|
|true|false|? false|
|false|true|? true|
|false|false|? false|

<sup>Exercises adapted from [General Assembly](https://github.com/ga-wdi-exercises/js-data-types/blob/master/exercise.md)</sup>
