# cloudflare stout on npm

- repo: https://github.com/balupton/cloudflare-stout-npm
- npm: http://npmjs.com/package/cloudflare-stout

mirrors [cloudflare stout](https://github.com/cloudflare/stout) releases to npm, such that you can do

this for local installations of stout:

```
npm install --save cloudflare-stout
npx stout-linux
npx stout-osx
npx stout-windows
npx stout
```

and this for global installations of stout:

```
npm install --global cloudflare-stout
stout-linux
stout-osx
stout-windows
stout
```

the `stout` executable is a bash script that will:

- determine your platform and use the appropriate executable for it
- determine if env vars "$ACCESS_KEY_ID" "$ACCESS_KEY_SECRET" are set, and if so, use their values for the --key and --secret arguments

for when stout releases a new version, just post a new issue, and I'll run the `./update` script
