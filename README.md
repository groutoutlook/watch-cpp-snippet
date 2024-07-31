# minicpp

A REPL-style "development environment" for small C++ snippets.
For cases where an online compiler is out of the question.

# Caution!

- if in windows, just use `WSL`.

![minicpp](https://i.imgur.com/nyUedKx.png)

(the example uses the [`dbg(…)`](https://github.com/sharkdp/dbg-macro/) macro
which is included in `minicpp`)

## How to

1. Start the watcher that recompiles and runs the snippet:

```bash
./run
```

2. Edit `main.cpp`. Save the file to trigger a new compile-and-run cycle.

## Restart

If you want to start from scratch, you can call

```bash
./reset
```

## Install

Make sure that `inotifywait` is installed. It should be available
for most Linux distributions (the package is typically called `inotify-tools`).

Apart from that, you just need to clone the repository:

```bash
git clone --recursive https://github.com/sharkdp/minicpp
```
