Implementation of the [Pinocchio](https://eprint.iacr.org/2013/279) zk-SNARK system and the [Geppetri](https://eprint.iacr.org/2017/013) extension for proofs on authenticated data based on text files.

Used by the [original PySNARK](https://github.com/Charterhouse/pysnark) and the qaptools backend of [its re-write](https://github.com/meilof/pysnark).

Compile instructions:

```
git submodule init
git submodule update
mkdir build
cd build
cmake ..
make
```

Windows binaries are available [here](https://github.com/Charterhouse/qaptools/releases/download/0.1/qaptools-0.1-win32.zip)
