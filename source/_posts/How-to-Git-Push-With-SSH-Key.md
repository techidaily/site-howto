---
title: How to Git Push With SSH Key
date: 2024-05-20T09:03:33.812Z
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

## Prerequisites

1. Git installed on your system.
2. SSH keys generated and added to your Git account.
3. A remote server to push your Git files.
4. A terminal to run the commands.
5. A Git repository to push your files.
6. A text editor to edit the SSH configuration file.
7. A basic understanding of Git and SSH.

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
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-nubia-z50-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Nubia Z50 Ultra | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-nokia-c32-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-vivo-y100a-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Vivo Y100A | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/4-ways-to-fix-android-blue-screen-of-death-on-poco-x5-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Ways to Fix Android Blue Screen of Death On Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/meizu-21-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Meizu 21 Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-lava-yuva-3-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Lava Yuva 3 Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-poco-m6-pro-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-realme-12-proplus-5g-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Realme 12 Pro+ 5G Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-lava-blaze-2-pro-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Lava Blaze 2 Pro Auto Does Not Work | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-lava-yuva-3-pro-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Lava Yuva 3 Pro? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-vivo-y56-5g-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Vivo Y56 5G ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-samsung-galaxy-a25-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Samsung Galaxy A25 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-vivo-v30-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-tecno-phantom-v-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/bricked-your-lava-blaze-pro-5g-heres-a-full-solution-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Bricked Your Lava Blaze Pro 5G? Heres A Full Solution | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-oppo-find-x7-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Oppo Find X7 Ultra | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-oppo-f25-pro-5g-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Oppo F25 Pro 5G Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-lava-yuva-2-pro-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Troubleshooting Guide How to Fix an Unresponsive Lava Yuva 2 Pro Screen | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/full-guide-how-to-fix-connection-is-not-private-on-xiaomi-redmi-k70-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Guide How To Fix Connection Is Not Private on Xiaomi Redmi K70 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-honor-70-lite-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/why-does-my-oppo-a38-keep-turning-off-by-itself-6-fixes-are-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Does My Oppo A38 Keep Turning Off By Itself? 6 Fixes Are Here | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-y27-5g-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo Y27 5G Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-the-soft-bricked-honor-magic-5-lite-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Honor Magic 5 Lite? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Xiaomi Redmi Note 12 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-videos-and-music-files-from-iphone-14-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Photos, Videos & Music Files from iPhone 14 | Stellar</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-how-to-fake-gps-on-android-without-mock-location-for-your-nokia-g310-drfone-by-drfone-virtual/"><u>In 2024, How to Fake GPS on Android without Mock Location For your Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-realme-c53-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Realme C53 Location Settings | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-adjust-the-tiktok-videos-length-to-make-them-captivating/"><u>New Adjust the TikTok Videos Length to Make Them Captivating</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-infinix-smart-8-plus-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Infinix Smart 8 Plus Data? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-motorola-moto-g24-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/2024-approved-discover-8-top-rated-video-and-photo-merger-tools-for-desktop-mobile-and-online-use-elevate-your-media-game-and-create-stunning-visuals-with-e/"><u>2024 Approved Discover 8 Top-Rated Video and Photo Merger Tools for Desktop, Mobile, and Online Use. Elevate Your Media Game and Create Stunning Visuals with Ease</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-effective-ways-to-bypass-activation-lock-from-apple-iphone-7-by-drfone-ios/"><u>3 Effective Ways to Bypass Activation Lock from Apple iPhone 7</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-xiaomi-redmi-k70-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Xiaomi Redmi K70</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-why-is-ipogo-not-working-on-google-pixel-7a-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Google Pixel 7a? Fixed | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-video-editing-on-the-move-top-apps-for-iphone-android-and-more/"><u>New Video Editing on the Move Top Apps for iPhone, Android, and More</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/fcpx-training-academy-top-online-courses-and-tutorials/"><u>FCPX Training Academy Top Online Courses and Tutorials</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-nubia-red-magic-9-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Nubia Red Magic 9 Pro+? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-nokia-c12-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Nokia C12 Pattern Lock if Forgotten? 6 Ways</u></a></li>
</ul></div>


