# Content Template
[![License](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

A template repository to quickly deploy content-only pages to the Digital Land website.

## Requirements

- [Node.js >= 12](https://nodejs.org/)
- [npm](https://npmjs.com/) (bundled with Node)

## Getting started

You can use this as a template repository within GitHub.com or you can [download this repository as a ZIP](https://github.com/digital-land/content-template/archive/master.zip).

For example:
```
git clone https://github.com/digital-land/content-template.git --recursive
cd content-template
npm install
```

Then you can add a remote:
```
git remote add {remote-name} https://github.com/../{new-repository-url}.git
git push -u {remote-name} master
```

You can add some content in the `content` directory. `npm run prestart` will compile these into the `docs` directory and you can expose it through GitHub Pages.

`npm run start` will also compile content into the `docs` directory, and will also expose it at `localhost:8080`.
