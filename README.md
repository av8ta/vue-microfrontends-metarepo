# single-spa vue-microfrontends metarepo

[meta repo](https://www.npmjs.com/package/meta) for example vuejs single-spa implementation at https://github.com/vue-microfrontends/

## clone all of the vue-microfrontends repos onto your machine:

```bash
npx meta git clone https://github.com/av8ta/vue-microfrontends-metarepo.git
```

[![asciicast](https://asciinema.org/a/efwJSpGYUi5ex0CaAhu6qfzkQ.svg)](https://asciinema.org/a/efwJSpGYUi5ex0CaAhu6qfzkQ)

## install all dependencies

```bash
npx meta yarn install
```

meta-yarn can also link child repos

```bash
npx meta yarn
```

```bash
Usage: meta-yarn [options] [command]

Options:
  -h, --help    output usage information

Commands:
  clean         delete the node_modules folder in meta and child repositories
  install       yarn install meta and child repositories
  link [--all]  yarn link child repositories where used within child and meta repositories
  help [cmd]    display help for [cmd]
```
