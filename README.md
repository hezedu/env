## 简单的Eslint配置
.eslintrc.json es6:
```js
{
    "env": {
        "browser": true,
        "node": true,
        "commonjs": true,
        "es6": true
    },
    "extends": "eslint:recommended",
    "parser": "babel-eslint",
    "parserOptions": {
        "ecmaFeatures": {
            "experimentalObjectRestSpread": true
        },
        "sourceType": "module"
    },
    "rules": {
        "indent": [
            "warn",
            2
        ],
        "no-unreachable": "warn",
        "no-unused-vars": "warn",
        "no-trailing-spaces": 0,
        "no-multiple-empty-lines": 0,
        "prefer-const": 0,
        "space-infix-ops": "warn",
        "camelcase": 0,
        "no-console": 0,
        "linebreak-style": 0,
        "quotes": 0,
        "semi": 0
    }
}
```
package.json devDependencies:
```json
{
    "babel-eslint": "^6.1.2",
    "eslint": "^3.4.0"
}
```
