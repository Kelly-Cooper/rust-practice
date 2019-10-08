## Quick Reminder List
### Notes from The Rust Programming Language, Klabnik and Nichols, no starch press

Helps my brain shift between Rust and Go to visualize this reminder.

`cargo new name`

`cd name`

`cargo build` 
compile

`./target/debug/name #` 
create executable, use debug while working

`cargo run` 
use run when done working

`cargo check` 
make sure - quality check

`cargo build --release` 
create executable in target/release rather than target/debug. Compile with optimizations

`const` 
declare constant

`let`
declare variable

Constants can be declared in any scope - set to constant expression not to the result of a function call or a value that can be computed at runtime

Variable shadowing - first variable is shadowed by the second. Value is what appers when the variable is used. Use same variable name - repeat use of let keyword.

```let x = 10;
let x = x + 5;
let x = x * 4;
```

first binds to 10, then 15, then 60

Perform a few transformations on a value; value is immutable after transformations are complete
Multiple `let` can change type

### Data Types

Scalar represent a single value: integer, floating-point, Boolean, characters
floating-point f32 - f64 (default)

`let x = 2.0; //f64
let y: f32 = 3.0; //f32`

Numeric operations
`let sum = 5 + 10;'
'let difference = 95.5 - 4.3;'
'let product = 4 * 30;'
'let quotient = 56.7/32.2;'
'let remainder = 43 % 5;`

Boolean
`let t = true;
let f :bool = false;`

Character - single quote, string literals double quote
`let c = 'z';`

Compound types
tuple - fixed length
let tup :(i32, f64, u8) = (500, 6.4, l);
  variable tup binds to the entire tuple to get individual values - since considered a single compound element


      
      
