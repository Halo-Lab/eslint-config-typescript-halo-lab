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

## Status and contribution
The project is supported by Halo lab development team, we're not working on it regularly, but trying to invest in it when we have time between clients' project. <br />
Though, feel free to open issues and you're very welcome to contribute. 
 <br />
  <br />
<a href="https://www.halo-lab.com/?utm_source=github-brifinator-3000">
    <img src="http://api.halo-lab.com/wp-content/uploads/dev_halo.svg" alt="Developed in Halo lab" height="60">
</a>
