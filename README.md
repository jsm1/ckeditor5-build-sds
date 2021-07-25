# CKEditor 5 classic editor build (SDS Fork)

[![npm version](https://badge.fury.io/js/%40ckeditor%2Fckeditor5-build-classic.svg)](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic)
[![Coverage Status](https://coveralls.io/repos/github/ckeditor/ckeditor5/badge.svg?branch=master)](https://coveralls.io/github/ckeditor/ckeditor5?branch=master)
[![Build Status](https://travis-ci.com/ckeditor/ckeditor5.svg?branch=master)](https://travis-ci.com/ckeditor/ckeditor5)

The classic editor build for CKEditor 5. Read more about the [classic editor build](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/overview.html#classic-editor) and see the [demo](https://ckeditor.com/docs/ckeditor5/latest/examples/builds/classic-editor.html).

## Documentation

See:

- [Installation](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/installation.html) for how to install this package and what it contains.
- [Basic API](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/basic-api.html) for how to create an editor and interact with it.
- [Configuration](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/integration/configuration.html) for how to configure the editor.
- [Creating custom builds](https://ckeditor.com/docs/ckeditor5/latest/builds/guides/development/custom-builds.html) for how to customize the build (configure and rebuild the editor bundle).

## Quick start

To use in development in SDS with watched reloading:

1. Run `yarn link` here.
2. Run `yarn link @hellospruce/ckeditor5-build-sds` in SDS.
3. Run `yarn dev` here. SDS's Storybook will recompile with changes you make here. It's a little slow and some Webpack changes here might not trigger a reload but most changes will come through.

## Notes

- `yarn add` editor plugins here. If they're CKEditor core they will likely already be downloaded and just need to be imported into `src/ckeditor.js`.
- Replace default toolbar icons by following the syntax in `theme/icons/index.js`

## License

Licensed under the terms of [GNU General Public License Version 2 or later](http://www.gnu.org/licenses/gpl.html). For full details about the license, please check the `LICENSE.md` file or [https://ckeditor.com/legal/ckeditor-oss-license](https://ckeditor.com/legal/ckeditor-oss-license).

```

```
