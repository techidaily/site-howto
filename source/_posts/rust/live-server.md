---
title: Live Server
date: 2024-07-30T11:25:38.464Z
description: Launch a local network server with live reload feature for static pages.
keywords: live server, live reload, local server, network server, static pages, web development
thumbnail: https://thmb.techidaily.com/e4dab8212b61415ab670db2724890039dc218886423e579644f1092e23638fe5.jpg
---

Launch a local network server with live reload feature for static pages.

## Binary

You can use it as a CLI program.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
### Install

```console
$ cargo install live-server
```

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
### Log Level

You can set different [`RUST_LOG` environment variable](https://rust-lang-nursery.github.io/rust-cookbook/development_tools/debugging/config_log.html) to filter the log. The default log level is `info`.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Package

You can also import it as a library in your project.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
### Create live server

```rust
use live_server::listen;

listen("127.0.0.1:8080", "./").await?.start().await?;
```

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
### Enable logs (Optional)

```rust
env_logger::init();
```
<ins class="adsbygoogle"
    style="display:block"
    data-ad-format="autorelaxed"
    data-ad-client="ca-pub-7571918770474297"
    data-ad-slot="1223367746"></ins>




