# Storage JS

A simple JS function that manages your web browser storage.

Supports **sessionStorage** and **localStorage**.

Import the lib. You need the download the **storage.js** file. Currently there is no npm repository.
```js
import storage from './storage';
```

## Usage

Get value
```js
storage('key')
```

Set value
```js
storage('key', 'value')
storage('key', ['value 1', 'value 2'])
storage('key', {'key1': 'value1', 'key2': 'value 2'})
```

Remove value
```js
storage('key', null, true)
```

## MIT

[MIT](http://opensource.org/licenses/MIT)
