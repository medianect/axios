# axios

This is a updated fork of `@bundled-es-modules/axios`, itself a mirror of
[axios](https://www.npmjs.com/package/axios), bundled and exposed as ES module.

## Install

```
npm install @medianect/axios-bundled-as-es-module
```

For bower please for now refer to `@bundled-es-modules` version.

## Use

```html
<script type="module">
  // from main file
  import { axios } from 'axios';
  // or directly
  import axios from 'axios/axios.js';
  console.log(axios);
</script>
```

Make sure you added `@medianect` scope to the path if used via npm.
