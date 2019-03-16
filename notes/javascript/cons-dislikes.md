# Cons/Dislikes

* No conventions.
* Not standardized.
* No consistency in online resources.
  * Lots of outdated online resources.
  * The fact that AirBNB has 20 pages on how to write JavaScript is insane.
* No first class Enums
* No types. Can be handled by [Flow](https://github.com/facebook/flow) or [TypeScript](https://www.typescriptlang.org)
* Callback hell \(work around with Promises, `async` and `await`, but its not supported everywhere\)
* Inconsisent: `Array.length` vs `Set.size`
  * Like wtf?
* All the problems of a loosely typed language.
  * Hard to scale as a language, due to no types.
  * Hard to refactor.
* Inconsistencies in coding style amongst the community
* JS Modules are confusing
* Requires high code coverage due to inconsistencies.
* Changing `babel` flags can make your code run differently
  * Requires high code coverage to ensure it does as expected.
* You need tools like `lodash` for basic stuff \(bucketing items in in an array, `groupBy`\)
* Requires a lot of tooling to maintain JavaScript
* Was design for client side browsing, not server side
* It has both `null` and `undefined`
* No native `sprintf`
* Browser support is inconsistent.
  * I ran into a problem with fetch\(\) not being supported. [https://github.com/github/fetch\#browser-support](https://github.com/github/fetch#browser-support)
* Requires a lot of static analysis tools.
  * jshint [http://jshint.com/about/](http://jshint.com/about/) 
  * flow
