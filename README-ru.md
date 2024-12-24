# @gravity-ui/babel-preset

Предустановка конфигурации Babel для проектов Gravity UI.

## Установка

```
npm install --save-dev @gravity-ui/babel-preset
```

## Использование

### Через `.babelrc`

```json5
{
  "presets": [
      "@gravity-ui/babel-preset",
      {
        "env": {modules: false}, // defaults to {}
        "runtime": {useESModules: true}, // defaults to {}
        "typescript": true, // defaults to false
        "react": {runtime: "automatic"} // defaults to {}
      }
  ]
}
```
