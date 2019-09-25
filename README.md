# Default themes for TypeDoc

This module contains the default themes of TypeDoc.
Visit https://typedoc.org/ to learn more about TypeDoc.


## Contributing

This repo is a mirrored copy of the one from [https://github.com/TypeStrong/typedoc](https://github.com/TypeStrong/typedoc)

You should keep your `origin` set to this mirrored version, and set your `upstream` remote to the original.

This way, if there are any necessary changes `upstream` that need to be merged in, we can keep in sync with the original.

### Branches

* `master`: is the "pristine" copy that will be used for any mParticle TypeScript projects

* `typedoc-master`: should be synced with `upstream` every so often.

The workflow should be as follows:

* Branch off `master` and create a feature branch

* Pull requests should be made against `master`

* Every so often, `typedoc-master` should be synced with the `upstream` remote then merged into `master`

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
