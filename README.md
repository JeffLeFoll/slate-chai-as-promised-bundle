# slate-chai-as-promised-bundle
Bundled version of the chai plugin *[chai-as-promised](https://github.com/domenic/chai-as-promised)* to be usefull in polymer web component tests.
*chai-as-promised* extends Chai with a fluent language for asserting facts about promises.

## Installation

Add the dependency to the `bower.json` of your application:

```
   "devDependencies": {
     [...]
     "slate-chai-as-promised-bundle": "slate-chai-as-promised-bundle#1.0.0"
   }
``` 

And then recover them via `bower install`.


## Usage

Add the foloowing import in you element .html test file:

`<script src="../bower_components/slate-chai-as-promised-bundle/slate-chaiAsPromised-bundle.js"></script>`

We take care of the `chai.use(chaiAsPromised)` so you juste have to import the script.


## Generating the elements

You need to do a `npm install` to recover the rependencies and then `npm run generate` to execute the script.

```
$ npm run generate
```

After executing it, a new .js file (*slate-chaiAsPromised-bundle.js*) wil be created in the root directory.


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## Credits

This work is a re-package of Domenic Denicola's work : [chai-as-promised](https://github.com/domenic/chai-as-promised) to be used in browser without tooling.


## License

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0)