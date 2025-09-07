

## Test locally

devtools:
```sh
sudo pacman -S devtools
```

```sh
extra-x86_64-build
```

```sh
makepkg -si -f -p PKGBUILD        # source
makepkg -si -f -p PKGBUILD.bin    # binary
```

to remove again:
```sh
sudo pacman -Rns clang-include-graph clang-include-graph-debug
sudo pacman -Rns clang-include-graph-bin clang-include-graph-bin-debug
```
