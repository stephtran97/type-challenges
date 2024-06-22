```ts
/* _____________ Your Code Here _____________ */

type TupleToObject<T extends readonly (string | number | symbol)[]> = {
  [k in T[number]]: k
}
// key of an object can only be string | number | symbol
```
