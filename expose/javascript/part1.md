1. values added: 20
2. final result: 20
3. var is function-scoped instead of block-scoped. This could allow access to this variable, outside of the block they were declared in like the above example.
4. values added: 20
5. error, since result is only accessible within the block or if statement it was declared in.
6. error, can't reassign a const variable.
7. final result: 0