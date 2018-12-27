# UKY MAP 672 Module Three Quiz

1. The parameters in this function are (a, b) and the arguments are (7, "7"). JS in this case is applying "type conversion" when comparing the two numbers because one of them is a string. The reason it is returning "7" is because once the two arguments enter the function, they fail the first if statement, then it defaults to the else. The reason it fails the first if statement is because technically 7 is not greater than 7, it is equal to 7. So that leaves us with "7".

<!-- Yep! Good answer. 7 == "7" is true! -->

2. The problem with this function is that the console.log() function is trying to access the variable inside of the function instead of the variable outside (geographer). It also is not returning the value it is looking for. I have fixed it here:

```js
  var geographer = 'ptolemy';
    function shoutName(geoName) {
      var capitalizedName = geoName.toUpperCase();
      return capitalizedName
    };
  console.log(shoutName(geographer));
```

<!-- Another good answer! 😀 -->

3. 

```js
    function squaredNum(num) {
      var numSquared = num ** 2;
      return numSquared
    };
    console.log(squaredNum(10))
```

#### Matthew Upchurch 10/27/2018
