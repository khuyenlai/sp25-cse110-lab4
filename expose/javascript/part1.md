1. values added: 20  
2. final result: 20
3. You shouldn't use var because it is function-scoped instead of block-scoped. This means variables delared with var inside a block can still be accessed outside of it, which can lead to unexpected behavior and bugs. Using let or const instead helps keep variables limited to the block where they're defined, making your code safer and easier to understand.
4. values added: 20
5. Returns an error. The variable result was decalred using let, which is block-scoped. This means result only exists inside the if block. When the code tries to access result outside of that block (on line 13), it causes an error because result is not defined in that scope. 
6. Returns an error. This is because result is declared as a const, which cannot be reassigned.
7. Does not print anything. This is because line 13 is never reached since there was an error previously.