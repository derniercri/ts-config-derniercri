# How to use ?

Install the package:

```bash
$ yarn add -D git+https://git@github.com/derniercri/ts-config-derniercri.git
```

Create or edit a `tsconfig.json` file at project's root :

```js
{
  // Web (React)
  "extends": "ts-config-derniercri/tsconfig.web.json"

  // Mobile (React Native)
  "extends": "ts-config-derniercri/tsconfig.mobile.json"
}
```

And voilà !