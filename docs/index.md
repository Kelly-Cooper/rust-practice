
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
let x = x * 4;```

first binds to 10, then 15, then 60

Perform a few transformations on a value; value is immutable after transformations are complete
Multiple `let` can change type


in progress - adding daily


      
      
