# Awesome Micro npm Packages [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of small, focused Node.js modules.

*Inspired by the <b><code>210891β­</code></b> <b><code>&nbsp;23848π΄</code></b> [awesome](https://github.com/sindresorhus/awesome) list thing.*


## Articles

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?π΄</code></b> [One-line node modules](https://github.com/sindresorhus/ama/issues/10)
* π [Build small single purpose modules](http://thenodeway.io/introduction/#build-small-single-purpose-modules)
* <b><code>&nbsp;&nbsp;1479β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;93π΄</code></b> [Module best practices](https://github.com/mattdesl/module-best-practices)
* π [Evaluating Packages Part 1 - Turn to community](http://bytearcher.com/articles/evaluating-packages-1-check-community/) 
* π [Evaluating Packages Part 2 - Review repository](http://bytearcher.com/articles/evaluating-packages-2-review-repository/)
* π [Small modules: itβs not quite that simple](https://medium.com/@Rich_Harris/small-modules-it-s-not-quite-that-simple-3ca532d65de4)
* π [In Defense of Hyper Modular JavaScript](https://medium.freecodecamp.com/in-defense-of-hyper-modular-javascript-33934c79e113)
* π [Tiny npm package: Guidelines to create a Node.js module following the small package philosophy](http://g14n.info/2015/12/tiny-npm-package/)
* π [The cost of small modules](https://nolanlawson.com/2016/08/15/the-cost-of-small-modules/)
* π [Why I think "micro-packages" are a good thing.](http://codetunnel.io/why-i-think-micro-packages-are-a-good-thing/)

## Modules

### Array

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;31π΄</code></b> [is-sorted](https://github.com/dcousens/is-sorted) - A small module to check if an Array is sorted.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12π΄</code></b> [array-first](https://github.com/jonschlinkert/array-first) - Get the first element or first n elements of an array.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13π΄</code></b> [array-last](https://github.com/jonschlinkert/array-last) - Return the last element in an array.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14π΄</code></b> [arr-flatten](https://github.com/jonschlinkert/arr-flatten) - Recursively flatten an array or arrays.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6π΄</code></b> [dedupe](https://github.com/seriousManual/dedupe) - Remove duplicates from an array.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6π΄</code></b> [array-range](https://github.com/mattdesl/array-range) - Creates a new array with given range.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;42β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17π΄</code></b> [arr-diff](https://github.com/jonschlinkert/arr-diff) - Returns an array with only the unique values from the first array, by excluding all values from additional arrays using strict equality for comparisons.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;40β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8π΄</code></b> [filled-array](https://github.com/sindresorhus/filled-array) - Returns an array filled with the specified input
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [map-array](https://github.com/parro-it/map-array) - Map object keys and values into an array.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2π΄</code></b> [in-array](https://github.com/jonschlinkert/in-array) - Return true if any of passed values exists in array - faster than using indexOf.
* <b><code>&nbsp;&nbsp;&nbsp;118β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9π΄</code></b> [unordered-array-remove](https://github.com/mafintosh/unordered-array-remove) - Efficiently remove an element from an unordered array without doing a splice.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4π΄</code></b> [array-swap](https://github.com/michaelzoidl/swap-array) - Swap position of two items in an array.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2π΄</code></b> [mirrarray](https://github.com/johnwquarles/mirrarray) - Creates a keymirror object from an array of valid keys.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;52β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14π΄</code></b> [group-array](https://github.com/doowb/group-array) - Group array of objects into lists.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [array.chunk](https://github.com/zhiyelee/array.chunk) - Split array/TypedArray to chunks of given size.

### String

* <b><code>&nbsp;&nbsp;&nbsp;217β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;26π΄</code></b> [decamelize](https://github.com/sindresorhus/decamelize) - Convert a camelized string into a lowercased one with a custom separator: unicornRainbow β unicorn_rainbow.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8π΄</code></b> [pad-left](https://github.com/jonschlinkert/pad-left) - Left pad a string with zeros or a specified string.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;37β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3π΄</code></b> [to-camel-case](https://github.com/ianstormtaylor/to-camel-case) - Convert a string to a camel case.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3π΄</code></b> [to-capital-case](https://github.com/ianstormtaylor/to-capital-case) - Convert a string to a capital case.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3π΄</code></b> [to-constant-case](https://github.com/ianstormtaylor/to-constant-case) - Convert a string to a constant case.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [to-dot-case](https://github.com/ianstormtaylor/to-dot-case) - Convert a string to a dot case.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5π΄</code></b> [to-no-case](https://github.com/ianstormtaylor/to-no-case) - Remove an existing case from a string.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [to-pascal-case](https://github.com/ianstormtaylor/to-pascal-case) - Convert a string to a pascal case.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [to-sentence-case](https://github.com/ianstormtaylor/to-sentence-case) - Convert a string to a sentence case.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;25β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4π΄</code></b> [to-snake-case](https://github.com/ianstormtaylor/to-snake-case) - Convert a string to a snake case.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3π΄</code></b> [to-space-case](https://github.com/ianstormtaylor/to-space-case) - Convert a string to a space case.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6π΄</code></b> [to-title-case](https://github.com/ianstormtaylor/to-title-case) - Convert a string to a title case.
* <b><code>&nbsp;&nbsp;1089β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94π΄</code></b> [node-slug](https://github.com/dodo/node-slug) - slugifies even utf-8 chars.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2π΄</code></b> [rtrim](https://github.com/sergejmueller/rtrim) - Strip whitespace - or other characters - from the end of a string.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2π΄</code></b> [slice.js](https://github.com/hustcc/slice.js) - Javascript library to enhance String.substring / Array.slice with python slice style.
* <b><code>&nbsp;&nbsp;&nbsp;331β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33π΄</code></b> [strip-ansi](https://github.com/chalk/strip-ansi) - Strip ANSI escape codes.
* <b><code>&nbsp;&nbsp;&nbsp;466β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54π΄</code></b> [striptags](https://github.com/ericnorris/striptags) - An implementation of PHP's strip_tags in Node.js.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [parse-next-json-value](https://github.com/ErikOnBike/parse-next-json-value) - Parse next JSON value from string allowing extraneous characters after value.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [pluralize](https://github.com/DaniAkash/pluralizer) - A very tiny library to pluralize words


### Date & Time

* <b><code>&nbsp;&nbsp;&nbsp;843β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58π΄</code></b> [pretty-ms](https://github.com/sindresorhus/pretty-ms) - Convert milliseconds to a human readable string: 1337000000 β 15d 11h 23m 20s.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2π΄</code></b> [hirestime](https://github.com/seriousManual/hirestime) - A wrapper around the built-in high resolution timer which simplifies the calculation of timestamps.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [periods](https://github.com/timruffles/periods) - Defined time-periods constants for Javascript, in milliseconds.
* <b><code>&nbsp;&nbsp;1985β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;139π΄</code></b> [fecha](https://github.com/taylorhakes/fecha) - Javascript Date formatting and parsing.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [akamai-time-reference](https://github.com/jucrouzet/akamai-time-reference) - Get reference time using Akamai's time reference service.
* <b><code>&nbsp;&nbsp;4799β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;405π΄</code></b> [timeago.js](https://github.com/hustcc/timeago.js) - A tiny(~1.7kb) library used to format date with `*** time ago` statement.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [count-days-in-month](https://github.com/shinnn/count-days-in-month) - Get the number of days in a given month.
* <b><code>&nbsp;&nbsp;&nbsp;109β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;17π΄</code></b> [time-stamp](https://github.com/jonschlinkert/time-stamp) - Get a formatted timestamp.
* <b><code>&nbsp;&nbsp;&nbsp;229β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9π΄</code></b> [twas](https://github.com/vutran/twas) - Generate a relative time string (Example: "3 seconds ago")

### Object

* <b><code>&nbsp;&nbsp;&nbsp;143β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;38π΄</code></b> [map-obj](https://github.com/sindresorhus/map-obj) - Map object keys and values into a new object.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;64β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5π΄</code></b> [filter-obj](https://github.com/sindresorhus/filter-obj) - Filter object keys and values into a new object.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5π΄</code></b> [object-values](https://github.com/sindresorhus/object-values) - Get the values of an object.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [object-pairs](https://github.com/eush77/object-pairs) - Turn an object into list of [key, value] pairs for mapping, iterating or other purposes.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [zipmap](https://github.com/landau/zipmap) - Returns a map with the keys mapped to the corresponding vals. zipmap also accepts a single value of objects or pairs.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2π΄</code></b> [just-pluck](https://github.com/jarofghosts/just-pluck) - Pluck without the madness.
* <b><code>&nbsp;&nbsp;&nbsp;687β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;108π΄</code></b> [deep-equal](https://github.com/substack/node-deep-equal) - Node's assert.deepEqual() algorithm as a standalone module.
* <b><code>&nbsp;&nbsp;&nbsp;248β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35π΄</code></b> [deep-assign](https://github.com/sindresorhus/deep-assign) - Recursive Object.assign().
* <b><code>&nbsp;&nbsp;&nbsp;246β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;43π΄</code></b> [set-value](https://github.com/jonschlinkert/set-value) - Create nested values and any intermediaries dot notation (`'a.b.c'`) paths.
* <b><code>&nbsp;&nbsp;&nbsp;213β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23π΄</code></b> [get-value](https://github.com/jonschlinkert/get-value) - Use property paths (a.b.c) to get a nested value from an object.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7π΄</code></b> [has-value](https://github.com/jonschlinkert/has-value) - Returns true if a value exists, false if empty. Works with deeply nested values using dot notation (`'a.b.c'`) paths.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2π΄</code></b> [has-key-deep](https://github.com/ryanaghdam/has-key-deep) - Deep-search objects for keys. Keys can be searched by providing an array of keys, or using a dot-notiation.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [flatkeys](https://github.com/ricardobeat/flatkeys) - Flatten object key hierarchies into a list of strings using a custom separator.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4π΄</code></b> [flatten-obj](https://github.com/watson/flatten-obj) - Converts an object literal with deeply nested nodes to a simple key/value object.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4π΄</code></b> [is-empty-object](https://github.com/gummesson/is-empty-object) - Check if an object is empty.
* <b><code>&nbsp;&nbsp;&nbsp;276β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;44π΄</code></b> [stringify-object](https://github.com/yeoman/stringify-object) - Stringify an object/array like JSON.stringify just without all the double-quotes.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;34β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4π΄</code></b> [sorted-object](https://github.com/domenic/sorted-object) - Returns a copy of an object with its keys sorted.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [static-props](https://github.com/fibo/static-props) - Defines static object attributes using `Object.defineProperties`
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [missing-deep-keys](https://github.com/vladgolubev/missing-deep-keys) - Returns an array of keys from first object that are missing in second.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [has-own-property](https://github.com/LinusU/has-own-property) - Check if an object has a local property. 
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [merge-objects](https://github.com/shevaroller/node-merge-objects) - Deep-merge two objects. Arrays that are values of the same object key get concatenated.
* <b><code>&nbsp;&nbsp;&nbsp;779β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75π΄</code></b> [deep-object-diff](https://github.com/mattphillips/deep-object-diff) - Deep diff two JavaScript Objects while preserving the data structure. Including nested structures of Arrays and Objects.

### Function

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3π΄</code></b> [compose-function](https://github.com/stoeffel/compose-function) - Compose a new function from smaller functions `f(g(x))`.
* <b><code>&nbsp;&nbsp;&nbsp;314β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;23π΄</code></b> [curry](https://github.com/dominictarr/curry) - A curry function without anything too clever.
* <b><code>&nbsp;&nbsp;&nbsp;207β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;24π΄</code></b> [once](https://github.com/isaacs/once) - Run a function exactly one time.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;8β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2π΄</code></b> [deep-bind](https://github.com/jonschlinkert/deep-bind) - Bind a context to all functions in an object, including deeply nested functions.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4π΄</code></b> [identity-function](https://github.com/substack/identity-function) - Always return the input argument. 
* <b><code>&nbsp;&nbsp;&nbsp;966β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;51π΄</code></b> [mem](https://github.com/sindresorhus/mem) - An optimization technique used to speed up consecutive function calls by caching the result of calls with identical input.
* <b><code>&nbsp;&nbsp;&nbsp;858β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;100π΄</code></b> [throttle-debounce](https://github.com/niksy/throttle-debounce) - Throttle/debounce your functions.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;45β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2π΄</code></b> [compose-tiny](https://github.com/hipstersmoothie/compose-tiny) - A very tiny and fast compose function.

### Math

* <b><code>&nbsp;&nbsp;&nbsp;163β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15π΄</code></b> [is-even](https://github.com/jonschlinkert/is-even) - A good way to tell if a number is even or not (avoids type issues). Uses `is-odd` and `is-number` under the hood.
* <b><code>&nbsp;&nbsp;&nbsp;210β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39π΄</code></b> [is-number](https://github.com/jonschlinkert/is-number) - Returns `true` if the value is a number.
* <b><code>&nbsp;&nbsp;&nbsp;222β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;74π΄</code></b> [is-odd](https://github.com/jonschlinkert/is-odd) - A good way to tell if a number is odd or not (avoids type issues). Uses `is-number` under the hood.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [easy-math.js](https://github.com/kingzez/easy-math.js) - A tiny easy math library including addition, multiplication, subtraction, and division.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [my-prime](https://github.com/jinnatul/my-prime) - A good way to tell if a number is prime or not.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [fun-gcd](https://github.com/zubayerhimel/fun-gcd) - A tiny math library to get gcd of two numbers using Euclidean algorithm

### Stream
* <b><code>&nbsp;&nbsp;1870β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;125π΄</code></b> [through2](https://github.com/rvagg/through2) - Tiny wrapper around Node streams2 Transform to avoid explicit subclassing noise.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;35β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4π΄</code></b> [through2-filter](https://github.com/brycebaril/through2-filter) - A through2 to create an Array.prototype.filter analog for streams.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;70β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3π΄</code></b> [through2-map](https://github.com/brycebaril/through2-map) - A through2 to create an Array.prototype.map analog for streams.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [stream-spigot](https://github.com/brycebaril/node-stream-spigot) - A readable stream generator, useful for testing or converting simple functions into Readable streams.
* <b><code>&nbsp;&nbsp;&nbsp;561β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;62π΄</code></b> [concat-stream](https://github.com/maxogden/concat-stream) - writable stream that concatenates strings or data and calls a callback with the result.
* <b><code>&nbsp;&nbsp;1860β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;171π΄</code></b> [JSONStream](https://github.com/dominictarr/JSONStream) - streaming JSON.parse and stringify
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [through2-map-promise](https://github.com/RangerMauve/through2-map-promise) - A small promise-based wrapper for through2.
* <b><code>&nbsp;&nbsp;&nbsp;875β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;54π΄</code></b> [pump](https://github.com/mafintosh/pump) - pipe streams together and close all of them if one of them closes.
* <b><code>&nbsp;&nbsp;&nbsp;344β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;39π΄</code></b> [split](https://github.com/dominictarr/split) - Break up a stream and reassemble it so that each line is a chunk.
* <b><code>&nbsp;&nbsp;&nbsp;105β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;21π΄</code></b> [is-stream](https://github.com/sindresorhus/is-stream) - Check if something is a Node.js stream.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;77β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;12π΄</code></b> [syncthrough](https://github.com/mcollina/syncthrough) - Transform your data as it pass by, synchronously.


### Promise

* <b><code>&nbsp;&nbsp;1455β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;86π΄</code></b> [pify](https://github.com/sindresorhus/pify) - Promisify a callback-style function.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2π΄</code></b> [promise-all-props](https://github.com/Siilwyn/promise-all-props) - Like `Promise.all` but for object properties.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;75β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;10π΄</code></b> [sleep-promise](https://github.com/brummelte/sleep-promise) - Resolves a promise after a specified delay.
* <b><code>&nbsp;&nbsp;&nbsp;273β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;33π΄</code></b> [is-promise](https://github.com/then/is-promise) - Test whether an object looks like a promises-a+ promise.

### Data Structure

* <b><code>&nbsp;&nbsp;&nbsp;109β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2π΄</code></b> [quetie](https://github.com/TomerAberbach/quetie) - Just the cutest and tiniest queue/deque implementation!

### File System

* <b><code>&nbsp;&nbsp;4776β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;242π΄</code></b> [rimraf](https://github.com/isaacs/rimraf) - A deep deletion module for node (like rm -rf).
* <b><code>&nbsp;&nbsp;2281β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;227π΄</code></b> [mkdirp](https://github.com/substack/node-mkdirp) - Recursively mkdir, like mkdir -p.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;29β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9π΄</code></b> [du](https://github.com/rvagg/node-du) - A simple JavaScript implementation of du -sb.
* <b><code>&nbsp;&nbsp;&nbsp;230β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11π΄</code></b> [file-size](https://github.com/Nijikokun/file-size) - Lightweight filesize to human-readable / proportions w/o dependencies.
* <b><code>&nbsp;&nbsp;&nbsp;680β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;94π΄</code></b> [tmp](https://github.com/raszi/node-tmp) - Temporary file and directory creator for node.js.
* <b><code>&nbsp;&nbsp;&nbsp;171β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11π΄</code></b> [fs-promise](https://github.com/kevinbeaty/fs-promise) - Node fs methods as Promise/A+ (optional fs-extra, graceful-fs).
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [read-git-user](https://github.com/RocktimSaikia/read-git-user) - Reads the username and email from `.gitconfig` :wrench: and returns it as json object.

### Browser

* <b><code>&nbsp;&nbsp;&nbsp;176β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;30π΄</code></b> [delegate](https://github.com/zenorocha/delegate) - Lightweight event delegation.
* <b><code>&nbsp;&nbsp;&nbsp;246β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;57π΄</code></b> [insert-css](https://github.com/substack/insert-css) - Insert a string of css into the head
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;6β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [dom-element-value](https://github.com/crysalead-js/dom-element-value) - DOM element value getter/setter.
* <b><code>&nbsp;&nbsp;&nbsp;139β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14π΄</code></b> [image-promise](https://github.com/bfred-it/image-promise) - Load one or more `<img>`s in a Promise.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;11β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [get-media-size](https://github.com/bfred-it/get-media-size) - Get the original size of any `img`/`video`/`svg`/`canvas` tags or canvas context.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;58β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3π΄</code></b> [document-ready](https://github.com/bendrucker/document-ready) - Document ready listener for modern browsers.
* <b><code>&nbsp;&nbsp;&nbsp;127β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4π΄</code></b> [copee](https://github.com/styfle/copee) - Copy text from browser to clipboard...natively!

### Semver

* <b><code>&nbsp;&nbsp;4257β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;436π΄</code></b> [semver](https://github.com/npm/node-semver) - The semantic version parser used by npm.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [semver-max](https://github.com/eush77/semver-max) - Find maximum (or minimum) version according to semver.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [semver-first-satisfied](https://github.com/parro-it/semver-first-satisfied) - Find minimum in an array of version that satisfies a semver range.



### CLI

* <b><code>&nbsp;&nbsp;&nbsp;148β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;41π΄</code></b> [abbrev](https://github.com/isaacs/abbrev-js) - Calculate the set of unique abbreviations for a given set of strings.
* <b><code>&nbsp;&nbsp;7591β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;484π΄</code></b> [glob](https://github.com/isaacs/node-glob) - Glob functionality for node.js.
* <b><code>&nbsp;&nbsp;&nbsp;141β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;16π΄</code></b> [username](https://github.com/sindresorhus/username) - Get the username of the current user.
* <b><code>&nbsp;&nbsp;5257β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;303π΄</code></b> [minimist](https://github.com/substack/minimist) - Parse argument options.
* <b><code>&nbsp;&nbsp;&nbsp;123β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;14π΄</code></b> [png-to-ico](https://github.com/steambap/png-to-ico) - Convert png to windows ico format.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [help-version](https://github.com/eush77/help-version) - Easily handle --help and --version arguments in your CLI application

### Module management

* <b><code>&nbsp;&nbsp;&nbsp;116β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;13π΄</code></b> [pkg-conf](https://github.com/sindresorhus/pkg-conf) - Get namespaced config from the closest package.json.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;18β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2π΄</code></b> [normalize-pkg](https://github.com/jonschlinkert/normalize-pkg) - Normalize values in package.json to improve compatibility, programmatic readability and usefulness with third party libs.

### Generators

* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;15β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5π΄</code></b> [is-generator](https://github.com/blakeembrey/is-generator) - Check whether a given value is a generator function.

### Other

* <b><code>&nbsp;12437β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;832π΄</code></b> [uuid](https://github.com/kelektiv/node-uuid) - Generate RFC-compliant UUIDs in JavaScript.
* <b><code>&nbsp;&nbsp;1841β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;310π΄</code></b> [node-mime](https://github.com/broofa/node-mime) - Comprehensive MIME type mapping API based on mime-db module.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3π΄</code></b> [not-defined](https://github.com/fibo/not-defined) - Checks if foo is not defined, i.e. undefined, null, an empty string, array or object.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;20β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [is-fqdn](https://github.com/parro-it/is-fqdn) - Check if a string represent a fully qualified domain name.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0π΄</code></b> [shurley](https://github.com/BrunoBernardino/shurley) - Parses URLs from user input (with potential typos in protocols, bad copy+paste, etc.) and returns a proper URL.
* <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1π΄</code></b> [mime-type-check](https://github.com/RocktimSaikia/mime-type-check) - Get the MIME type of a file by its extension.

## Related lists

This section contains awesome lists that you may find useful if you use or write small NPM modules.

* <b><code>&nbsp;45663β­</code></b> <b><code>&nbsp;&nbsp;5406π΄</code></b> [awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) - A curated list of delightful Node.js packages and resources.
* <b><code>&nbsp;&nbsp;4026β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;252π΄</code></b> [awesome-npm](https://github.com/sindresorhus/awesome-npm) - Awesome npm resources and tips.

## Small modules rockstars to follow

These people are used to develop awesome NPM modules that follows the single responsibility philosophy.
Follow them to discover new great modules:

[![Sindre Sorhus](https://avatars.githubusercontent.com/u/170270?s=130)](https://github.com/sindresorhus) | [![James Halliday](https://avatars1.githubusercontent.com/u/12631?s=130)](https://github.com/substack) | [![Eugene Sharygin](https://avatars3.githubusercontent.com/u/4472489?s=130)](https://github.com/eush77) | [![Isaac Z. Schlueter](https://avatars3.githubusercontent.com/u/9287?s=130)](https://github.com/isaacs) | [![Jon Schlinkert](https://avatars1.githubusercontent.com/u/383994?s=130)](https://github.com/jonschlinkert) | [![Dominic Tarr](https://avatars3.githubusercontent.com/u/259374?s=130)](https://github.com/dominictarr)
---|---|---|---|---|--- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?π΄</code></b> [Sindre Sorhus](https://github.com/sindresorhus) | <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?π΄</code></b> [James Halliday](https://github.com/substack) | <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?π΄</code></b> [Eugene Sharygin](https://github.com/eush77) | <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?π΄</code></b> [Isaac Z. Schlueter](https://github.com/isaacs) | <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?π΄</code></b> [Jon Schlinkert](https://github.com/jonschlinkert) | <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?π΄</code></b> [Dominic Tarr](https://github.com/dominictarr)

[![Rod Vagg](https://avatars0.githubusercontent.com/u/495647?s=130)](https://github.com/rvagg) | [![Max Ogden](https://avatars3.githubusercontent.com/u/39759?s=130)](https://github.com/maxogden) | [![Brian Woodward](https://avatars1.githubusercontent.com/u/995160?s=130)](https://github.com/doowb)
---|---|--- <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?π΄</code></b> [Rod Vagg](https://github.com/rvagg) | <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?π΄</code></b> [Max Ogden](https://github.com/maxogden) | <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?π΄</code></b> [Brian Woodward](https://github.com/doowb)


## Contribute

Contributions welcome! Read the π [contribution guidelines](contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?β­</code></b> <b><code>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;?π΄</code></b> [Andrea Parodi](https://github.com/parro-it) has waived all copyright and related or neighboring rights to this work.
