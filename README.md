# cloudflare stout on npm

- repo: https://github.com/balupton/cloudflare-stout-npm
- npm: http://npmjs.com/package/cloudflare-stout

mirrors cloudflare stout releases to npm, such that you can do:

```
npm install --save cloudflare-stout@1.3.1
npx stout-linux
npx stout-osx
npx stout-windows
npx stout  # runs the appropriate executable for your platform
```

and

```
npm install --global cloudflare-stout@1.3.1
stout-linux
stout-osx
stout-windows
stout  # runs the appropriate executable for your platform
```
