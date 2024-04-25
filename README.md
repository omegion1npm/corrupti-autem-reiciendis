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

# Arrays

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Arrays.

<section class="installation">

## Installation

```bash
npm install @omegion1npm/corrupti-autem-reiciendis
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
var ns = require( '@omegion1npm/corrupti-autem-reiciendis' );
```

#### ns

Arrays.

```javascript
var o = ns;
// returns {...}
```

The namespace exports the following array constructors:

<!-- <toc pattern="+(int*|float*|uint*|*buffer)"> -->

<div class="namespace-toc">

-   <span class="signature">[`ArrayBuffer( size )`][@omegion1npm/corrupti-autem-reiciendis/buffer]</span><span class="delimiter">: </span><span class="description">constructor which returns an object used to represent a generic, fixed-length raw binary data buffer.</span>
-   <span class="signature">[`Float32Array()`][@omegion1npm/corrupti-autem-reiciendis/float32]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of single-precision floating-point numbers in the platform byte order.</span>
-   <span class="signature">[`Float64Array()`][@omegion1npm/corrupti-autem-reiciendis/float64]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of double-precision floating-point numbers in the platform byte order.</span>
-   <span class="signature">[`Int16Array()`][@omegion1npm/corrupti-autem-reiciendis/int16]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of twos-complement 16-bit signed integers in the platform byte order.</span>
-   <span class="signature">[`Int32Array()`][@omegion1npm/corrupti-autem-reiciendis/int32]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of twos-complement 32-bit signed integers in the platform byte order.</span>
-   <span class="signature">[`Int8Array()`][@omegion1npm/corrupti-autem-reiciendis/int8]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of twos-complement 8-bit signed integers in the platform byte order.</span>
-   <span class="signature">[`SharedArrayBuffer( size )`][@omegion1npm/corrupti-autem-reiciendis/shared-buffer]</span><span class="delimiter">: </span><span class="description">constructor returning an object used to represent a generic, fixed-length raw binary data buffer which can be used to create views of shared memory.</span>
-   <span class="signature">[`Uint16Array()`][@omegion1npm/corrupti-autem-reiciendis/uint16]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of 16-bit unsigned integers in the platform byte order.</span>
-   <span class="signature">[`Uint32Array()`][@omegion1npm/corrupti-autem-reiciendis/uint32]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of 32-bit unsigned integers in the platform byte order.</span>
-   <span class="signature">[`Uint8Array()`][@omegion1npm/corrupti-autem-reiciendis/uint8]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of 8-bit unsigned integers in the platform byte order.</span>
-   <span class="signature">[`Uint8ClampedArray()`][@omegion1npm/corrupti-autem-reiciendis/uint8c]</span><span class="delimiter">: </span><span class="description">typed array constructor which returns a typed array representing an array of 8-bit unsigned integers in the platform byte order clamped to 0-255.</span>

</div>

<!-- </toc> -->

```javascript
var arr = new ns.Int32Array( 5 );
// returns <Int32Array>[ 0, 0, 0, 0, 0 ]
```

Alternatively, use the `typedarray` function to create a typed array of a given data type:

<!-- <toc pattern="typed"> -->

<div class="namespace-toc">

-   <span class="signature">[`typedarray()`][@omegion1npm/corrupti-autem-reiciendis/typed]</span><span class="delimiter">: </span><span class="description">create a typed array.</span>

</div>

<!-- </toc> -->

```javascript
var arr1 = ns.typedarray( 5 );
// returns <Float64Array>[ 0.0, 0.0, 0.0, 0.0, 0.0 ]

var arr2 = ns.typedarray( 5, 'uint8' );
// returns <Uint8Array>[ 0, 0, 0, 0, 0 ]
```

The namespace contains functions to create arrays pre-filled with spaced values:

<!-- <toc pattern="*space"> -->

<div class="namespace-toc">

-   <span class="signature">[`datespace( start, stop[, length][, opts] )`][@omegion1npm/corrupti-autem-reiciendis/datespace]</span><span class="delimiter">: </span><span class="description">generate an array of linearly spaced dates.</span>
-   <span class="signature">[`incrspace( start, stop[, increment] )`][@omegion1npm/corrupti-autem-reiciendis/incrspace]</span><span class="delimiter">: </span><span class="description">generate a linearly spaced numeric array using a provided increment.</span>
-   <span class="signature">[`linspace( start, stop, length[, options] )`][@omegion1npm/corrupti-autem-reiciendis/linspace]</span><span class="delimiter">: </span><span class="description">generate a linearly spaced array over a specified interval.</span>
-   <span class="signature">[`logspace( a, b[, length] )`][@omegion1npm/corrupti-autem-reiciendis/logspace]</span><span class="delimiter">: </span><span class="description">generate a logarithmically spaced numeric array.</span>

</div>

<!-- </toc> -->

You can use the following functions to retrieve a list of available data types:

<!-- <toc pattern="*dtypes"> -->

<div class="namespace-toc">

-   <span class="signature">[`dtypes( [kind] )`][@omegion1npm/corrupti-autem-reiciendis/dtypes]</span><span class="delimiter">: </span><span class="description">list of array data types.</span>
-   <span class="signature">[`complexarrayDataTypes()`][@omegion1npm/corrupti-autem-reiciendis/typed-complex-dtypes]</span><span class="delimiter">: </span><span class="description">list of complex typed array data types.</span>
-   <span class="signature">[`typedarrayDataTypes()`][@omegion1npm/corrupti-autem-reiciendis/typed-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array data types.</span>
-   <span class="signature">[`floatarrayDataTypes()`][@omegion1npm/corrupti-autem-reiciendis/typed-float-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array floating-point data types.</span>
-   <span class="signature">[`intarrayDataTypes()`][@omegion1npm/corrupti-autem-reiciendis/typed-integer-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array integer data types.</span>
-   <span class="signature">[`realarrayDataTypes()`][@omegion1npm/corrupti-autem-reiciendis/typed-real-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array real-valued data types.</span>
-   <span class="signature">[`realarrayFloatDataTypes()`][@omegion1npm/corrupti-autem-reiciendis/typed-real-float-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array real-valued floating-point data types.</span>
-   <span class="signature">[`intarraySignedDataTypes()`][@omegion1npm/corrupti-autem-reiciendis/typed-signed-integer-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array signed integer data types.</span>
-   <span class="signature">[`intarrayUnsignedDataTypes()`][@omegion1npm/corrupti-autem-reiciendis/typed-unsigned-integer-dtypes]</span><span class="delimiter">: </span><span class="description">list of typed array unsigned integer data types.</span>

</div>

<!-- </toc> -->

Furthermore, the namespace contains utility functions to retrieve a given constructor:

<!-- <toc keywords="+constructors,+constructor"> -->

<div class="namespace-toc">

-   <span class="signature">[`ctors( dtype )`][@omegion1npm/corrupti-autem-reiciendis/ctors]</span><span class="delimiter">: </span><span class="description">array constructors.</span>
-   <span class="signature">[`ArrayIndex( x[, options] )`][@omegion1npm/corrupti-autem-reiciendis/index]</span><span class="delimiter">: </span><span class="description">array index constructor.</span>
-   <span class="signature">[`complexarrayCtors( dtype )`][@omegion1npm/corrupti-autem-reiciendis/typed-complex-ctors]</span><span class="delimiter">: </span><span class="description">complex typed array constructors.</span>
-   <span class="signature">[`typedarrayCtors( dtype )`][@omegion1npm/corrupti-autem-reiciendis/typed-ctors]</span><span class="delimiter">: </span><span class="description">typed array constructors.</span>
-   <span class="signature">[`floatarrayCtors( dtype )`][@omegion1npm/corrupti-autem-reiciendis/typed-float-ctors]</span><span class="delimiter">: </span><span class="description">floating-point typed array constructors.</span>
-   <span class="signature">[`intarrayCtors( dtype )`][@omegion1npm/corrupti-autem-reiciendis/typed-integer-ctors]</span><span class="delimiter">: </span><span class="description">integer-valued typed array constructors.</span>
-   <span class="signature">[`realarrayCtors( dtype )`][@omegion1npm/corrupti-autem-reiciendis/typed-real-ctors]</span><span class="delimiter">: </span><span class="description">typed array constructors.</span>
-   <span class="signature">[`realarrayFloatCtors( dtype )`][@omegion1npm/corrupti-autem-reiciendis/typed-real-float-ctors]</span><span class="delimiter">: </span><span class="description">real-valued floating-point typed array constructors.</span>
-   <span class="signature">[`intarraySignedCtors( dtype )`][@omegion1npm/corrupti-autem-reiciendis/typed-signed-integer-ctors]</span><span class="delimiter">: </span><span class="description">signed integer typed array constructors.</span>
-   <span class="signature">[`intarrayUnsignedCtors( dtype )`][@omegion1npm/corrupti-autem-reiciendis/typed-unsigned-integer-ctors]</span><span class="delimiter">: </span><span class="description">unsigned integer typed array constructors.</span>

</div>

<!-- </toc> -->

```javascript
var ctor = ns.typedarrayCtors( 'float64' );
// returns <Function>

ctor = ns.typedarrayCtors( 'int' );
// returns null
```

Lastly, the namespace contains various other functions for dealing with arrays, including functions to convert arrays from one data type to another or to serialize them as JSON and vice versa.

<!-- <toc ignore="+(int*|float*|uint*|*buffer)" ignore="typed" ignore="*dtypes" keywords="-constructors,-constructor"> -->

<div class="namespace-toc">

-   <span class="signature">[`base`][@omegion1npm/corrupti-autem-reiciendis/base]</span><span class="delimiter">: </span><span class="description">base (i.e., lower-level) array utilities.</span>
-   <span class="signature">[`cartesianPower( x, n )`][@omegion1npm/corrupti-autem-reiciendis/cartesian-power]</span><span class="delimiter">: </span><span class="description">return the Cartesian power.</span>
-   <span class="signature">[`cartesianProduct( x1, x2 )`][@omegion1npm/corrupti-autem-reiciendis/cartesian-product]</span><span class="delimiter">: </span><span class="description">return the Cartesian product.</span>
-   <span class="signature">[`cartesianSquare( x )`][@omegion1npm/corrupti-autem-reiciendis/cartesian-square]</span><span class="delimiter">: </span><span class="description">return the Cartesian square.</span>
-   <span class="signature">[`Complex128Array()`][@omegion1npm/corrupti-autem-reiciendis/complex128]</span><span class="delimiter">: </span><span class="description">128-bit complex number array.</span>
-   <span class="signature">[`Complex64Array()`][@omegion1npm/corrupti-autem-reiciendis/complex64]</span><span class="delimiter">: </span><span class="description">64-bit complex number array.</span>
-   <span class="signature">[`convertSame( x, y )`][@omegion1npm/corrupti-autem-reiciendis/convert-same]</span><span class="delimiter">: </span><span class="description">convert an array to the same data type as a second input array.</span>
-   <span class="signature">[`convert( arr, dtype )`][@omegion1npm/corrupti-autem-reiciendis/convert]</span><span class="delimiter">: </span><span class="description">convert an array to an array of a different data type.</span>
-   <span class="signature">[`DataView( buffer[, byteOffset[, byteLength]] )`][@omegion1npm/corrupti-autem-reiciendis/dataview]</span><span class="delimiter">: </span><span class="description">constructor which returns a data view representing a provided array buffer.</span>
-   <span class="signature">[`defaults()`][@omegion1npm/corrupti-autem-reiciendis/defaults]</span><span class="delimiter">: </span><span class="description">default array settings.</span>
-   <span class="signature">[`dtype( array )`][@omegion1npm/corrupti-autem-reiciendis/dtype]</span><span class="delimiter">: </span><span class="description">return the data type of an array.</span>
-   <span class="signature">[`emptyLike( x[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/empty-like]</span><span class="delimiter">: </span><span class="description">create an uninitialized array having the same length and data type as a provided array.</span>
-   <span class="signature">[`empty( length[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/empty]</span><span class="delimiter">: </span><span class="description">create an uninitialized array having a specified length.</span>
-   <span class="signature">[`filledBy()`][@omegion1npm/corrupti-autem-reiciendis/filled-by]</span><span class="delimiter">: </span><span class="description">create a filled array according to a provided callback function.</span>
-   <span class="signature">[`filled()`][@omegion1npm/corrupti-autem-reiciendis/filled]</span><span class="delimiter">: </span><span class="description">create a filled array.</span>
-   <span class="signature">[`iterator2array( iterator[, out][, mapFcn[, thisArg]] )`][@omegion1npm/corrupti-autem-reiciendis/from-iterator]</span><span class="delimiter">: </span><span class="description">create (or fill) an array from an iterator.</span>
-   <span class="signature">[`scalar2array( value[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/from-scalar]</span><span class="delimiter">: </span><span class="description">create a single-element array containing a provided scalar value.</span>
-   <span class="signature">[`fullLike( x, value[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/full-like]</span><span class="delimiter">: </span><span class="description">create a filled array having the same length and data type as a provided array.</span>
-   <span class="signature">[`full( length, value[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/full]</span><span class="delimiter">: </span><span class="description">create a filled array having a specified length.</span>
-   <span class="signature">[`minDataType( value )`][@omegion1npm/corrupti-autem-reiciendis/min-dtype]</span><span class="delimiter">: </span><span class="description">determine the minimum array data type of the closest "kind" necessary for storing a provided scalar value.</span>
-   <span class="signature">[`mostlySafeCasts( [dtype] )`][@omegion1npm/corrupti-autem-reiciendis/mostly-safe-casts]</span><span class="delimiter">: </span><span class="description">return a list of array data types to which a provided array data type can be safely cast and, for floating-point data types, can be downcast.</span>
-   <span class="signature">[`mskfilter( x, mask )`][@omegion1npm/corrupti-autem-reiciendis/mskfilter]</span><span class="delimiter">: </span><span class="description">apply a mask to a provided input array.</span>
-   <span class="signature">[`mskreject( x, mask )`][@omegion1npm/corrupti-autem-reiciendis/mskreject]</span><span class="delimiter">: </span><span class="description">apply a mask to a provided input array.</span>
-   <span class="signature">[`nansLike( x[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/nans-like]</span><span class="delimiter">: </span><span class="description">create an array filled with NaNs and having the same length and data type as a provided array.</span>
-   <span class="signature">[`nans( length[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/nans]</span><span class="delimiter">: </span><span class="description">create an array filled with NaNs and having a specified length.</span>
-   <span class="signature">[`nextDataType( [dtype] )`][@omegion1npm/corrupti-autem-reiciendis/next-dtype]</span><span class="delimiter">: </span><span class="description">return the next larger array data type of the same kind.</span>
-   <span class="signature">[`oneToLike( x[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/one-to-like]</span><span class="delimiter">: </span><span class="description">generate a linearly spaced numeric array whose elements increment by `1` starting from one and having the same length and data type as a provided input array.</span>
-   <span class="signature">[`oneTo( n[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/one-to]</span><span class="delimiter">: </span><span class="description">generate a linearly spaced numeric array whose elements increment by `1` starting from one.</span>
-   <span class="signature">[`onesLike( x[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/ones-like]</span><span class="delimiter">: </span><span class="description">create an array filled with ones and having the same length and data type as a provided array.</span>
-   <span class="signature">[`ones( length[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/ones]</span><span class="delimiter">: </span><span class="description">create an array filled with ones and having a specified length.</span>
-   <span class="signature">[`typedarraypool()`][@omegion1npm/corrupti-autem-reiciendis/pool]</span><span class="delimiter">: </span><span class="description">allocate typed arrays from a typed array memory pool.</span>
-   <span class="signature">[`promotionRules( [dtype1, dtype2] )`][@omegion1npm/corrupti-autem-reiciendis/promotion-rules]</span><span class="delimiter">: </span><span class="description">return the array data type with the smallest size and closest "kind" to which array data types can be **safely** cast.</span>
-   <span class="signature">[`typedarrayReviver( key, value )`][@omegion1npm/corrupti-autem-reiciendis/reviver]</span><span class="delimiter">: </span><span class="description">revive a JSON-serialized typed array.</span>
-   <span class="signature">[`safeCasts( [dtype] )`][@omegion1npm/corrupti-autem-reiciendis/safe-casts]</span><span class="delimiter">: </span><span class="description">return a list of array data types to which a provided array data type can be safely cast.</span>
-   <span class="signature">[`sameKindCasts( [dtype] )`][@omegion1npm/corrupti-autem-reiciendis/same-kind-casts]</span><span class="delimiter">: </span><span class="description">return a list of array data types to which a provided array data type can be safely cast or cast within the same "kind".</span>
-   <span class="signature">[`shape( arr )`][@omegion1npm/corrupti-autem-reiciendis/shape]</span><span class="delimiter">: </span><span class="description">determine (nested) array dimensions.</span>
-   <span class="signature">[`slice( x[, start[, end]] )`][@omegion1npm/corrupti-autem-reiciendis/slice]</span><span class="delimiter">: </span><span class="description">return a shallow copy of a portion of an array.</span>
-   <span class="signature">[`take( x, indices[, options] )`][@omegion1npm/corrupti-autem-reiciendis/take]</span><span class="delimiter">: </span><span class="description">take elements from an array.</span>
-   <span class="signature">[`circarray2iterator( src[, options][, mapFcn[, thisArg]] )`][@omegion1npm/corrupti-autem-reiciendis/to-circular-iterator]</span><span class="delimiter">: </span><span class="description">create an iterator which repeatedly iterates over the elements of an array-like object.</span>
-   <span class="signature">[`array2fancy( x[, options] )`][@omegion1npm/corrupti-autem-reiciendis/to-fancy]</span><span class="delimiter">: </span><span class="description">convert an array to an object supporting fancy indexing.</span>
-   <span class="signature">[`array2iteratorRight( src[, mapFcn[, thisArg]] )`][@omegion1npm/corrupti-autem-reiciendis/to-iterator-right]</span><span class="delimiter">: </span><span class="description">create an iterator from an array-like object, iterating from right to left.</span>
-   <span class="signature">[`array2iterator( src[, mapFcn[, thisArg]] )`][@omegion1npm/corrupti-autem-reiciendis/to-iterator]</span><span class="delimiter">: </span><span class="description">create an iterator from an array-like object.</span>
-   <span class="signature">[`typedarray2json( typedarray )`][@omegion1npm/corrupti-autem-reiciendis/to-json]</span><span class="delimiter">: </span><span class="description">return a JSON representation of a typed array.</span>
-   <span class="signature">[`sparsearray2iteratorRight( src[, mapFcn[, thisArg]] )`][@omegion1npm/corrupti-autem-reiciendis/to-sparse-iterator-right]</span><span class="delimiter">: </span><span class="description">create an iterator from a sparse array-like object, iterating from right to left.</span>
-   <span class="signature">[`sparsearray2iterator( src[, mapFcn[, thisArg]] )`][@omegion1npm/corrupti-autem-reiciendis/to-sparse-iterator]</span><span class="delimiter">: </span><span class="description">create an iterator from a sparse array-like object.</span>
-   <span class="signature">[`stridedarray2iterator( N, src, stride, offset[, mapFcn[, thisArg]] )`][@omegion1npm/corrupti-autem-reiciendis/to-strided-iterator]</span><span class="delimiter">: </span><span class="description">create an iterator from a strided array-like object.</span>
-   <span class="signature">[`arrayview2iteratorRight( src[, begin[, end]][, mapFcn[, thisArg]] )`][@omegion1npm/corrupti-autem-reiciendis/to-view-iterator-right]</span><span class="delimiter">: </span><span class="description">create an iterator from an array-like object view, iterating from right to left.</span>
-   <span class="signature">[`arrayview2iterator( src[, begin[, end]][, mapFcn[, thisArg]] )`][@omegion1npm/corrupti-autem-reiciendis/to-view-iterator]</span><span class="delimiter">: </span><span class="description">create an iterator from an array-like object view.</span>
-   <span class="signature">[`complexarray()`][@omegion1npm/corrupti-autem-reiciendis/typed-complex]</span><span class="delimiter">: </span><span class="description">create a complex number typed array.</span>
-   <span class="signature">[`realarray()`][@omegion1npm/corrupti-autem-reiciendis/typed-real]</span><span class="delimiter">: </span><span class="description">create a typed array.</span>
-   <span class="signature">[`zeroToLike( x[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/zero-to-like]</span><span class="delimiter">: </span><span class="description">generate a linearly spaced numeric array whose elements increment by `1` starting from zero and having the same length and data type as a provided input array.</span>
-   <span class="signature">[`zeroTo( n[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/zero-to]</span><span class="delimiter">: </span><span class="description">generate a linearly spaced numeric array whose elements increment by `1` starting from zero.</span>
-   <span class="signature">[`zerosLike( x[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/zeros-like]</span><span class="delimiter">: </span><span class="description">create a zero-filled array having the same length and data type as a provided array.</span>
-   <span class="signature">[`zeros( length[, dtype] )`][@omegion1npm/corrupti-autem-reiciendis/zeros]</span><span class="delimiter">: </span><span class="description">create a zero-filled array having a specified length.</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils/keys' );
var ns = require( '@omegion1npm/corrupti-autem-reiciendis' );

console.log( objectKeys( ns ) );
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

[npm-image]: http://img.shields.io/npm/v/@omegion1npm/corrupti-autem-reiciendis.svg
[npm-url]: https://npmjs.org/package/@omegion1npm/corrupti-autem-reiciendis

[test-image]: https://github.com/omegion1npm/corrupti-autem-reiciendis/actions/workflows/test.yml/badge.svg?branch=main
[test-url]: https://github.com/omegion1npm/corrupti-autem-reiciendis/actions/workflows/test.yml?query=branch:main

[coverage-image]: https://img.shields.io/codecov/c/github/omegion1npm/corrupti-autem-reiciendis/main.svg
[coverage-url]: https://codecov.io/github/omegion1npm/corrupti-autem-reiciendis?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/omegion1npm/corrupti-autem-reiciendis.svg
[dependencies-url]: https://david-dm.org/omegion1npm/corrupti-autem-reiciendis/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/deno
[deno-readme]: https://github.com/omegion1npm/corrupti-autem-reiciendis/blob/deno/README.md
[umd-url]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/umd
[umd-readme]: https://github.com/omegion1npm/corrupti-autem-reiciendis/blob/umd/README.md
[esm-url]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/esm
[esm-readme]: https://github.com/omegion1npm/corrupti-autem-reiciendis/blob/esm/README.md
[branches-url]: https://github.com/omegion1npm/corrupti-autem-reiciendis/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/omegion1npm/corrupti-autem-reiciendis/main/LICENSE

<!-- <toc-links> -->

[@omegion1npm/corrupti-autem-reiciendis/base]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/base

[@omegion1npm/corrupti-autem-reiciendis/cartesian-power]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/cartesian-power

[@omegion1npm/corrupti-autem-reiciendis/cartesian-product]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/cartesian-product

[@omegion1npm/corrupti-autem-reiciendis/cartesian-square]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/cartesian-square

[@omegion1npm/corrupti-autem-reiciendis/complex128]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/complex128

[@omegion1npm/corrupti-autem-reiciendis/complex64]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/complex64

[@omegion1npm/corrupti-autem-reiciendis/convert-same]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/convert-same

[@omegion1npm/corrupti-autem-reiciendis/convert]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/convert

[@omegion1npm/corrupti-autem-reiciendis/dataview]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/dataview

[@omegion1npm/corrupti-autem-reiciendis/defaults]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/defaults

[@omegion1npm/corrupti-autem-reiciendis/dtype]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/dtype

[@omegion1npm/corrupti-autem-reiciendis/empty-like]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/empty-like

[@omegion1npm/corrupti-autem-reiciendis/empty]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/empty

[@omegion1npm/corrupti-autem-reiciendis/filled-by]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/filled-by

[@omegion1npm/corrupti-autem-reiciendis/filled]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/filled

[@omegion1npm/corrupti-autem-reiciendis/from-iterator]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/from-iterator

[@omegion1npm/corrupti-autem-reiciendis/from-scalar]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/from-scalar

[@omegion1npm/corrupti-autem-reiciendis/full-like]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/full-like

[@omegion1npm/corrupti-autem-reiciendis/full]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/full

[@omegion1npm/corrupti-autem-reiciendis/min-dtype]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/min-dtype

[@omegion1npm/corrupti-autem-reiciendis/mostly-safe-casts]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/mostly-safe-casts

[@omegion1npm/corrupti-autem-reiciendis/mskfilter]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/mskfilter

[@omegion1npm/corrupti-autem-reiciendis/mskreject]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/mskreject

[@omegion1npm/corrupti-autem-reiciendis/nans-like]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/nans-like

[@omegion1npm/corrupti-autem-reiciendis/nans]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/nans

[@omegion1npm/corrupti-autem-reiciendis/next-dtype]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/next-dtype

[@omegion1npm/corrupti-autem-reiciendis/one-to-like]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/one-to-like

[@omegion1npm/corrupti-autem-reiciendis/one-to]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/one-to

[@omegion1npm/corrupti-autem-reiciendis/ones-like]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/ones-like

[@omegion1npm/corrupti-autem-reiciendis/ones]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/ones

[@omegion1npm/corrupti-autem-reiciendis/pool]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/pool

[@omegion1npm/corrupti-autem-reiciendis/promotion-rules]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/promotion-rules

[@omegion1npm/corrupti-autem-reiciendis/reviver]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/reviver

[@omegion1npm/corrupti-autem-reiciendis/safe-casts]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/safe-casts

[@omegion1npm/corrupti-autem-reiciendis/same-kind-casts]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/same-kind-casts

[@omegion1npm/corrupti-autem-reiciendis/shape]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/shape

[@omegion1npm/corrupti-autem-reiciendis/slice]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/slice

[@omegion1npm/corrupti-autem-reiciendis/take]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/take

[@omegion1npm/corrupti-autem-reiciendis/to-circular-iterator]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/to-circular-iterator

[@omegion1npm/corrupti-autem-reiciendis/to-fancy]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/to-fancy

[@omegion1npm/corrupti-autem-reiciendis/to-iterator-right]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/to-iterator-right

[@omegion1npm/corrupti-autem-reiciendis/to-iterator]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/to-iterator

[@omegion1npm/corrupti-autem-reiciendis/to-json]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/to-json

[@omegion1npm/corrupti-autem-reiciendis/to-sparse-iterator-right]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/to-sparse-iterator-right

[@omegion1npm/corrupti-autem-reiciendis/to-sparse-iterator]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/to-sparse-iterator

[@omegion1npm/corrupti-autem-reiciendis/to-strided-iterator]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/to-strided-iterator

[@omegion1npm/corrupti-autem-reiciendis/to-view-iterator-right]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/to-view-iterator-right

[@omegion1npm/corrupti-autem-reiciendis/to-view-iterator]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/to-view-iterator

[@omegion1npm/corrupti-autem-reiciendis/typed-complex]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-complex

[@omegion1npm/corrupti-autem-reiciendis/typed-real]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-real

[@omegion1npm/corrupti-autem-reiciendis/zero-to-like]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/zero-to-like

[@omegion1npm/corrupti-autem-reiciendis/zero-to]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/zero-to

[@omegion1npm/corrupti-autem-reiciendis/zeros-like]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/zeros-like

[@omegion1npm/corrupti-autem-reiciendis/zeros]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/zeros

[@omegion1npm/corrupti-autem-reiciendis/ctors]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/ctors

[@omegion1npm/corrupti-autem-reiciendis/index]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/index

[@omegion1npm/corrupti-autem-reiciendis/typed-complex-ctors]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-complex-ctors

[@omegion1npm/corrupti-autem-reiciendis/typed-ctors]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-ctors

[@omegion1npm/corrupti-autem-reiciendis/typed-float-ctors]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-float-ctors

[@omegion1npm/corrupti-autem-reiciendis/typed-integer-ctors]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-integer-ctors

[@omegion1npm/corrupti-autem-reiciendis/typed-real-ctors]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-real-ctors

[@omegion1npm/corrupti-autem-reiciendis/typed-real-float-ctors]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-real-float-ctors

[@omegion1npm/corrupti-autem-reiciendis/typed-signed-integer-ctors]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-signed-integer-ctors

[@omegion1npm/corrupti-autem-reiciendis/typed-unsigned-integer-ctors]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-unsigned-integer-ctors

[@omegion1npm/corrupti-autem-reiciendis/dtypes]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/dtypes

[@omegion1npm/corrupti-autem-reiciendis/typed-complex-dtypes]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-complex-dtypes

[@omegion1npm/corrupti-autem-reiciendis/typed-dtypes]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-dtypes

[@omegion1npm/corrupti-autem-reiciendis/typed-float-dtypes]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-float-dtypes

[@omegion1npm/corrupti-autem-reiciendis/typed-integer-dtypes]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-integer-dtypes

[@omegion1npm/corrupti-autem-reiciendis/typed-real-dtypes]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-real-dtypes

[@omegion1npm/corrupti-autem-reiciendis/typed-real-float-dtypes]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-real-float-dtypes

[@omegion1npm/corrupti-autem-reiciendis/typed-signed-integer-dtypes]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-signed-integer-dtypes

[@omegion1npm/corrupti-autem-reiciendis/typed-unsigned-integer-dtypes]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed-unsigned-integer-dtypes

[@omegion1npm/corrupti-autem-reiciendis/datespace]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/datespace

[@omegion1npm/corrupti-autem-reiciendis/incrspace]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/incrspace

[@omegion1npm/corrupti-autem-reiciendis/linspace]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/linspace

[@omegion1npm/corrupti-autem-reiciendis/logspace]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/logspace

[@omegion1npm/corrupti-autem-reiciendis/typed]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/typed

[@omegion1npm/corrupti-autem-reiciendis/buffer]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/buffer

[@omegion1npm/corrupti-autem-reiciendis/float32]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/float32

[@omegion1npm/corrupti-autem-reiciendis/float64]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/float64

[@omegion1npm/corrupti-autem-reiciendis/int16]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/int16

[@omegion1npm/corrupti-autem-reiciendis/int32]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/int32

[@omegion1npm/corrupti-autem-reiciendis/int8]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/int8

[@omegion1npm/corrupti-autem-reiciendis/shared-buffer]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/shared-buffer

[@omegion1npm/corrupti-autem-reiciendis/uint16]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/uint16

[@omegion1npm/corrupti-autem-reiciendis/uint32]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/uint32

[@omegion1npm/corrupti-autem-reiciendis/uint8]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/uint8

[@omegion1npm/corrupti-autem-reiciendis/uint8c]: https://github.com/omegion1npm/corrupti-autem-reiciendis/tree/main/uint8c

<!-- </toc-links> -->

</section>

<!-- /.links -->
