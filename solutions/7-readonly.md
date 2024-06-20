```ts
/* _____________ Your Code Here _____________ */

type MyReadonly<T> = {
  readonly [k in keyof T] : T[k]
}
```
