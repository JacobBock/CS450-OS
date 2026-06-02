# The C Team

## CS450 Operating System

---

## Build Environment

The necessary build environment to run the operating system is shown below.

```dockerfile
FROM ubuntu

RUN apt update && apt install -y \
    clang \
    make \
    nasm \
    git \
    binutils-i686-linux-gnu \
    qemu-system-x86 \
    gdb
