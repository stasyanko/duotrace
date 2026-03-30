# Duotrace

## Description

Duotrace is a reimplementation of strace and it has such a name as it has two builtin ways of tracing:
- ptrace syscall
- ebpf

## Build

```bash
make
```

> :warning: **This project only works on Linux**

### build with debug symbols

```bash
make debug
```

> This will generate a binary with debug symbols (./ft_strace_debug)

## Run unit tests

```bash
make unit
```

> This will run test for libft and ft_strace

## Usage

```bash
./ft_strace -h
```

## Examples

```bash
./ft_strace ls
```

```bash
./ft_strace -c ls
```
