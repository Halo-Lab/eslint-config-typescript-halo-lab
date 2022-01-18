# Eslint halo lab config TypeScript

## Installation
```
npm install --save-dev eslint-config-halo-lab-typescript
```

## Usage
In ```.eslintrc```:
```json
{
  "extends": [
    "halo-lab-typescript"
  ]
}
```

And add your ```tsconfig.json``` in ```.eslintrc```;

```json
{
  "parserOptions": {
    "project": "tsconfig.json",
    "tsconfigRootDir": "."
  }
}
```

## Word from author

Have fun! ✌️

<a href="https://www.halo-lab.com/?utm_source=github">
  <img src="https://dgestran.sirv.com/Images/supported-by-halolab.png" alt="Supported by Halo lab" height="60">
</a>
