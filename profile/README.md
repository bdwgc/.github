## BDWGC Organization

This is a dedicated Github organization established for collaborate development of
* the Boehm-Demers-Weiser conservative C/C++ Garbage Collector (bdwgc, also known as bdw-gc, boehm-gc and libgc)
* the BDWGC bindings for various programming languages ([D](https://github.com/bdwgc/bdwgc-d), [Rust](https://github.com/bdwgc/bdwgc-rust), Zig and potentially others)
* the [Cords](https://github.com/bdwgc/bdwgc/tree/master/cord) package (also known as "cord library") which is a string package that uses a tree-based representation on top of BDWGC
* the [atomic_ops](https://github.com/bdwgc/libatomic_ops) library which provides a semi-portable access to hardware-provided memory update operations on a number of architectures (used by BDWGC)

Major resources
* [Slides about BDWGC](https://www.hboehm.info/gc/04tutorial.pdf) (ISMM 2004)
* [BDWGC info site](https://www.hboehm.info/gc) (updated by Hans Boehm)
* [BDWGC (C/C++) releases](https://github.com/bdwgc/bdwgc/releases)
* [Known BDWGC clients](https://github.com/bdwgc/bdwgc/wiki/Known-clients)
