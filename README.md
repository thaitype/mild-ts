# mild-ts
Opinionated TypeScript Utility Libraries

## Packages
- [@mild-ts/utils](https://github.com/mild-ts/utils)
- [@mild-ts/rest-client](https://github.com/mild-ts/rest-client)

## TODO

- [retry-helper](https://github.com/actions/checkout/blob/ac593985615ec2ede58e132d2e21d2b1cbd6127c/src/retry-helper.ts)
- ConsoleLogger

```ts
// https://pawelgrzybek.com/make-the-typescript-interface-partially-optional-required/
export type PartialRequired<T, K extends keyof T> = Omit<T, K> & Required<Pick<T, K>>;
```

