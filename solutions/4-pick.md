```ts
/* _____________ Your Code Here _____________ */

type MyPick<T, K extends keyof T> = {[key in K] : T[key]}
```
