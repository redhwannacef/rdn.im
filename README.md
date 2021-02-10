# rdn.im

A url shortener inspired by https://github.com/kentcdodds/netlify-shortener that uses firebase.

All redirects are held in the `./firebase.json` file.

## Example

Given the hostname https://rdn.im, an entry of:

```json
{
  "source": "/youtube",
  "destination": "https://www.youtube.com/c/RedhwanNacef",
  "type": 301
}
```
will redirect from https://rdn.im/youtube to https://www.youtube.com/c/RedhwanNacef.
