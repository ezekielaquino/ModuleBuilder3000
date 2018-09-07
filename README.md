# ModuleBuilder3000

Get started building your plugins, modules, and javascript based experiments smooth as butter.

This is basically a package that sets up [Microbundle](https://github.com/developit/microbundle) and [Parcel](https://github.com/parcel-bundler/parcel) for you. The only thing you gotta do is :sparkles:Start:sparkles:.


## The setup

**Scripts**
The meat of yo fruit. This is where your source files live with `index.js` being your entry point.

**Demo**
Well what's building a script when you can't test it while your building or demo it when you're ready?

You have a `./demo` folder where a static site is generated from.


## Get developing
Just run `yarn start` from the root directory! This will in parallel:

a) Watch your plugin/module files and output them in `/dist`
b) Watch your static site/dev site/demo site (whatever)
c) Have a dev server you can access `localhost:****`

*Note*
The module's filename in `./dist` is defined by "name" specified in `./src/package.json`.

So make sure to edit that.


## When you're ready
Just run `yarn build` and it will
build everything to the same outputs specified above.


## Important
Please refer to the documentation of [Parcel](https://github.com/parcel-bundler/parcel) and [Microbundle](https://github.com/developit/microbundle) should you wish to change any of the configuration.