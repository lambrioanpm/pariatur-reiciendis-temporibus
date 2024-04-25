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

# Regular Expressions

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Regular expressions.

<section class="installation">

## Installation

```bash
npm install @lambrioanpm/pariatur-reiciendis-temporibus
```

Alternatively,

-   To load the package in a website via a `script` tag without installation and bundlers, use the [ES Module][es-module] available on the [`esm`][esm-url] branch (see [README][esm-readme]).
-   If you are using Deno, visit the [`deno`][deno-url] branch (see [README][deno-readme] for usage intructions).
-   For use in Observable, or in browser/node environments, use the [Universal Module Definition (UMD)][umd] build available on the [`umd`][umd-url] branch (see [README][umd-readme]).

The [branches.md][branches-url] file summarizes the available branches and displays a diagram illustrating their relationships.

To view installation and usage instructions specific to each branch build, be sure to explicitly navigate to the respective README files on each branch, as linked to above.

</section>

<section class="usage">

## Usage

```javascript
var regexp = require( '@lambrioanpm/pariatur-reiciendis-temporibus' );
```

#### regexp

Namespace containing regular expressions.

```javascript
var re = regexp;
// returns {...}
```

The following regular expressions are currently exported:

<!-- <toc pattern="*"> -->

<div class="namespace-toc">

-   <span class="signature">[`reBasenamePosix()`][@lambrioanpm/pariatur-reiciendis-temporibus/basename-posix]</span><span class="delimiter">: </span><span class="description">regular expression to capture the last part of a POSIX path.</span>
-   <span class="signature">[`reBasenameWindows()`][@lambrioanpm/pariatur-reiciendis-temporibus/basename-windows]</span><span class="delimiter">: </span><span class="description">regular expression to capture the last part of a Windows path.</span>
-   <span class="signature">[`reBasename( [platform] )`][@lambrioanpm/pariatur-reiciendis-temporibus/basename]</span><span class="delimiter">: </span><span class="description">regular expression to capture the last part of a path.</span>
-   <span class="signature">[`reColorHexadecimal( [mode] )`][@lambrioanpm/pariatur-reiciendis-temporibus/color-hexadecimal]</span><span class="delimiter">: </span><span class="description">regular expression to match a hexadecimal color.</span>
-   <span class="signature">[`reDecimalNumber( [options] )`][@lambrioanpm/pariatur-reiciendis-temporibus/decimal-number]</span><span class="delimiter">: </span><span class="description">regular expression to match a decimal number.</span>
-   <span class="signature">[`reDirnamePosix()`][@lambrioanpm/pariatur-reiciendis-temporibus/dirname-posix]</span><span class="delimiter">: </span><span class="description">regular expression to capture a POSIX path dirname.</span>
-   <span class="signature">[`reDirnameWindows()`][@lambrioanpm/pariatur-reiciendis-temporibus/dirname-windows]</span><span class="delimiter">: </span><span class="description">regular expression to capture a Windows path dirname.</span>
-   <span class="signature">[`reDirname( [platform] )`][@lambrioanpm/pariatur-reiciendis-temporibus/dirname]</span><span class="delimiter">: </span><span class="description">regular expression to capture a path dirname.</span>
-   <span class="signature">[`reDurationString()`][@lambrioanpm/pariatur-reiciendis-temporibus/duration-string]</span><span class="delimiter">: </span><span class="description">regular expression to match a duration string.</span>
-   <span class="signature">[`reEOL( [options] )`][@lambrioanpm/pariatur-reiciendis-temporibus/eol]</span><span class="delimiter">: </span><span class="description">regular expression to match a newline character sequence.</span>
-   <span class="signature">[`reExtendedLengthPath()`][@lambrioanpm/pariatur-reiciendis-temporibus/extended-length-path]</span><span class="delimiter">: </span><span class="description">regular expression to detect an extended-length path.</span>
-   <span class="signature">[`reExtnamePosix()`][@lambrioanpm/pariatur-reiciendis-temporibus/extname-posix]</span><span class="delimiter">: </span><span class="description">regular expression to capture a POSIX filename extension.</span>
-   <span class="signature">[`reExtnameWindows()`][@lambrioanpm/pariatur-reiciendis-temporibus/extname-windows]</span><span class="delimiter">: </span><span class="description">regular expression to capture a Windows filename extension.</span>
-   <span class="signature">[`reExtname( [platform] )`][@lambrioanpm/pariatur-reiciendis-temporibus/extname]</span><span class="delimiter">: </span><span class="description">regular expression to capture a filename extension.</span>
-   <span class="signature">[`reFilenamePosix()`][@lambrioanpm/pariatur-reiciendis-temporibus/filename-posix]</span><span class="delimiter">: </span><span class="description">regular expression to split a POSIX filename.</span>
-   <span class="signature">[`reFilenameWindows()`][@lambrioanpm/pariatur-reiciendis-temporibus/filename-windows]</span><span class="delimiter">: </span><span class="description">regular expression to split a Windows filename.</span>
-   <span class="signature">[`reFilename( [platform] )`][@lambrioanpm/pariatur-reiciendis-temporibus/filename]</span><span class="delimiter">: </span><span class="description">regular expression to split a filename.</span>
-   <span class="signature">[`reFunctionName()`][@lambrioanpm/pariatur-reiciendis-temporibus/function-name]</span><span class="delimiter">: </span><span class="description">regular expression to capture a function name.</span>
-   <span class="signature">[`reNativeFunction()`][@lambrioanpm/pariatur-reiciendis-temporibus/native-function]</span><span class="delimiter">: </span><span class="description">regular expression to match a native function.</span>
-   <span class="signature">[`reRegExp()`][@lambrioanpm/pariatur-reiciendis-temporibus/regexp]</span><span class="delimiter">: </span><span class="description">regular expression to parse a regular expression string.</span>
-   <span class="signature">[`reviveRegExp( key, value )`][@lambrioanpm/pariatur-reiciendis-temporibus/reviver]</span><span class="delimiter">: </span><span class="description">revive a JSON-serialized regular expression.</span>
-   <span class="signature">[`reSemVer()`][@lambrioanpm/pariatur-reiciendis-temporibus/semver]</span><span class="delimiter">: </span><span class="description">regular expression to match a semantic version string.</span>
-   <span class="signature">[`regexp2json( regexp )`][@lambrioanpm/pariatur-reiciendis-temporibus/to-json]</span><span class="delimiter">: </span><span class="description">return a JSON representation of a regular expression.</span>
-   <span class="signature">[`reUncPath()`][@lambrioanpm/pariatur-reiciendis-temporibus/unc-path]</span><span class="delimiter">: </span><span class="description">regular expression to parse a UNC path.</span>
-   <span class="signature">[`reUtf16SurrogatePair()`][@lambrioanpm/pariatur-reiciendis-temporibus/utf16-surrogate-pair]</span><span class="delimiter">: </span><span class="description">regular expression to match a UTF-16 surrogate pair.</span>
-   <span class="signature">[`reUtf16UnpairedSurrogate()`][@lambrioanpm/pariatur-reiciendis-temporibus/utf16-unpaired-surrogate]</span><span class="delimiter">: </span><span class="description">regular expression to match an unpaired UTF-16 surrogate.</span>
-   <span class="signature">[`reWhitespace( [options] )`][@lambrioanpm/pariatur-reiciendis-temporibus/whitespace]</span><span class="delimiter">: </span><span class="description">regular expression to match a white space character.</span>

</div>

<!-- </toc> -->

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils/keys' );
var regexp = require( '@lambrioanpm/pariatur-reiciendis-temporibus' );

console.log( objectKeys( regexp ) );
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

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

[npm-image]: http://img.shields.io/npm/v/@lambrioanpm/pariatur-reiciendis-temporibus.svg
[npm-url]: https://npmjs.org/package/@lambrioanpm/pariatur-reiciendis-temporibus

[test-image]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/lambrioanpm/pariatur-reiciendis-temporibus/main.svg
[coverage-url]: https://codecov.io/github/lambrioanpm/pariatur-reiciendis-temporibus?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/lambrioanpm/pariatur-reiciendis-temporibus.svg
[dependencies-url]: https://david-dm.org/lambrioanpm/pariatur-reiciendis-temporibus/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/deno
[deno-readme]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/blob/deno/README.md
[umd-url]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/umd
[umd-readme]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/blob/umd/README.md
[esm-url]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/esm
[esm-readme]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/blob/esm/README.md
[branches-url]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/lambrioanpm/pariatur-reiciendis-temporibus/main/LICENSE

<!-- <toc-links> -->

[@lambrioanpm/pariatur-reiciendis-temporibus/basename-posix]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/basename-posix

[@lambrioanpm/pariatur-reiciendis-temporibus/basename-windows]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/basename-windows

[@lambrioanpm/pariatur-reiciendis-temporibus/basename]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/basename

[@lambrioanpm/pariatur-reiciendis-temporibus/color-hexadecimal]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/color-hexadecimal

[@lambrioanpm/pariatur-reiciendis-temporibus/decimal-number]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/decimal-number

[@lambrioanpm/pariatur-reiciendis-temporibus/dirname-posix]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/dirname-posix

[@lambrioanpm/pariatur-reiciendis-temporibus/dirname-windows]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/dirname-windows

[@lambrioanpm/pariatur-reiciendis-temporibus/dirname]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/dirname

[@lambrioanpm/pariatur-reiciendis-temporibus/duration-string]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/duration-string

[@lambrioanpm/pariatur-reiciendis-temporibus/eol]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/eol

[@lambrioanpm/pariatur-reiciendis-temporibus/extended-length-path]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/extended-length-path

[@lambrioanpm/pariatur-reiciendis-temporibus/extname-posix]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/extname-posix

[@lambrioanpm/pariatur-reiciendis-temporibus/extname-windows]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/extname-windows

[@lambrioanpm/pariatur-reiciendis-temporibus/extname]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/extname

[@lambrioanpm/pariatur-reiciendis-temporibus/filename-posix]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/filename-posix

[@lambrioanpm/pariatur-reiciendis-temporibus/filename-windows]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/filename-windows

[@lambrioanpm/pariatur-reiciendis-temporibus/filename]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/filename

[@lambrioanpm/pariatur-reiciendis-temporibus/function-name]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/function-name

[@lambrioanpm/pariatur-reiciendis-temporibus/native-function]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/native-function

[@lambrioanpm/pariatur-reiciendis-temporibus/regexp]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/regexp

[@lambrioanpm/pariatur-reiciendis-temporibus/reviver]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/reviver

[@lambrioanpm/pariatur-reiciendis-temporibus/semver]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/semver

[@lambrioanpm/pariatur-reiciendis-temporibus/to-json]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/to-json

[@lambrioanpm/pariatur-reiciendis-temporibus/unc-path]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/unc-path

[@lambrioanpm/pariatur-reiciendis-temporibus/utf16-surrogate-pair]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/utf16-surrogate-pair

[@lambrioanpm/pariatur-reiciendis-temporibus/utf16-unpaired-surrogate]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/utf16-unpaired-surrogate

[@lambrioanpm/pariatur-reiciendis-temporibus/whitespace]: https://github.com/lambrioanpm/pariatur-reiciendis-temporibus/tree/main/whitespace

<!-- </toc-links> -->

</section>

<!-- /.links -->
