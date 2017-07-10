# sketch-polyfill-setInterval

A [setInterval](https://developer.mozilla.org/fr/docs/Web/API/WindowTimers/setInterval) and [clearInterval](https://developer.mozilla.org/fr/docs/Web/API/WindowTimers/clearInterval) polyfill for sketch. It is automatically included (when needed) when using [skpm](https://github.com/skpm/skpm).

## Installation

```bash
npm i -S sketch-polyfill-setinterval
```

## Usage

```js
import {setInterval, clearInterval} from 'sketch-polyfill-setinterval'

const interval = setInterval(
  (param) => console.log(param),
  1000,
  'hello world'
)

clearInterval(interval)
```
