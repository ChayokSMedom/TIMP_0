# TIMP_0
отчёт

personal token: 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

```
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ cmake --version
cmake version 4.2.3

CMake suite maintained and supported by Kitware (kitware.com/cmake).
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ curl --version
Command 'curl' not found, but can be installed with:
sudo snap install curl  # version 8.20.0, or
sudo apt  install curl  # version 8.18.0-1ubuntu2.1
See 'snap info curl' for additional versions.
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo apt install curl
[sudo: authenticate] Password:             
The following packages were automatically installed and are no longer required:
  linux-headers-7.0.0-14                   linux-modules-7.0.0-14-generic
  linux-headers-7.0.0-14-generic           linux-tools-7.0.0-14
  linux-image-unsigned-7.0.0-14-generic    linux-tools-7.0.0-14-generic
  linux-main-modules-zfs-7.0.0-14-generic
Use 'sudo apt autoremove' to remove them.

Installing:
  curl

Summary:
  Upgrading: 0, Installing: 1, Removing: 0, Not Upgrading: 2
  Download size: 272 kB
  Space needed: 521 kB / 12.0 GB available

Get:1 http://archive.ubuntu.com/ubuntu resolute-updates/main amd64 curl amd64 8.18.0-1ubuntu2.1 [272 kB]
Fetched 272 kB in 0s (653 kB/s)
Selecting previously unselected package curl.
(Reading database… 218987 files and directories currently installed.)
Preparing to unpack …/curl_8.18.0-1ubuntu2.1_amd64.deb…
Unpacking curl (8.18.0-1ubuntu2.1)…
Setting up curl (8.18.0-1ubuntu2.1)…
Processing triggers for man-db (2.13.1-1build1)…
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ curl --version
curl 8.18.0 (x86_64-pc-linux-gnu) libcurl/8.18.0 OpenSSL/3.5.5 zlib/1.3.1 brotli/1.2.0 zstd/1.5.7 libidn2/2.3.8 libpsl/0.21.2 libssh2/1.11.1 nghttp2/1.68.0 librtmp/2.3 mit-krb5/1.22.1 OpenLDAP/2.6.10
Release-Date: 2026-01-07, security patched: 8.18.0-1ubuntu2.1
Protocols: dict file ftp ftps gopher gophers http https imap imaps ipfs ipns ldap ldaps mqtt pop3 pop3s rtmp rtsp scp sftp smb smbs smtp smtps telnet tftp ws wss
Features: alt-svc AsynchDNS brotli GSS-API HSTS HTTP2 HTTPS-proxy IDN IPv6 Kerberos Largefile libz NTLM PSL SPNEGO SSL threadsafe TLS-SRP UnixSockets zstd
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ $ git --version
$: command not found
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ git --version
Command 'git' not found, but can be installed with:
sudo apt install git
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo apt install git
The following packages were automatically installed and are no longer required:
  linux-headers-7.0.0-14                   linux-modules-7.0.0-14-generic
  linux-headers-7.0.0-14-generic           linux-tools-7.0.0-14
  linux-image-unsigned-7.0.0-14-generic    linux-tools-7.0.0-14-generic
  linux-main-modules-zfs-7.0.0-14-generic
Use 'sudo apt autoremove' to remove them.

Installing:
  git

Installing dependencies:
  git-man  liberror-perl

Suggested packages:
  git-doc  git-email  git-gui  gitk  gitweb  git-cvs  git-svn

Summary:
  Upgrading: 0, Installing: 3, Removing: 0, Not Upgrading: 2
  Download size: 5,453 kB
  Space needed: 28.4 MB / 12.0 GB available

Continue? [Y/n] y
Get:1 http://archive.ubuntu.com/ubuntu resolute/main amd64 liberror-perl all 0.17030-1 [23.5 kB]
Get:2 http://archive.ubuntu.com/ubuntu resolute/main amd64 git-man all 1:2.53.0-1ubuntu1 [1,202 kB]
Get:3 http://archive.ubuntu.com/ubuntu resolute/main amd64 git amd64 1:2.53.0-1ubuntu1 [4,227 kB]
Fetched 5,453 kB in 1s (8,891 kB/s)
Selecting previously unselected package liberror-perl.
(Reading database… 218998 files and directories currently installed.)
Preparing to unpack …/liberror-perl_0.17030-1_all.deb…
Unpacking liberror-perl (0.17030-1)…
Selecting previously unselected package git-man.
Preparing to unpack …/git-man_1%3a2.53.0-1ubuntu1_all.deb…
Unpacking git-man (1:2.53.0-1ubuntu1)…
Selecting previously unselected package git.
Preparing to unpack …/git_1%3a2.53.0-1ubuntu1_amd64.deb…
Unpacking git (1:2.53.0-1ubuntu1)…
Setting up liberror-perl (0.17030-1)…
Setting up git-man (1:2.53.0-1ubuntu1)…
Setting up git (1:2.53.0-1ubuntu1)…
Processing triggers for man-db (2.13.1-1build1)…
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ g++ --version
Command 'g++' not found, but can be installed with:
sudo apt install g++
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo apt install g++
The following packages were automatically installed and are no longer required:
  linux-headers-7.0.0-14                   linux-modules-7.0.0-14-generic
  linux-headers-7.0.0-14-generic           linux-tools-7.0.0-14
  linux-image-unsigned-7.0.0-14-generic    linux-tools-7.0.0-14-generic
  linux-main-modules-zfs-7.0.0-14-generic
Use 'sudo apt autoremove' to remove them.

Installing:
  g++

Installing dependencies:
  g++-15  g++-15-x86-64-linux-gnu  g++-x86-64-linux-gnu  libstdc++-15-dev

Suggested packages:
  g++-multilib  g++-15-multilib  gcc-15-doc  libstdc++-15-doc

Summary:
  Upgrading: 0, Installing: 5, Removing: 0, Not Upgrading: 2
  Download size: 17.4 MB
  Space needed: 68.0 MB / 12.0 GB available

Continue? [Y/n] y
Get:1 http://archive.ubuntu.com/ubuntu resolute/main amd64 libstdc++-15-dev amd64 15.2.0-16ubuntu1 [2,920 kB]
Get:2 http://archive.ubuntu.com/ubuntu resolute/main amd64 g++-15-x86-64-linux-gnu amd64 15.2.0-16ubuntu1 [14.4 MB]
Get:3 http://archive.ubuntu.com/ubuntu resolute/main amd64 g++-15 amd64 15.2.0-16ubuntu1 [26.7 kB]
Get:4 http://archive.ubuntu.com/ubuntu resolute/main amd64 g++-x86-64-linux-gnu amd64 4:15.2.0-5ubuntu1 [968 B]
Get:5 http://archive.ubuntu.com/ubuntu resolute/main amd64 g++ amd64 4:15.2.0-5ubuntu1 [1,100 B]
Fetched 17.4 MB in 1s (23.4 MB/s)            
Selecting previously unselected package libstdc++-15-dev:amd64.
(Reading database… 220139 files and directories currently installed.)
Preparing to unpack …/libstdc++-15-dev_15.2.0-16ubuntu1_amd64.deb…
Unpacking libstdc++-15-dev:amd64 (15.2.0-16ubuntu1)…
Selecting previously unselected package g++-15-x86-64-linux-gnu.
Preparing to unpack …/g++-15-x86-64-linux-gnu_15.2.0-16ubuntu1_amd64.deb…
Unpacking g++-15-x86-64-linux-gnu (15.2.0-16ubuntu1)…
Selecting previously unselected package g++-15.
Preparing to unpack …/g++-15_15.2.0-16ubuntu1_amd64.deb…
Unpacking g++-15 (15.2.0-16ubuntu1)…
Selecting previously unselected package g++-x86-64-linux-gnu.
Preparing to unpack …/g++-x86-64-linux-gnu_4%3a15.2.0-5ubuntu1_amd64.deb…
Unpacking g++-x86-64-linux-gnu (4:15.2.0-5ubuntu1)…
Selecting previously unselected package g++.
Preparing to unpack …/g++_4%3a15.2.0-5ubuntu1_amd64.deb…
Unpacking g++ (4:15.2.0-5ubuntu1)…
Setting up libstdc++-15-dev:amd64 (15.2.0-16ubuntu1)…
Setting up g++-15-x86-64-linux-gnu (15.2.0-16ubuntu1)…
Setting up g++-x86-64-linux-gnu (4:15.2.0-5ubuntu1)…
Setting up g++-15 (15.2.0-16ubuntu1)…
Setting up g++ (4:15.2.0-5ubuntu1)…
update-alternatives: using /usr/bin/g++ to provide /usr/bin/c++ (c++) in auto mo
de
Processing triggers for man-db (2.13.1-1build1)…
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo apt install hub
The following packages were automatically installed and are no longer required:
  linux-headers-7.0.0-14                   linux-modules-7.0.0-14-generic
  linux-headers-7.0.0-14-generic           linux-tools-7.0.0-14
  linux-image-unsigned-7.0.0-14-generic    linux-tools-7.0.0-14-generic
  linux-main-modules-zfs-7.0.0-14-generic
Use 'sudo apt autoremove' to remove them.

Installing:
  hub

Installing dependencies:
  xsel

Summary:
  Upgrading: 0, Installing: 2, Removing: 0, Not Upgrading: 2
  Download size: 2,718 kB
  Space needed: 7,808 kB / 11.9 GB available

Continue? [Y/n] y
Get:1 http://archive.ubuntu.com/ubuntu resolute/universe amd64 hub amd64 2.14.2~ds1-3 [2,697 kB]
Get:2 http://archive.ubuntu.com/ubuntu resolute/universe amd64 xsel amd64 1.2.1-1build1 [20.5 kB]
Fetched 2,718 kB in 16s (171 kB/s)                                             
Selecting previously unselected package hub.
(Reading database… 221043 files and directories currently installed.)
Preparing to unpack …/hub_2.14.2~ds1-3_amd64.deb…
Unpacking hub (2.14.2~ds1-3)…
Selecting previously unselected package xsel.
Preparing to unpack …/xsel_1.2.1-1build1_amd64.deb…
Unpacking xsel (1.2.1-1build1)…
Setting up xsel (1.2.1-1build1)…
Setting up hub (2.14.2~ds1-3)…
Processing triggers for man-db (2.13.1-1build1)…
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo apt install make
make is already the newest version (4.4.1-3).
make set to manually installed.
The following packages were automatically installed and are no longer required:
  linux-headers-7.0.0-14                   linux-modules-7.0.0-14-generic
  linux-headers-7.0.0-14-generic           linux-tools-7.0.0-14
  linux-image-unsigned-7.0.0-14-generic    linux-tools-7.0.0-14-generic
  linux-main-modules-zfs-7.0.0-14-generic
Use 'sudo apt autoremove' to remove them.

Summary:
  Upgrading: 0, Installing: 0, Removing: 0, Not Upgrading: 2
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo apt install sudl
Error: Unable to locate package sudl
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo apt install subl
Error: Unable to locate package subl
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo apt install sub1
Error: Unable to locate package sub1
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ subl --version
Command 'subl' not found, but can be installed with:
sudo snap install sublime-text
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo snap install sublime-text
error: This revision of snap "sublime-text" was published using classic
       confinement and thus may perform arbitrary system changes outside of the
       security sandbox that snaps are usually confined to, which may put your
       system at risk.

       If you understand and want to proceed repeat the command including
       --classic.
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo snap install sublime-text --classic
sublime-text 4200 from Snapcrafters✪ installed
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo apt install tree
The following packages were automatically installed and are no longer required:
  linux-headers-7.0.0-14                   linux-modules-7.0.0-14-generic
  linux-headers-7.0.0-14-generic           linux-tools-7.0.0-14
  linux-image-unsigned-7.0.0-14-generic    linux-tools-7.0.0-14-generic
  linux-main-modules-zfs-7.0.0-14-generic
Use 'sudo apt autoremove' to remove them.

Installing:
  tree

Summary:
  Upgrading: 0, Installing: 1, Removing: 0, Not Upgrading: 2
  Download size: 53.5 kB
  Space needed: 125 kB / 11.8 GB available

Get:1 http://archive.ubuntu.com/ubuntu resolute/universe amd64 tree amd64 2.3.1-1 [53.5 kB]
Fetched 53.5 kB in 0s (143 kB/s)
Selecting previously unselected package tree.
(Reading database… 221113 files and directories currently installed.)
Preparing to unpack …/tree_2.3.1-1_amd64.deb…
Unpacking tree (2.3.1-1)…
Setting up tree (2.3.1-1)…
Processing triggers for man-db (2.13.1-1build1)…
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo apt install wget
wget is already the newest version (1.25.0-2ubuntu4).
wget set to manually installed.
The following packages were automatically installed and are no longer required:
  linux-headers-7.0.0-14                   linux-modules-7.0.0-14-generic
  linux-headers-7.0.0-14-generic           linux-tools-7.0.0-14
  linux-image-unsigned-7.0.0-14-generic    linux-tools-7.0.0-14-generic
  linux-main-modules-zfs-7.0.0-14-generic
Use 'sudo apt autoremove' to remove them.

Summary:
  Upgrading: 0, Installing: 0, Removing: 0, Not Upgrading: 2
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ sudo apt install openss1
Error: Unable to locate package openss1
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ openssl version
OpenSSL 3.5.5 27 Jan 2026 (Library: OpenSSL 3.5.5 27 Jan 2026)
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ git --version
git version 2.53.0
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ g++ --version
g++ (Ubuntu 15.2.0-16ubuntu1) 15.2.0
Copyright (C) 2025 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ hub --version
git version 2.53.0
hub version 2.14.2
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ make --version
GNU Make 4.4.1
Built for x86_64-pc-linux-gnu
Copyright (C) 1988-2023 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later <https://gnu.org/licenses/gpl.html>
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ subl --version
Sublime Text Build 4200
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ $ tree --version
$: command not found
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ tree --version
tree v2.3.1 © 1996 - 2026 by Steve Baker, Thomas Moore, Francesc Rocher, Florian Sesser, Kyosuke Tokoro
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ wget --version
GNU Wget 1.25.0 built on linux-gnu.

-cares +digest -gpgme +https +ipv6 +iri +large-file -metalink +nls 
+ntlm +opie +psl +ssl/gnutls 

Wgetrc: 
    /etc/wgetrc (system)
Locale: 
    /usr/share/locale 
Compile: 
    gcc -DHAVE_CONFIG_H -DSYSTEM_WGETRC="/etc/wgetrc" 
    -DLOCALEDIR="/usr/share/locale" -I. -I../../src -I../lib 
    -I../../lib -Wdate-time -D_FORTIFY_SOURCE=3 
    -I/usr/include/p11-kit-1 -DHAVE_LIBGNUTLS -DNDEBUG -g -O2 
    -Werror=implicit-function-declaration -fno-omit-frame-pointer 
    -mno-omit-leaf-frame-pointer 
    -ffile-prefix-map=/build/wget-PpRkge/wget-1.25.0=. -flto=auto 
    -ffat-lto-objects -fstack-protector-strong -fstack-clash-protection 
    -Wformat -Werror=format-security -fcf-protection 
    -fdebug-prefix-map=/build/wget-PpRkge/wget-1.25.0=/usr/src/wget-1.25.0-2ubuntu4 
    -DNO_SSLv2 
Link: 
    gcc -I/usr/include/p11-kit-1 -DHAVE_LIBGNUTLS -DNDEBUG -g -O2 
    -Werror=implicit-function-declaration -fno-omit-frame-pointer 
    -mno-omit-leaf-frame-pointer 
    -ffile-prefix-map=/build/wget-PpRkge/wget-1.25.0=. -flto=auto 
    -ffat-lto-objects -fstack-protector-strong -fstack-clash-protection 
    -Wformat -Werror=format-security -fcf-protection 
    -fdebug-prefix-map=/build/wget-PpRkge/wget-1.25.0=/usr/src/wget-1.25.0-2ubuntu4 
    -DNO_SSLv2 -Wl,-Bsymbolic-functions 
    -Wl,--package-metadata=%7B%22type%22:%22deb%22%2C%22os%22:%22ubuntu%22%2C%22name%22:%22wget%22%2C%22version%22:%221.25.0-2ubuntu4%22%2C%22architecture%22:%22amd64%22%7D 
    -flto=auto -ffat-lto-objects -Wl,-z,relro -Wl,-z,now -lpcre2-8 
    -luuid -lidn2 -lnettle -lgnutls -lz -lpsl ../lib/libgnu.a 

Copyright (C) 2015 Free Software Foundation, Inc.
License GPLv3+: GNU GPL version 3 or later
<http://www.gnu.org/licenses/gpl.html>.
This is free software: you are free to change and redistribute it.
There is NO WARRANTY, to the extent permitted by law.

Originally written by Hrvoje Niksic <hniksic@xemacs.org>.
Please send bug reports and questions to <bug-wget@gnu.org>.
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ openssl version
OpenSSL 3.5.5 27 Jan 2026 (Library: OpenSSL 3.5.5 27 Jan 2026)
reyne@reyne-VirtualBox:/run/media/reyne/VBox_GAs_7.2.6$ 
```
