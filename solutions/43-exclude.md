```ts
/* _____________ Your Code Here _____________ */

type MyExclude<T, U> = T extends U ? never : T
MyExclude<'a' | 'b' | 'c', 'a'> //'b' | 'c'
MyExclude<'a' | 'b' | 'c', 'a' | 'b'> // 'c'
```
- For each literal type in types T
  - if T can be assigned to U return never
  - else return T
