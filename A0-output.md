1. Command name and purpose:
sudo wget https://github.com/shiftkey/desktop/releases/download/release-3.1.1-linux1/GitHubDesktop-linux-3.1.1-linux1.deb
--2023-02-06 21:16:06--  https://github.com/shiftkey/desktop/releases/download/release-3.1.1-linux1/GitHubDesktop-linux-3.1.1-linux1.deb
Resolving github.com (github.com)... 140.82.114.4
Connecting to github.com (github.com)|140.82.114.4|:443... connected.
HTTP request sent, awaiting response... 302 Found
Location: https://objects.githubusercontent.com/github-production-release-asset-2e65be/93324270/3274740f-cbaa-45ea-ad5b-c7610707d477?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20230207%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230207T021606Z&X-Amz-Expires=300&X-Amz-Signature=d3eb40901642aff6780f68db0bdaa512887ba32f7ed1984cb04cd62acc6e2bf2&X-Amz-SignedHeaders=host&actor_id=0&key_id=0&repo_id=93324270&response-content-disposition=attachment%3B%20filename%3DGitHubDesktop-linux-3.1.1-linux1.deb&response-content-type=application%2Foctet-stream [following]
--2023-02-06 21:16:07--  https://objects.githubusercontent.com/github-production-release-asset-2e65be/93324270/3274740f-cbaa-45ea-ad5b-c7610707d477?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20230207%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230207T021606Z&X-Amz-Expires=300&X-Amz-Signature=d3eb40901642aff6780f68db0bdaa512887ba32f7ed1984cb04cd62acc6e2bf2&X-Amz-SignedHeaders=host&actor_id=0&key_id=0&repo_id=93324270&response-content-disposition=attachment%3B%20filename%3DGitHubDesktop-linux-3.1.1-linux1.deb&response-content-type=application%2Foctet-stream
Resolving objects.githubusercontent.com (objects.githubusercontent.com)... 185.199.108.133, 185.199.110.133, 185.199.109.133, ...
Connecting to objects.githubusercontent.com (objects.githubusercontent.com)|185.199.108.133|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 76277604 (73M) [application/octet-stream]
Saving to: ‘GitHubDesktop-linux-3.1.1-linux1.deb’
GitHubDesktop-linux 100%[===================>]  72.74M  9.90MB/s    in 7.2s    
2023-02-06 21:16:14 (10.1 MB/s) - ‘GitHubDesktop-linux-3.1.1-linux1.deb’ saved [76277604/76277604]
riley@riley-VirtualBox:~$ ls
]          Downloads                             Pictures  Templates
Desktop    GitHubDesktop-linux-3.1.1-linux1.deb  Public    Videos
Documents  Music                                 snap
riley@riley-VirtualBox:~$ pwd

/home/riley
Clear
riley@riley-VirtualBox:~$ sudo apt update
[sudo] password for riley: 
Hit:1 http://us.archive.ubuntu.com/ubuntu jammy InRelease
Get:2 http://security.ubuntu.com/ubuntu jammy-security InRelease [110 kB]
Get:3 http://us.archive.ubuntu.com/ubuntu jammy-updates InRelease [114 kB]
Get:4 http://us.archive.ubuntu.com/ubuntu jammy-backports InRelease [107 kB]
Get:5 http://security.ubuntu.com/ubuntu jammy-security/main amd64 DEP-11 Metadata [41.5 kB]
Get:6 http://security.ubuntu.com/ubuntu jammy-security/universe amd64 DEP-11 Metadata [13.3 kB]
Get:7 http://us.archive.ubuntu.com/ubuntu jammy-updates/main amd64 DEP-11 Metadata [101 kB]
Get:8 http://us.archive.ubuntu.com/ubuntu jammy-updates/universe amd64 DEP-11 Metadata [265 kB]
Get:9 http://us.archive.ubuntu.com/ubuntu jammy-updates/multiverse amd64 DEP-11 Metadata [940 B]
Get:10 http://us.archive.ubuntu.com/ubuntu jammy-backports/main amd64 DEP-11 Metadata [7,952 B]
Get:11 http://us.archive.ubuntu.com/ubuntu jammy-backports/universe amd64 DEP-11 Metadata [12.5 kB]
Fetched 774 kB in 0s (1,661 kB/s)                                           
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
39 packages can be upgraded. Run 'apt list --upgradable' to see them.
riley@riley-VirtualBox:~$ sudo apt install gcc

Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
gcc is already the newest version (4:11.2.0-1ubuntu1).
The following packages were automatically installed and are no longer required:
  chromium-codecs-ffmpeg-extra gstreamer1.0-vaapi i965-va-driver
  intel-media-va-driver libaacs0 libaom3 libass9 libavcodec58 libavformat58
  libavutil56 libbdplus0 libblas3 libbluray2 libbs2b0 libchromaprint1
  libcodec2-1.0 libdav1d5 libflashrom1 libflite1 libftdi1-2 libgme0 libgsm1
  libgstreamer-plugins-bad1.0-0 libigdgmm12 liblilv-0-0 libmfx1 libmysofa1
  libnorm1 libopenmpt0 libpgm-5.3-0 libpostproc55 librabbitmq4 librubberband2
  libserd-0-0 libshine3 libsnappy1v5 libsord-0-0 libsratom-0-0
  libsrt1.4-gnutls libssh-gcrypt-4 libswresample3 libswscale5 libudfread0
  libva-drm2 libva-wayland2 libva-x11-2 libva2 libvdpau1 libvidstab1.1
  libx265-199 libxvidcore4 libzimg2 libzmq5 libzvbi-common libzvbi0
  mesa-va-drivers mesa-vdpau-drivers pocketsphinx-en-us va-driver-all
  vdpau-driver-all
Use 'sudo apt autoremove' to remove them.
0 upgraded, 0 newly installed, 0 to remove and 39 not upgraded.
riley@riley-VirtualBox:~$ sudo apt install build-essential
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
build-essential is already the newest version (12.9ubuntu3).
The following packages were automatically installed and are no longer required:
  chromium-codecs-ffmpeg-extra gstreamer1.0-vaapi i965-va-driver
  intel-media-va-driver libaacs0 libaom3 libass9 libavcodec58 libavformat58
  libavutil56 libbdplus0 libblas3 libbluray2 libbs2b0 libchromaprint1
  libcodec2-1.0 libdav1d5 libflashrom1 libflite1 libftdi1-2 libgme0 libgsm1
  libgstreamer-plugins-bad1.0-0 libigdgmm12 liblilv-0-0 libmfx1 libmysofa1
  libnorm1 libopenmpt0 libpgm-5.3-0 libpostproc55 librabbitmq4 librubberband2
  libserd-0-0 libshine3 libsnappy1v5 libsord-0-0 libsratom-0-0
  libsrt1.4-gnutls libssh-gcrypt-4 libswresample3 libswscale5 libudfread0
  libva-drm2 libva-wayland2 libva-x11-2 libva2 libvdpau1 libvidstab1.1
  libx265-199 libxvidcore4 libzimg2 libzmq5 libzvbi-common libzvbi0
  mesa-va-drivers mesa-vdpau-drivers pocketsphinx-en-us va-driver-all
  vdpau-driver-all
Use 'sudo apt autoremove' to remove them
0 upgraded, 0 newly installed, 0 to remove and 39 not upgraded.
