# lyrics-finder

This package contains code for retrieving song information and lyrics from Google and Musixmatch. The code is written in TypeScript and uses the JSDOM library for DOM manipulation and axios for making HTTP requests.

## Installation

npm:

```bash
npm install @flytri/lyrics-finder
```

yarn:

```bash
yarn add @flytri/lyrics-finder
```

## Example usage

```js
const { Google, Musixmatch } = require("@flytri/lyrics-finder");

Google("Hai phút hơn", "vi").then(console.log);
// and
Musixmatch("Hai phút hơn").then(console.log);
```

## License

This code is provided under the **MIT License**. Feel free to modify and use it in your projects.
