1. values added: 20
2. final result: 20
3. We should not use var because it has function scope, which can lead to unexpected behavior.
4. values added: 20
5. ReferenceError: result is not defined. We get this error because using let limits the scope of result to the block in which it is defined, and it is not accessible outside that block.
6. Cannot assign to "result" because it is a constant. This error occurs because we are trying to reassign a value to a constant variable, which is not allowed in JavaScript.
7. ReferenceError: result is not defined. We get this error because using const limits the scope of result to the block in which it is defined, and it is not accessible outside that block.