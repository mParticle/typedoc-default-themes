# Default themes for TypeDoc

This module contains the default themes of TypeDoc.
Visit https://typedoc.org/ to learn more about TypeDoc.

## Using for an mParticle project

Install typedoc and custom themes

```
npm i -D typedoc git+ssh://git@github.com:mParticle/typedoc-default-themes.git#mp-custom

```


Add/Update `typedoc.json` in the root of your project

```
{
    "name": "Project Name",
    "readme": "./README.md",
    "theme": "./node_modules/typedoc-default-themes/bin/mptheme",
}
```

Add any other custom configurations based on [TypeDoc Arguments](https://typedoc.org/guides/arguments/)

Add build task to your package.json scripts

```
"scripts": {
    "docs": "typedoc src/"
}
```

Run `npm run docs` to generate your docs!

## Contributing

This repo is a forked copy of the one from [https://github.com/TypeStrong/typedoc](https://github.com/TypeStrong/typedoc)

You should keep your `origin` set to this forked version, and set your `upstream` remote to the original.

This way, if there are any necessary changes `upstream` that need to be merged in, we can keep in sync with the original.

### Branches

* `master`: is the "pristine" copy of the original repo and should be synced with `upstream` every so often.

* `mp-custom`: should be used for any mParticle TypeScript project. `master` from `upstream` should be synced in every so often.

The workflow should be as follows:

* Branch off `mp-custom` and create a feature branch

* Pull requests should be made against `mp-custom`

* Every so often, `master` should be synced with the `upstream` remote then merged into `origin` `master`

### Contributions to Original Project

Contributions are welcome and appreciated. You can find TypeDoc on GitHub, feel free to start
an issue or create a pull requests:<br>
[https://github.com/TypeStrong/typedoc](https://github.com/TypeStrong/typedoc)

To use a local build of this project, run the `npm pack` command in this directory. Then
in the project where you want to use your local build run `npm install ../path/to/typedoc-default-themes-VERSION.tgz`


## Original License

Copyright (c) 2015 [Sebastian Lenz](http://www.sebastian-lenz.de).<br>
Copyright (c) 2016-2019 [TypeDoc Contributors](https://github.com/TypeStrong/typedoc/graphs/contributors).<br>
Licensed under the Apache License 2.0.
