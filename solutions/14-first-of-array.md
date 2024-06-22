```ts
/* _____________ Your Code Here _____________ */

type First<T extends any[]> = T extends [infer K, ...infer rest] ? K : never

```
