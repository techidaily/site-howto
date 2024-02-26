---
title: How to Git Push With SSH Key
date: 2024-02-02 00:00:00
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
