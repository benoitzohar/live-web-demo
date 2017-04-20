# Live Web Playground
An auto-reloading simple web app boilerplate (using Webpack) for quick JS/CSS demos.


### Installation

Clone the repository locally:

```
git clone https://github.com/benoitzohar/live-web-playground.git
```

and install the dependencies:

```
npm install
```
or
```
yarn
```


### Usage

```
npm start
```

or

```
yarn start
```

You can then open [localhost:8080](http://localhost:8080/) in your browser and start editing files in `/src`.
The browser will be reloaded when you change a file.

To import a new library :
```
npm install [library_name]
```
or
```
yarn add [library_name]
```

then add this in `src/app.js`:
```js
const lib = require('[library_name]');
```


### Reset

Once you've finished your demo, use this to fully reset the local repository:

```
npm run reset
```
or
```
yarn reset
```


> **Warning**  
> This will permanently remove any change you made so make sure everything in there was temporary before running this command.
