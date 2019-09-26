Implementation of the [Pinocchio](https://eprint.iacr.org/2013/279) zk-SNARK system and the [Geppetri](https://eprint.iacr.org/2017/013) extension for proofs on authenticated data based on text files.

Used by the [original PySNARK](https://github.com/Charterhouse/pysnark) and the qaptools backend of [its re-write](https://github.com/meilof/pysnark).

Qaptools may be used for non-commercial, experimental and research purposes; see `LICENSE.md` for details. Qaptools is experimental and **not fit for production environment**. In particular, qaptools does **not use cryptographically secure randomness**! See `base.cpp` and `modp.cpp`.

Compile instructions:

```
git submodule init
git submodule update
mkdir build
cd build
cmake ..
make
```

Compiling for Windows: using mingw64 (on Windows or as a cross-compiler) and [the GMP package](https://packages.msys2.org/package/mingw-w64-x86_64-gmp?repo=mingw64)

Windows binaries are available [here](https://github.com/Charterhouse/qaptools/releases/download/0.1.1/qaptools-win64-0.1.1.zip)
