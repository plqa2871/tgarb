# Termux ARM64 package

The archive contains the original Android AArch64 executable unchanged. It is
packaged rather than rebuilt, so it preserves the interface produced by this
binary. It is not reconstructed C++ source.

Download `termux-arm64.tar.gz` from the successful GitHub Actions run, then
extract it in Termux and run:

```sh
tar -xzf termux-arm64.tar.gz
cd <the-extracted-directory>
./lib
```

The archive preserves the executable permission. If the program needs root,
run it from the same root environment in which `./lib` already works.