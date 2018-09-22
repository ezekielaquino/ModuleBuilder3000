# ModuleBuilder3000

Get started building your plugins, modules, and javascript based experiments smooth as butter.

This is basically a package that sets up [Microbundle](https://github.com/developit/microbundle) and [Parcel](https://github.com/parcel-bundler/parcel) for you. The only thing you gotta do is :sparkles:Start:sparkles:.


## The setup

**Scripts**

The meat of yo fruit. This is where your source files live with `index.js` being your entry point.

**Demo**

Well what's building a script when you can't test it while your building or demo it when you're ready?

💃 You have a `./demo` folder where a static site is generated from.


## Get developing
First you must clone this repository

```
  git clone git@github.com:ezekielaquino/ModuleBuilder3000.git yourDirectoryName
```

There are a couple of commands:

**From root**

`yarn dev`
Would watch your module source files, as well as your demo. This would start your dev server too so you can build and demo straight away.

`yarn start`
Would just watch and compile your module source files for changes

`yarn build`
Build your module code for production!

--

If you `cd` to `demo` you may also run the `start` and `build` scripts to do the same things described above for your demo site.


**Note**

The module's filename in `./dist` is defined by "name" specified in `./src/package.json`. Also make sure to edit necessary entries in `./package.json` (e.g. entry points)

Make sure to edit those!


## When you're ready
Just run `yarn build` and it will build everything to the same outputs specified above.

## Deployment
This comes with `gh-pages` as a dependency. Make sure that you have added the remote origin to your repo:

- `git init`
- `git remote add origin ssh@....`
- `cd demo` (the deploy script is in your demo folder!)
- `yarn deploy`

Deploying would build everything: your module, your demo site, and will push to `gh-pages` branch.

Note: If gh-pages isn't created yet, it will create on for you. Nice!


## Important
Please refer to the documentation of [Parcel](https://github.com/parcel-bundler/parcel) and [Microbundle](https://github.com/developit/microbundle) should you wish to change any of the configuration.