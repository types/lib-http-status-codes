# HTTP Status Codes

This type defintion utilizes the 
[const enum](https://github.com/Microsoft/TypeScript/blob/master/doc/spec.md#94-constant-enum-declarations)
feature of typescript to replace the status code name
with it's code number at compile time.

Just install the typings:

```
typings install --save --global http-status-codes
```

And use it:

```js

const ok = HTTPStatusCodes.OK;

ok === 200 // true

```

**Note**: Make sure `--preserveConstEnums` is not passed to the compiler.

## License
This project is licensed under the 
[MIT license](https://github.com/typed-typings/global-http-status/blob/master/LICENSE).
