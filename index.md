   ### Write the output of each line of code:

 - `21 > 11;` // true
 - `200 < 11;` // false
 - `11 >= 21;` // false
 - `200 <= 100;` // false
 - `200 != 200;` // false
 - `"A" > "B";` // false
 - `"d" < "a";` //  flase
 - `"Hello" < "World";` //  true
 - `"JavaScript" >= "Java";` //  false

  <!--# Equality Operator -->

 - `200 == 200;` // true
 - `null == 0; `// false
 - `null == "";` // false
 - `null == false;` // flse
 - `undefined == 0;` // false
 - `undefined == "";` // flase
 - `undefined == false;` // false
 - `NaN == 0;` // false
 - `NaN == "";` //  false
 - `NaN == false;` // false
 - `200 === 200;` // true
 - `0 == false;` // true
 - `0 == "";` // true
 - `"" == false;` // true
 - `0 === false;` // false
 - `true === 1;` // false
 - `"21" === "21";` // true
 - `"21" === 21;` // false

  <!-- Double and Triple equal -->
 ```js
 `let a = 5,
    b = 10,
    c = "5";
    let x = a;
 ```
   ## What will be the output of the code below on the basis of above code:

 - `a == c;` //  true
 - `a === c;` // false
 - `a == x;` // true
 - `a != b;` // true
 - `a > b;` // false
 - `a < b; `// true
 - `a >= b;` // false
 - `a <= b;` // true
 - `a >= c;` // true
 - `a <= c;` // true

   ### Output of the following line of code.

 - `"NaN" && "undefined" && 0;`// 0
 - `"AT" && "" && false; `// ""
 - `"AT" && " " && false;` // false
 - `"AT" || 5;` // "AT"
 - `" " || "AT" || false;` // " " 
 - `!{};` // false
 - `!""; `// true
 - `!"OK";` // false
 - `!false;` // true
 - `!true;`// false

   ### Enter a number as input and check whether it's divisible by 5 OR 7, alert true and false based on that.
  
  ```js
     let num = Number(prompt("Enter a number"));
     num % 5 === 0 || num % 7  ===  0 ? alert(true) : alert(false)
  ``` 
   ### Enter a number as input and check whether it's divisible by 2 AND 4, alert true and false based on that.

   ```js
      let num = Number(prompt("Enter a number"));
      num % 2 === 0 && num % 4 === 0 ? alert(true) : alert(false)
   ```