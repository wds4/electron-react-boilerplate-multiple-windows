<img src=".erb/img/erb-banner.svg" width="100%" />

<br>

<p>
  Electron React Boilerplate uses <a href="https://electron.atom.io/">Electron</a>, <a href="https://facebook.github.io/react/">React</a>, <a href="https://github.com/reactjs/react-router">React Router</a>, <a href="https://webpack.js.org/">Webpack</a> and <a href="https://www.npmjs.com/package/react-refresh">React Fast Refresh</a>.
</p>

<br>

A fork of [electron-react-boilerplate](https://github.com/electron-react-boilerplate/electron-react-boilerplate) with multiple renderer windows (three in this demo), each with its own renderer process. Each window is functional in development and in the packaged app.

<br>

I am following the example of [this repo](https://github.com/jp887/electron-react-boilerplate) which does the same thing but starts from an earlier version of electron-react-boilerplate.
In the intervening time, electron-react-boilerplate has incorporated several changes including update from webpack 3 to webpack 5. These changes necessitate a few additional steps to be involved, most notably involving the HtmlWebpackPlugin plugin in webpack.config.renderer.dev.ts and webpack.config.renderer.prod.ts files. See [commit history](https://github.com/wds4/electron-react-boilerplate-multiple-windows/commits) for the steps.

## Install

Clone the repo and install dependencies:

```bash
git clone --depth 1 --branch main https://github.com/wds4/electron-react-boilerplate-multiple-windows.git your-project-name
cd your-project-name
npm install
```

## Starting Development

Start the app in the `dev` environment:

```bash
npm start
```

## Packaging for Production

To package apps for the local platform:

```bash
npm run package
```

## License

MIT © [Electron React Boilerplate](https://github.com/electron-react-boilerplate)
