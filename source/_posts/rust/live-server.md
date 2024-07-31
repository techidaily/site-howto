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



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-web.techidaily.com/024-approved-battlefront-bastion-100plus-epic-game-battles/"><u>[New] 2024 Approved  Battlefront Bastion  100+ Epic Game Battles</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-elevating-your-videography-through-audio-storytelling/"><u>[New] 2024 Approved  Elevating Your Videography Through Audio Storytelling</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-mirthful-methodology-making-memes-for-free/"><u>[New] 2024 Approved  Mirthful Methodology  Making Memes for Free</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-your-ultimate-guide-to-accessing-facebook-content-on-applemedia-hub-for-2024/"><u>[New] Your Ultimate Guide to Accessing Facebook Content on AppleMedia Hub for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-make-money-on-youtube-without-ads-for-2024/"><u>[Updated] How to Make Money on YouTube Without Ads for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-navigating-free-text-animation-for-artists/"><u>[Updated] Navigating Free Text Animation for Artists</u></a></li>
<li><a href="https://howto.techidaily.com/11-ways-to-fix-it-when-my-tecno-camon-20-wont-charge-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Ways to Fix it When My Tecno Camon 20 Wont Charge | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-leading-platforms-for-digital-graffiti-fonts/"><u>2024 Approved  Leading Platforms for Digital Graffiti Fonts</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-mememagic-app-unleash-your-comedic-genius-online/"><u>2024 Approved  MemeMagic App - Unleash Your Comedic Genius Online</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-samsung-galaxy-xcover-7-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Samsung Galaxy XCover 7 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-tecno-phantom-v-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-motorola-defy-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Motorola Defy 2 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-samsung-galaxy-f04-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Samsung Galaxy F04 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-asus-rog-phone-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-tecno-pop-8-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Tecno Pop 8 System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-tecno-spark-20c-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Tecno Spark 20C? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-xiaomi-redmi-k70-pro-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Xiaomi Redmi K70 Pro Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-poco-m6-pro-4g-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Poco M6 Pro 4G Quickly | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fix-vivo-x90s-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Vivo X90S Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-nokia-c300-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Nokia C300 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-honor-magic-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-realme-narzo-n53-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-nokia-c02-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-honor-magic-6-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Honor Magic 6 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-oppo-reno-11f-5g-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Oppo Reno 11F 5G 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-samsung-galaxy-a05s-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Samsung Galaxy A05s 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-tecno-spark-20-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-it-oppo-reno-8t-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Oppo Reno 8T 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-vivo-y100i-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-itel-p55t-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Itel P55T | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-huawei-p60-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Huawei P60 to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-oppo-reno-10-pro-5g-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Oppo Reno 10 Pro 5G to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-any-samsung-galaxy-s24plus-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any Samsung Galaxy S24+ Phone Password Using Emergency Call</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-removing-device-from-apple-id-for-your-apple-iphone-15-pro-by-drfone-ios/"><u>In 2024, Removing Device From Apple ID For your Apple iPhone 15 Pro</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-unlock-your-boost-mobile-apple-iphone-15-pro-max-before-the-plan-expires-by-drfone-ios/"><u>In 2024, Unlock Your Boost Mobile Apple iPhone 15 Pro Max Before the Plan Expires</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-file-access-fixes-for-read-only-reversion-on-pcs/"><u>Mastering File Access: Fixes for Read-Only Reversion on PCs</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/maximizing-reach-sharing-twitters-vids-via-snapchat-for-2024/"><u>Maximizing Reach  Sharing Twitters' Vids via Snapchat for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mirthful-montage-mastering-7-comical-video-vignettes-for-2024/"><u>Mirthful Montage  Mastering 7 Comical Video Vignettes for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/-matters-choosing-best-stocks-yts-guide-for-2024/"><u>Money Matters  Choosing Best Stocks YTs Guide for 2024</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-15-pro-max-data-from-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 15 Pro Max Data From iCloud | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/resolve-your-iphone-8-plus-keeps-asking-for-outlook-password-drfone-by-drfone-ios/"><u>Resolve Your iPhone 8 Plus Keeps Asking for Outlook Password | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/tips-for-seamlessly-screening-instagram-stories-for-2024/"><u>Tips for Seamlessly Screening Instagram Stories for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-honor-play-7t-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Honor Play 7T Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-s18-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo S18 Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-y100i-power-5g-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo Y100i Power 5G Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-nokia-c210-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Nokia C210 Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-htc-u23-pro-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your HTC U23 Pro Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
</ul></div>
