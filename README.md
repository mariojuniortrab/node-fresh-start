# NODE-FRESH-START

This is a small boilerplate to start a node app using Typescript with some code and commit padronization. It verifies your code before each commit and try to auto-fix it. Jest is already pre configured and it tests your code before each commit, so, you are not allowed to commit with tests issues. And finally, it validade your commit message using [Convention Commit](https://www.conventionalcommits.org/en/v1.0.0/) rules.

## Installation

First you must install [Eslint](https://eslint.org/) and [Jest](https://jestjs.io/) globally:

```bash
npm install -g eslint && npm install -g jest
```

Then you have to clone it:

```bash
git clone https://github.com/mariojuniortrab/node-fresh-start.git
```

And install dependencies:

```bash
cd node-fresh-start && npm install
```

## Usage

Now, you can create your code inside **src** folder.
You can compile your Typescript code into Javascript following this [tutorial](https://docs.microsoft.com/pt-br/visualstudio/javascript/compile-typescript-code-npm?view=vs-2019)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)