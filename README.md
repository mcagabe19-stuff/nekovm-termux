## Build Instructions

1. Clone repo and cd on it

2. Installing dependencies

NOTE: You needed have x11-repo installed

```bash
apt update && yes | apt upgrade && apt install build-essential cmake make clang apache2 libgc gtk3 xorgproto 
```

3. Building

```bash
mkdir build && cd build && cmake .. && make -j$(nproc)
```

4. Installing

```bash
make install
```

## Broken Things
* SQL
