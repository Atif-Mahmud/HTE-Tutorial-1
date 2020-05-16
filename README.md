# Quick Tutorial on Node and Rest API

This project uses [axois](https://www.npmjs.com/package/axios) instead of fetch
but it can easily be interchanged. I prefer axios for it's simplicity so it's
included here.

Simply include a `constants.json` file to house your API key.

```json
{
  "FDCKey": "MY KEY HERE"
}
```

After that simply run:
```bash
npm install
```
to install axios, and any other dependencies you may have.

Run your server by using:
```
node index.js
```
