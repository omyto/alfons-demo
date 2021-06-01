# Alfons Demo

## Setup

* Update Submodules

```bash
git submodule update --init
```

* Ubuntu

```bash
sudo apt update
sudo apt install -y build-essential
sudo apt install -y cmake libgl-dev libglfw3-dev
```

## Build


```bash
mkdir build
cd build
cmake ..
make
```

## Run

* Basic demo

```bash
./bin/basic
```
* Spiraling demo

```bash
./bin/enspiraling
```
