# React+Redux Code Snippets

Install here: https://marketplace.visualstudio.com/items?itemName=aakashns.react-power-snippets

Snippets for React+Redux power users. Designed to take maximum advantage of Javascript Intellisense (code-completion). 

<img src="https://i.imgur.com/zfqObyD.gif" width="500px">

To enable code completion for filenames and `npm` modules, add the following to your User Settings:

```json
  "editor.quickSuggestions": {
    "other": true,
    "comments": false,
    "strings": true
  }
```

## Snippets

### `imn` : ES6 named imports

<img src="https://i.imgur.com/huHrOLH.gif" width="500px">

**Notes**

* As you start typing the module name (or relative path), which is autocompleted.

* As you start typing the name of an import inside `{ }`, it is also autocompleted, since the editor knows which file you're importing from.

### `imd` : ES6 default import

<img src="https://i.imgur.com/DjS9KTi.gif" width="500px">

**Notes**

* Use this when you're importing from an `npm` module.

### `imdn` : ES6 default import (reverse)

<img src="https://i.imgur.com/lcdI9OX.gif" width="500px">

**Notes**

* Use this when you're importing from a relative path. The path is autcompleted as you type.

* If the name you're using for default export is same as the filename, that is also autocompleted.

### `ec` : ES6 named export

<img src="https://i.imgur.com/P8OlCWG.gif" width="500px">

### `ed` : ES6 default export

<img src="https://i.imgur.com/Qxxk6V8.gif" width="500px">

### `ec` : ES6 named export

<img src="https://i.imgur.com/P8OlCWG.gif" width="500px">

### `log` : Console log

<img src="https://i.imgur.com/mW8SRNx.gif" width="500px">

### `imr` : Import React

<img src="https://i.imgur.com/GyltmTu.gif" width="500px">

### `imrc` : Import React & Component

<img src="https://i.imgur.com/OZhMqBB.gif" width="500px">

### `imrpc` : Import React & PureComponent

<img src="https://i.imgur.com/P2XEsPT.gif" width="500px">

### `sl` : Stateless component

<img src="https://i.imgur.com/5iYFFjw.gif" width="500px">

**Notes**

* The name of the file is used as the component name, and can be modified if required.

* If the component has no props, make sure to delete the `{}`.

### `slr`: Stateless component with `return`

<img src="https://i.imgur.com/fOTa4mJ.gif" width="500px">

**Notes**

* The name of the file is used as the component name, and can be modified if required.

* If the component has no props, make sure to delete the `{}`.

### `edccs`: Class component (with export default)

<img src="https://i.imgur.com/zfqObyD.gif" width="500px">

**Notes**

* The name of the file is used as the component name, and can be modified if required.

### `ccs`: Class component

<img src="https://i.imgur.com/HZ0T5bG.gif" width="500px">

**Notes**

* The name of the file is used as the component name, and can be modified if required.

### `container`: Redux container component

<img src="https://i.imgur.com/65hiwyd.gif" width="500px">

More snippets coming soon..

## Requirements

None

## Extension Settings

None

## Known Issues

None

## Release Notes

### 1.0.0

- Initial release

### 1.1.0

- List prefixes and add GIF previews

- Use filename as component name
