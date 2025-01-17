+++
title = "Software"
layout = "single-para"
+++

We have a [Roaring Bitmap organization on GitHub](https://github.com/RoaringBitmap) counting over 40 programmers. We
maintain a portable [format specification](https://github.com/RoaringBitmap/RoaringFormatSpec).

* [RoaringBitmap](https://github.com/lemire/RoaringBitmap/) is a widely used, optimized and robust **Java** library. It supports both regular and off-heap (e.g., memory mapped) bitmaps.
* The [CRoaring library](https://github.com/RoaringBitmap/CRoaring) is a **C/C++** library that provides an optimized implementation of Roaring for C/C++ programmers. It works under Windows (Visual Studio), Linux (ARM and x64) and macOS.
  *   We have **Python** libraries wrapping our C code: [PyRoaringBitMap](https://github.com/Ezibenroc/PyRoaringBitMap) and [python-croaring](https://github.com/sunzhaoping/python-croaring).
  *   We have a [**Swift** library wrapping our C code](https://github.com/RoaringBitmap/SwiftRoaring).
  *   We have a [**Rust** library wrapping our C code](https://github.com/saulius/croaring-rs).
  *   We have a [**Go** library wrapping our C code](https://github.com/RoaringBitmap/gocroaring).    
  *   We have a [**Node**/JavaScript library wrapping our C code](https://github.com/SalvatorePreviti/roaring-node).
  *   We have a [**WebAssembly** library wrapping our C code](https://github.com/SalvatorePreviti/roaring-wasm).
  *   We have a [**D** library wrapping our C code](https://github.com/yuce/droaring).
  *   We have a [**Redis** Module wrapping our C code](https://github.com/aviggiano/redis-roaring).
  *   We have a [**PostgreSQL** Extension wrapping our C code](https://github.com/ChenHuajun/pg_roaringbitmap).
  *   We have a [**Greenplum** Extension wrapping our C code](https://github.com/zeromax007/gpdb-roaringbitmap).
  *   We have a [**C#** library wrapping our C code](https://github.com/RogueException/CRoaring.Net). It works under Windows and Linux. See also the  [.NET wrapper around Roaring64Map](https://github.com/RoaringBitmap/RoaringCLI).
* We have a pure [**Go** implementation of Roaring](https://github.com/RoaringBitmap/roaring).

## Various ports

In addition to the Java, C/C++, Python and Go versions described above, there are many other ports.

* C++: [izenelib](https://github.com/izenecloud/izenelib/blob/master/include/am/bitmap/RoaringBitmap.h) by izenecloud
* Rust: [A better compressed bitset in Rust](https://github.com/RoaringBitmap/roaring-rs)
* Cython: [Roaring Bitmap in Cython](https://github.com/andreasvc/roaringbitmap) by Andreas van Cranenburgh
* C#: A [.NET library for compressed bit set data structures](https://github.com/BitSetsNet/BitSetsNet)
* C#: A [C# implementation of Roaring Bitmap](https://github.com/mgholam/MGRB) used by [RaptorDB](https://github.com/mgholam/RaptorDB-Document)
* C#: A [.NET Implementation of RoaringBitmap (C#)](https://github.com/Tornhoof/RoaringBitmap)
* Go: [Pilosa](https://www.pilosa.com/) has its own Go implementation
* Go: [Roaring Bitmaps - compressed bitmaps in Go](https://github.com/fzandona/goroar) by Fernando Zandona
* Haskell: [Roaring Bitmaps in Haskell](https://github.com/thsutton/leonine) by Thomas Sutton
* Java: [Apache Lucene](https://lucene.apache.org/core/) has a Roaring bitmap implementation ([source code](https://github.com/apache/lucene-solr))
* OCaml:  [Roaring bitmaps for OCaml](https://github.com/travisbrady/ocaml-roaring)
* Python: The [Whoosh](https://pypi.python.org/pypi/Whoosh/) search engine uses Roaring ([source code](https://bitbucket.org/mchaput/whoosh/wiki/Home))
* Python: [Basic roaring bitmap in Python](https://github.com/burtgulash/roarink) by Tomáš Maršálek
