# gitassignment

1. Differentiation of let, const, and var in JavaScript

Imagine varables are containers holding information. In JavaScript, you have three main ways to create these containers:
var, let and const.

Var (old-fashioned): Think of these as big, shared containers. You can put stuff in them, change what's inside, and even create another container with the same name in the same area. It's messy, so we try to avoid it now.
Let (flexible): These are smaller, more organized containers. You can chnage what's inside, but you can only have one container with that specific name in a given area.
Const (constant): These are sealed containers. Once you put something in, you can't change it. You also need to fill them right away when you create them.

It's best to use const unles you know you need to change the value later. If you need to change the value, Use let. Avoid var because it's less organized and can lead to errors.

References
www.w3schools.com › js_let
www.w3schools.com › js_variables
www.w3schools.com › js_const

2. Concept of Falsy Values in JvaScript

Imagine you're asking JavaScript a yes/no question using an if statement. Sometimes, JavaScript will answer "no" even if you didn't explicitly say "false". These are called "falsy" values. They're not false, but they act like it in if statements and other places where JavaScript expects a true/false answer:

Some common falsy values are:
false: This one's obvious.
0 (zero): Nothingness in number.
-0 (negative zero): same as above.
0n (BigInt zero): A special type of zero.
"" (empty string): No text at all.
null: Means "nothing" in a more general sense.
undefined: Means a variable hasn't been given a value yet.
NaN (Not a Number): Represents a failed number calculation.

If you use any of these in an if statement, JavaScript will treat it as a "no" (false) and skip the code inside the if block. Anythng else is considered "truthy" and will run the code.

References
https://wesbos.com/javascript/07-logic-and-flow-control/if-statements-function-returns-truthy-falsy?need_sec_link=1&sec_link_scene=im
https://www.freecodecamp.org/news/what-are-falsey-values-in-javascript/?need_sec_link=1&sec_link_scene=im
https://bobbyhadz.com/blog/javascript-check-if-value-is-falsy?need_sec_link=1&sec_link_scene=im
