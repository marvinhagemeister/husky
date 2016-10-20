# husky-dontbark

This project is a fork of [husky](https://github.com/typicode/husky) with an additional config to
silence all these pesky `npm ERR` messages.

## Usage

Same as [husky](https://github.com/typicode/husky). Simply install it:

```bash
npm install husky-dontbark --save-dev
```

Silencing `npm ERR` messages by adding a config setting to your `package.json`:

```json
{
  "name": "mypackage",
  "config": {
    "husky": {
      "silent": "true"
    }
  }
}
```

## More Information

For more information see the upstream [husky repository](https://github.com/typicode/husky).

## License

MIT
