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

# Path Delimiter

> Windows path delimiter.

<section class="installation">

## Installation

```bash
npm install @stdlib/constants-path-delimiter-win32
```

</section>

<section class="usage">

## Usage

```javascript
var PATH_DELIMITER_WIN32 = require( '@stdlib/constants-path-delimiter-win32' );
```

#### PATH_DELIMITER_WIN32

Windows path delimiter.

```javascript
var delimiter = PATH_DELIMITER_WIN32;
// returns ';'
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- eslint no-undef: "error" -->

```javascript
var PATH_DELIMITER_WIN32 = require( '@stdlib/constants-path-delimiter-win32' );

var PATH = 'C:\\Windows\\system32;C:\\Windows;C:\\Program Files\\node\\';
var paths = PATH.split( PATH_DELIMITER_WIN32 );
// returns ['C:\\Windows\\system32','C:\\Windows','C:\\Program Files\\node\\']
```

</section>

<!-- /.examples -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/constants-path-delimiter-win32/main/LICENSE

</section>

<!-- /.links -->
