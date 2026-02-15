# Weibo Crawler

This project includes an auto-send mail feature to notify you of updates.

**Note:** This project does not support Docker installation. It must be run directly on Linux with the `msmtp` package installed.

## Prerequisites

Install Python dependencies:

```bash
pip install -r requirements.txt


## Install msmtp
You need to install msmtp to enable the email sending feature. And configure it yourself.

For Arch Linux

```bash
sudo pacman -S msmtp
```

For Debian / Ubuntu

```bash
sudo apt update
sudo apt install msmtp msmtp-mta ca-certificates
```

For CentOS / RHEL

```bash
sudo yum install msmtp
```
