<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# uppercaseKeys

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Convert each object key to uppercase.

<!-- Section to include introductory text. Make sure to keep an empty line after the intro `section` element and another before the `/section` close. -->

<section class="intro">

</section>

<!-- /.intro -->

<!-- Package usage documentation. -->



<section class="usage">

## Usage

```javascript
import uppercaseKeys from 'https://cdn.jsdelivr.net/gh/stdlib-js/utils-uppercase-keys@esm/index.mjs';
```
The previous example will load the latest bundled code from the esm branch. Alternatively, you may load a specific version by loading the file from one of the [tagged bundles](https://github.com/stdlib-js/utils-uppercase-keys/tags). For example,

```javascript
import uppercaseKeys from 'https://cdn.jsdelivr.net/gh/stdlib-js/utils-uppercase-keys@v0.2.0-esm/index.mjs';
```

#### uppercaseKeys( obj )

Converts each `object` key to uppercase, mapping the transformed keys to a new `object` having the same values.

```javascript
var obj1 = {
    'a': 1,
    'b': 2
};

var obj2 = uppercaseKeys( obj1 );
// returns { 'A': 1, 'B': 2 }
```

</section>

<!-- /.usage -->

<!-- Package usage notes. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="notes">

## Notes

-   The function only transforms **own** properties. Hence, the function does **not** transform inherited properties.
-   The function **shallow** copies key values.

</section>

<!-- /.notes -->

<!-- Package usage examples. -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="module">

import uppercaseKeys from 'https://cdn.jsdelivr.net/gh/stdlib-js/utils-uppercase-keys@esm/index.mjs';

var obj1 = {
    'a': 'beep',
    'b': 'boop',
    'c': 'foo',
    'd': 'bar'
};

var obj2 = uppercaseKeys( obj1 );

console.dir( obj2 );
// => { 'A': 'beep', 'B': 'boop', 'C': 'foo', 'D': 'bar' }

</script>
</body>
</html>
```

</section>

<!-- /.examples -->

<!-- Section to include cited references. If references are included, add a horizontal rule *before* the section. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="references">

</section>

<!-- /.references -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

* * *

## See Also

-   <span class="package-name">[`@stdlib/utils-capitalize-keys`][@stdlib/utils/capitalize-keys]</span><span class="delimiter">: </span><span class="description">convert the first letter of each object key to uppercase.</span>
-   <span class="package-name">[`@stdlib/utils-lowercase-keys`][@stdlib/utils/lowercase-keys]</span><span class="delimiter">: </span><span class="description">convert each object key to lowercase.</span>

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/utils-uppercase-keys.svg
[npm-url]: https://npmjs.org/package/@stdlib/utils-uppercase-keys

[test-image]: https://github.com/stdlib-js/utils-uppercase-keys/actions/workflows/test.yml/badge.svg?branch=v0.2.0
[test-url]: https://github.com/stdlib-js/utils-uppercase-keys/actions/workflows/test.yml?query=branch:v0.2.0

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/utils-uppercase-keys/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/utils-uppercase-keys?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/utils-uppercase-keys.svg
[dependencies-url]: https://david-dm.org/stdlib-js/utils-uppercase-keys/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/utils-uppercase-keys/tree/deno
[deno-readme]: https://github.com/stdlib-js/utils-uppercase-keys/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/utils-uppercase-keys/tree/umd
[umd-readme]: https://github.com/stdlib-js/utils-uppercase-keys/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/utils-uppercase-keys/tree/esm
[esm-readme]: https://github.com/stdlib-js/utils-uppercase-keys/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/utils-uppercase-keys/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/utils-uppercase-keys/main/LICENSE

<!-- <related-links> -->

[@stdlib/utils/capitalize-keys]: https://github.com/stdlib-js/utils-capitalize-keys/tree/esm

[@stdlib/utils/lowercase-keys]: https://github.com/stdlib-js/utils-lowercase-keys/tree/esm

<!-- </related-links> -->

</section>

<!-- /.links -->
