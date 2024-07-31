---
title: How to Git Push With SSH Key
date: 2024-07-30T09:05:13.365Z
tags: 
  - git
  - ssh key
  - git ssh
categories: 
  - git
description: This tutorial describes the process of pushing Git files with specific SSH keys to remote servers using command line.
keywords: git push with ssh key, git ssh key, git ssh, git push, git push with specific ssh key, git push with specific ssh key to remote server, git push with specific ssh key to remote server using command line
---

This tutorial describes the process of pushing Git files with specific SSH keys to remote servers using command line.

## Introduction

When you have multiple SSH keys and you want to push your Git files to a remote server using a specific SSH key, you can use the following process to do so.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
## Prerequisites

1. Git installed on your system.
2. SSH keys generated and added to your Git account.
3. A remote server to push your Git files.
4. A terminal to run the commands.
5. A Git repository to push your files.
6. A text editor to edit the SSH configuration file.
7. A basic understanding of Git and SSH.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
## Steps to Git Push With SSH Key

1. Open the terminal on your system.
2. Navigate to the directory where your Git repository is located.
3. Run the following command to check the remote URL of your Git repository.

```bash
git remote -v
```

4. Run the following command to check the list of SSH keys on your system.

```bash
ls -al ~/.ssh
```

5. Run the following command to check the list of SSH keys added to your SSH agent.

```bash
ssh-add -l
```

6. Run the following command to check the list of SSH keys added to your Git account.

```bash
ssh -T
```

7. Run the following command to edit the SSH configuration file.

```bash
nano ~/.ssh/config
```

8. Add the following lines to the SSH configuration file.

```bash
Host github.com
  HostName github.com
  User git
  IdentityFile ~/.ssh/id_rsa
  IdentitiesOnly yes
```

9. Replace `github.com` with the remote server URL and `id_rsa` with the name of your SSH key.
10. Save the changes and exit the text editor.
11. Run the following command to push your Git files to the remote server.

```bash
git push
```

<ins class="adsbygoogle"
    style="display:block"
    data-ad-format="autorelaxed"
    data-ad-client="ca-pub-7571918770474297"
    data-ad-slot="1223367746"></ins>





<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-crafting-thumbnails-on-the-go-for-aspiring-mobile-film-makers/"><u>[New] 2024 Approved  Crafting Thumbnails on the Go  For Aspiring Mobile Film Makers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-easy-reduction-of-footage-for-instagram-on-a-mac/"><u>[New] 2024 Approved  Easy Reduction of Footage for Instagram on a Mac</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-convert-your-webcam-to-vlc-clip/"><u>[New] In 2024, Convert Your Webcam to VLC Clip</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-spectacle-of-speed-simulators-top-5/"><u>[New] Spectacle of Speed Simulators (Top 5)</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-converting-mac-image-types-a-step-by-step-process/"><u>[Updated] 2024 Approved  Converting Mac Image Types  A Step-by-Step Process</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-integrating-audio-elements-into-facebooks-visual-stories/"><u>[Updated] 2024 Approved  Integrating Audio Elements Into Facebook's Visual Stories</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-explore-top-5-non-samsung-360-cameras-today/"><u>[Updated] Explore Top 5 Non-Samsung 360 Cameras Today</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-a-tweet-to-snap-showcase-video-posting-techniques/"><u>[Updated] In 2024, A Tweet-to-Snap Showcase  Video Posting Techniques</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-latest-android-selection-ranked-top-10-apps-for-saving-facebook-videos/"><u>[Updated] In 2024, Latest Android Selection  Ranked Top 10 Apps for Saving Facebook Videos</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-screen-grab-insights-a-critical-appraisal-for-2024/"><u>[Updated] Screen Grab Insights  A Critical Appraisal for 2024</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/10-best-history-youtube-channels-for-students-and-history-lovers-for-2024/"><u>10 Best History YouTube Channels for Students & History Lovers for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Xiaomi Civi 3 Disney 100th Anniversary Edition | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-samsung-galaxy-m34-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Samsung Galaxy M34 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-honor-70-lite-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-oppo-reno-10-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Oppo Reno 10 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-nokia-c12-plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-samsung-galaxy-f15-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-xiaomi-13-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-oppo-a78-5g-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Ultimate Fixes for Google Play Your Oppo A78 5G Isnt Compatible | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-honor-90-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-oppo-reno-11f-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Oppo Reno 11F 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-workable-fixes-to-the-sim-not-provisioned-mm2-error-on-poco-f5-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Workable Fixes to the SIM not provisioned MM#2 Error on Poco F5 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-oppo-a59-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Oppo A59 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-poco-m6-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-vivo-y56-5g-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Vivo Y56 5G System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-vivo-x-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Vivo X Flip? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/best-methods-for-lava-blaze-pro-5g-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Best Methods for Lava Blaze Pro 5G Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-lava-blaze-curve-5g-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Lava Blaze Curve 5G? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-lava-yuva-2-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Lava Yuva 2 Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-page-queue-in-hp-printer-errors/"><u>Clearing Page Queue in HP Printer Errors</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/elite-11-auditorial-capture-devices-overview/"><u>Elite #11 Auditorial Capture Devices Overview</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-realme-gt-5-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Realme GT 5 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fix-motorola-g24-power-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Motorola G24 Power Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-nokia-c12-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Nokia C12 Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fixes-for-apps-keep-crashing-on-vivo-y100i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixes for Apps Keep Crashing on Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-vivo-y27-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Vivo Y27 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-oppo-f23-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Oppo F23 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-vivo-v29e-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Vivo V29e | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-oppo-a2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Oppo A2 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-oneplus-open-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on OnePlus Open 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-vivo-v30-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-change-your-apple-id-on-apple-iphone-12-mini-with-or-without-password-by-drfone-ios/"><u>How To Change Your Apple ID on Apple iPhone 12 mini With or Without Password</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-motorola-moto-g04-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Motorola Moto G04 Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-lava-blaze-pro-5g-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-essential-insights-on-asmr-videos/"><u>In 2024, Essential Insights on ASMR Videos</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-complete-guide-to-xiaomi-redmi-12-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Xiaomi Redmi 12 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-vn-video-editor-for-pc-a-compact-review-of-features-and-performance/"><u>In 2024, VN Video Editor for PC A Compact Review of Features and Performance</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-poco-c50-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Poco C50? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/is-it-illegal-to-document-video-on-youtube-platform-in-2024/"><u>Is It Illegal to Document Video on YouTube Platform, In 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/perfect-your-presence-masterful-morphvox-techniques-for-2024/"><u>Perfect Your Presence  Masterful MorphVOX Techniques for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/premier-5-iphones-for-podcast-aficionados-for-2024/"><u>Premier 5 iPhones for Podcast Aficionados for 2024</u></a></li>
<li><a href="https://techidaily.com/remove-google-frp-lock-on-vivo-s18-pro-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP lock on Vivo S18 Pro</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-vivo-v29e-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Vivo V29e Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-oppo-find-n3-flip-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Oppo Find N3 Flip Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-realme-narzo-60-pro-5g-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Realme Narzo 60 Pro 5G Screen | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-vivo-y100t-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Vivo Y100t Screen | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/ultimate-drone-list-to-maximize-gopro-video-quality/"><u>Ultimate Drone List to Maximize GoPro Video Quality</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-metagame-concept-meaning-importance-and-order/"><u>Unveiling Metagame Concept: Meaning, Importance, & Order</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-oppo-a38-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Oppo A38? Here is How | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-vivo-v30-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Vivo V30? Here is How | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Vivo Y200e 5G? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-honor-magic-vs-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-honor-x7b-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Honor X7b | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-xiaomi-redmi-note-12t-pro-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Xiaomi Redmi Note 12T Pro Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
</ul></div>
