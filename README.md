# typecheck-flowtype

```sh
$ npm run typecheck

...

src/index.js:5
  5: const bar = foo('2');
                 ^^^^^^^^ function call
  5: const bar = foo('2');
                     ^^^ string. This type is incompatible with
  2: declare export default function foo(x: number): number;
                                            ^^^^^^ number. See: src/foo.js.flow:2


Found 1 error
```
