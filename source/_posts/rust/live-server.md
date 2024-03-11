---
title: Live Server
date: 2024-03-12 00:00:00
description: Launch a local network server with live reload feature for static pages.
keywords: live server, live reload, local server, network server, static pages, web development
thumbnail: https://www.lifewire.com/thmb/RHk5CzUskZEHtVQS5Kba30nHhvY=/400x300/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/is-kindle-unlimited-worth-it-fda01dceb923406a8524c64d2b72693e.jpg
---

Launch a local network server with live reload feature for static pages.

## Binary

You can use it as a CLI program.

### Install

```console
$ cargo install live-server
```

### Usage

```console
$ live-server --help
Launch a local network server with live reload feature for static pages

Usage: live-server.exe [OPTIONS] [ROOT]

Arguments:
  [ROOT]  Set the root path of the static assets [default: .]

Options:
  -H, --host <HOST>  Set the listener host [default: 0.0.0.0]
  -p, --port <PORT>  Set the listener port [default: 0]
  -o, --open         Open the page in browser automatically
  -h, --help         Print help
  -V, --version      Print version
```

```console
$ live-server
[2023-12-22T15:16:04Z INFO  live_server::server] Listening on http://10.17.95.220:6634/
[2023-12-22T15:16:04Z INFO  live_server::watcher] Listening on /home/mirus/html-demo
```

### Log Level

You can set different [`RUST_LOG` environment variable](https://rust-lang-nursery.github.io/rust-cookbook/development_tools/debugging/config_log.html) to filter the log. The default log level is `info`.

## Package

You can also import it as a library in your project.

### Create live server

```rust
use live_server::listen;

listen("127.0.0.1:8080", "./").await?.start().await?;
```

### Enable logs (Optional)

```rust
env_logger::init();
```