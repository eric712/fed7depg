# fed7depg
# fed7deps.ce7
# Written by Eric Matteson
# permission is granted to copy this file fed7deps.ce7
# and to publish it on the Internet.
# This batch file first copies dependencies from
# the 32-bit Fedora 7 Linux DVD to current directory
# on the hard drive and then
# uses rpm to install those 32-bit dependencies into the
# current 64-bit Linux.
# before running this file  chmod 755 fed7deps.ce7
# df -h should show the Fedora 7 DVD mounted as
# /run/media/taxpayer/Fedora 7 i386 DVD
# in order to use this batch file and you must become root user
# because rpm requires root
# ./fed7deps.ce7
# to install 32-bit dependencies while 32-bit Fedora 7 is in DVD drive.
# fed7deps.ce7 for 32-bit dependencies from 32-bit Fedora 7 balloon Linux
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/rootfiles-8.1-1.1.1.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/redhat-rpm-config-8.0.45-15.fc7.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libgcc-4.1.2-12.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/tzdata-2007e-1.fc7.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/basesystem-8.1-1.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/m17n-db-1.3.4-9.fc7.noarch.rpm ./ && echo copy
# --
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/glibc-common-2.6-3.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/glibc-2.6-3.i386.rpm ./ && echo copy
# --
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libattr-2.4.32-2.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libcap-1.10-29.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libstdc++-4.1.2-12.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/pcre-7.0-2.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libsepol-2.0.3-1.fc7.i386.rpm ./ && echo copy
# --
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/mcstrans-0.2.5-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libselinux-2.0.13-1.fc7.i386.rpm ./ && echo copy
# --
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/glibc-headers-2.6-3.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/glibc-devel-2.6-3.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/zlib-1.2.3-10.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/zlib-devel-1.2.3-10.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/
# was libffi
# was bash-completion
# was xz-libs
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libxml2-2.6.28-2.i386.rpm ./ && echo copy
# was shared-mime-info
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libgomp-4.1.2-12.i386.rpm ./ && echo copy
# --
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gamin-0.1.8-5.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/glib2-2.12.11-1.fc7.i386.rpm ./ && echo copy
# --
# was pkgconfig
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/pkgconfig-0.21-5.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libxml2-devel-2.6.28-2.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/glib2-devel-2.12.11-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/expat-1.95.8-9.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXau-1.0.3-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-filesystem-7.1-2.fc6.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-proto-devel-7.2-9.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXau-devel-1.0.3-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXdmcp-1.0.2-2.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXdmcp-devel-1.0.2-2.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libX11-1.0.3-8.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libX11-devel-1.0.3-8.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/ncurses-5.6-6.20070303.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libICE-1.0.3-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libICE-devel-1.0.3-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libstdc++-devel-4.1.2-12.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXfixes-4.0.3-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXfixes-devel-4.0.3-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXdamage-1.1.1-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXdamage-devel-1.1.1-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libdrm-2.3.0-5.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libdrm-devel-2.3.0-5.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXext-1.0.1-2.1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXext-devel-1.0.1-2.1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libexif-0.6.13-3.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXxf86vm-1.0.1-3.1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXxf86vm-devel-1.0.1-3.1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/ncurses-devel-5.6-6.20070303.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/elfutils-libelf-0.127-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/bzip2-libs-1.0.4-10.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/bzip2-devel-1.0.4-10.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/mesa-libGL-6.5.2-10.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/mesa-libGL-devel-6.5.2-10.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/mesa-libGLU-6.5.2-10.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/mesa-libGLU-devel-6.5.2-10.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libSM-1.0.2-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libSM-devel-1.0.2-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/alsa-lib-1.0.14-0.4.rc3.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/alsa-lib-devel-1.0.14-0.4.rc3.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libogg-1.1.3-3.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libvorbis-1.1.2-2.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/flac-1.1.4-4.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/readline-5.2-4.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/readline-devel-5.2-4.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libgpg-error-1.4-2.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libgpg-error-devel-1.4-2.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libgcrypt-1.2.4-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libgcrypt-devel-1.2.4-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gnutls-1.4.5-2.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gnutls-devel-1.4.5-2.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libieee1284-0.2.9-4.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/giflib-4.1.3-8.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/audit-libs-1.5.3-1.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/dbus-1.0.2-4.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/dbus-devel-1.0.2-4.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libFS-1.0.0-3.1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/popt-1.10.2-46.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/freetype-2.3.4-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/freetype-devel-2.3.4-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libfontenc-1.0.4-2.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libfontenc-devel-1.0.4-2.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXfont-1.2.8-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXfont-devel-1.2.8-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-font-utils-7.1-5.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/ttmkfdir-3.0.9-24.fc7.i386.rpm ./ && echo copy
# --
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-xfs-1.0.2-3.1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/chkfontpath-1.10.1-1.1.i386.rpm ./ && echo copy
# --
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-misc-7.1-3.fc7.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-base-7.1-3.fc7.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libjpeg-6b-37.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libjpeg-devel-6b-37.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libpng-1.2.16-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libpng-devel-1.2.16-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXcomposite-0.3.1-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXcomposite-devel-0.3.1-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXi-1.0.4-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXi-devel-1.0.4-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXinerama-1.0.2-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXinerama-devel-1.0.2-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXrender-0.9.2-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXrender-devel-0.9.2-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXrandr-1.2.0-3.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXrandr-devel-1.2.0-3.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libxslt-1.1.20-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libxslt-devel-1.1.20-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXt-1.0.4-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXt-devel-1.0.4-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXv-1.0.3-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXv-devel-1.0.3-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libtiff-3.8.2-7.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libtiff-devel-3.8.2-7.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/lcms-1.16-3.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/tcp_wrappers-libs-7.6-44.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXtst-1.0.1-3.1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/freeglut-2.4.0-11.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/nspr-4.6.6-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/nspr-devel-4.6.6-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/db4-4.5.20-5.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/cyrus-sasl-lib-2.1.22-6.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/cyrus-sasl-devel-2.1.22-6.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libtool-ltdl-1.5.22-11.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/unixODBC-2.2.12-2.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/sane-backends-libs-1.0.18-6.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libpcap-0.9.5-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/isdn4k-utils-3.2-54.fc7.i386.rpm ./ && echo copy
# duplicate cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/audit-libs-1.5.3-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fontconfig-2.4.2-3.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fontconfig-devel-2.4.2-3.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXcursor-1.1.8-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXcursor-devel-1.1.8-1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gstreamer-tools-0.10.12-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gstreamer-0.10.12-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/liboil-0.3.10-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXft-2.1.12-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libthai-0.1.7-5.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libtheora-1.0alpha7-2.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/keyutils-libs-1.2-2.fc6.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/keyutils-libs-devel-1.2-2.fc6.i386.rpm ./ && echo copy
# --
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/krb5-libs-1.6-6.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libsepol-devel-2.0.3-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libselinux-devel-2.0.13-1.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/krb5-devel-1.6-6.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gettext-0.16.1-8.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/cups-libs-1.2.10-10.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/openssl-0.9.8b-12.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/openssl-devel-0.9.8b-12.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/atk-1.18.0-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gmp-4.1.4-12.3.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/jasper-1.900.1-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libIDL-0.8.8-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libIDL-devel-0.8.8-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/ORBit2-2.14.7-3.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/dbus-glib-0.73-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/cracklib-2.8.9-10.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/pam-0.99.7.1-5.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/pam-devel-0.99.7.1-5.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/pam_krb5-2.2.11-1.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/pam_passwdqc-1.0.2-1.2.2.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libidn-0.6.8-4.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libidn-devel-0.6.8-4.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/imake-1.0.2-4.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/autoconf-2.61-8.fc7.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/automake14-1.4p6-15.fc7.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/pcsc-lite-libs-1.3.3-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/SDL-1.2.11-2.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/cdparanoia-libs-alpha9.8-27.2.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libiptcdata-1.0.2-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libmpcdec-1.2.2-4.fc6.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libcroco-0.6.1-2.1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libgsf-1.14.3-4.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libraw1394-1.2.1-7.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libavc1394-0.5.3-1.fc6.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libdv-1.0.0-1.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/hal-libs-0.5.9-8.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libiec61883-1.1.0-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libbonobo-2.18.0-3.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/popt-1.10.2-46.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/avahi-0.6.17-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libacl-2.2.39-3.1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/speex-1.2-0.2.beta1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libshout-2.2.2-1.fc6.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/taglib-1.4-5.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/wavpack-4.41-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/urw-fonts-2.3-6.1.1.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libgsf-devel-1.14.3-4.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/cairo-1.4.4-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/pango-1.16.4-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gtk2-2.10.11-7.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libwmf-0.2.8.4-14.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/SDL-devel-1.2.11-2.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gstreamer-plugins-base-0.10.12-2.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libgcj-4.1.2-12.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libgcj-devel-4.1.2-12.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/librsvg2-2.16.1-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/sqlite-3.3.13-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/pulseaudio-lib-0.9.5-5.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/nss-3.11.5-2.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/nss-devel-3.11.5-2.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/openldap-2.3.34-0.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/openldap-devel-2.3.34-0.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/curl-7.16.2-1.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/curl-devel-7.16.2-1.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/pam_pkcs11-0.5.3-24.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/GConf2-2.18.0.1-2.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gnome-vfs2-2.18.1-4.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libgnome-2.18.0-4.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gnome-keyring-0.8-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libsoup-2.2.100-1.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gstreamer-plugins-good-0.10.5-6.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/elfutils-libs-0.127-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXmu-1.0.3-1.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXmu-devel-1.0.3-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXft-devel-2.1.12-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/cairo-devel-1.4.4-1.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/hal-devel-0.5.9-8.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libmng-1.0.9-5.1.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/kde-settings-3.5-28.fc7.1.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/kde-settings-kdm-3.5-28.fc7.1.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/qt-3.3.8-4.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libmng-devel-1.0.9-5.1.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/bitmap-fonts-0.3-5.1.2.fc7.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXxf86misc-1.0.1-3.1.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXxf86misc-devel-1.0.1-3.1.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-75dpi-7.1-3.fc7.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-100dpi-7.1-3.fc7.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-ISO8859-1-75dpi-7.1-3.fc7.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-ISO8859-1-100dpi-7.1-3.fc7.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/atk-devel-1.18.0-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/pango-devel-1.16.4-1.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/gtk2-devel-2.10.11-7.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXfont-1.2.8-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXfont-devel-1.2.8-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXfontcache-1.0.4-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/libXfontcache-devel-1.0.4-1.fc7.i386.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-ISO8859-2-1.0-17.1.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-truetype-7.1-3.fc7.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/qt-devel-3.3.8-4.fc7.i386.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/bitmap-fonts-0.3-5.1.2.fc7.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/dejavu-lgc-fonts-2.15-1.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/liberation-fonts-0.1-9.fc7.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-ISO8859-2-75dpi-1.0-17.1.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-ISO8859-2-100dpi-1.0-17.1.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-ISO8859-1-75dpi-7.1-3.fc7.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-ISO8859-1-100dpi-7.1-3.fc7.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-ISO8859-9-75dpi-7.1-3.fc7.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-ISO8859-9-100dpi-7.1-3.fc7.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-75dpi-7.1-3.fc7.noarch.rpm ./ && echo copy
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-100dpi-7.1-3.fc7.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-bengali-2.1.5-1.fc7.noarch.rpm ./ && echo copy
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-cyrillic-7.1-3.fc7.noarch.rpm ./ && echo copy
# -----------------------------------------------------------
# adding additional fonts here ********************
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-arabic-2.0-5.fc7.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-chinese-3.03-4.fc7.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-gujarati-2.1.5-1.fc7.noarch.rpm ./ && echo font
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-hebrew-0.100-4.1.1.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-hindi-2.1.5-1.fc7.noarch.rpm ./ && echo font
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-japanese-0.20061016-6.fc7.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-kannada-2.1.5-1.fc7.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-KOI8-R-100dpi-1.0-9.1.1.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-KOI8-R-1.0-9.1.1.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-KOI8-R-75dpi-1.0-9.1.1.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-korean-1.0.11-9.1.1.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-malayalam-2.1.5-1.fc7.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-oriya-2.1.5-1.fc7.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-punjabi-2.1.5-1.fc7.noarch.rpm ./ && echo font
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-sinhala-0.2.2-1.fc7.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-tamil-2.1.5-1.fc7.noarch.rpm ./ && echo font
 cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/fonts-telugu-2.1.5-1.fc7.noarch.rpm ./ && echo font
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/ghostscript-fonts-5.50-16.fc7.noarch.rpm ./ && echo font
# cp /run/media/taxpayer/Fedora\ 7\ i386\ DVD/Fedora/xorg-x11-fonts-Type1-7.1-3.fc7.noarch.rpm ./ && echo font
# end of copying
# begin rpm install portion 0214.0230.0292
 rpm -ivh --ignoreos --force rootfiles-8.1-1.1.1.noarch.rpm && echo i
 rpm -ivh --ignoreos --force redhat-rpm-config-8.0.45-15.fc7.noarch.rpm && echo i
 rpm -ivh --ignoreos --force libgcc-4.1.2-12.i386.rpm && echo i
 rpm -ivh --ignoreos --force tzdata-2007e-1.fc7.noarch.rpm && echo i
 rpm -ivh --ignoreos --force basesystem-8.1-1.noarch.rpm && echo i
 rpm -ivh --ignoreos --force m17n-db-1.3.4-9.fc7.noarch.rpm && echo i
# ------
 rpm -ivh --nodeps --ignoreos --force glibc-common-2.6-3.i386.rpm && echo i
 rpm -ivh --nodeps --ignoreos --force glibc-2.6-3.i386.rpm && echo i
# warning: /etc/localtime created as /etc/localtime.rpmnew
# warning: /etc/nsswitch.conf created as /etc/nsswitch.conf.rpmnew
# line 0229.0219.0240
 rpm -ivh --ignoreos --force libattr-2.4.32-2.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libcap-1.10-29.i386.rpm && echo i
 rpm -ivh --ignoreos --force libstdc++-4.1.2-12.i386.rpm && echo i
 rpm -ivh --ignoreos --force pcre-7.0-2.i386.rpm && echo i
 rpm -ivh --ignoreos --force libsepol-2.0.3-1.fc7.i386.rpm && echo i
# libselinux needs libsepol.so.1   setransd
# ------
 rpm -ivh --nodeps --ignoreos --force mcstrans-0.2.5-1.fc7.i386.rpm && echo i
 rpm -ivh --nodeps --ignoreos --force libselinux-2.0.13-1.fc7.i386.rpm && echo i
# rpm -ivh --nodeps --ignoreos --force mcstrans-0.2.5-1.fc7.i386.rpm && echo i
# rpm -ivh --nodeps --ignoreos --force libselinux-2.0.13-1.fc7.i386.rpm && echo i
# -------
# Missing dependency nss-softokn-freebl would be here.
 rpm -ivh --nodeps --ignoreos --force glibc-common-2.6-3.i386.rpm && echo i
 rpm -ivh --nodeps --ignoreos --force glibc-2.6-3.i386.rpm && echo i
# ------
# rpm -ivh --ignoreos --force glibc-common-2.6-3.i386.rpm && echo i
# glibc > 2.6 conflicts with glibc-common-2.6-3.i386
# rpm -ivh --ignoreos --force glibc-2.6-3.i386.rpm && echo i failed
# glibc > 2.6 conflicts with (installed) glibc-common-2.6-3.i386
 rpm -ivh --ignoreos --force libstdc++-4.1.2-12.i386.rpm && echo i
# kernel-headers of invalid architecture is needed by glibc-headers-2.6-3.i386
 rpm -ivh --nodeps --ignoreos --force glibc-headers-2.6-3.i386.rpm && echo i
 rpm -ivh --ignoreos --force glibc-devel-2.6-3.i386.rpm && echo i
# xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
# xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx 0302
 rpm -ivh --ignoreos --force zlib-1.2.3-10.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force zlib-devel-1.2.3-10.fc7.i386.rpm && echo i
# need libffi
# need bash-completion
# need xz-libs
 rpm -ivh --ignoreos --force libxml2-2.6.28-2.i386.rpm && echo i
# need shared-mime-info
 rpm -ivh --ignoreos --force libgomp-4.1.2-12.i386.rpm && echo i
# ----
 rpm -ivh --nodeps --ignoreos --force gamin-0.1.8-5.fc7.i386.rpm && echo i
 rpm -ivh --nodeps --ignoreos --force glib2-2.12.11-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force gamin-0.1.8-5.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force glib2-2.12.11-1.fc7.i386.rpm && echo i
# ----
# need pkgconfig
 rpm -ivh --ignoreos --force pkgconfig-0.21-5.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libxml2-devel-2.6.28-2.i386.rpm && echo i
 rpm -ivh --ignoreos --force glib2-devel-2.12.11-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force expat-1.95.8-9.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXau-1.0.3-1.fc7.i386.rpm && echo i
 rpm -ivh xorg-x11-filesystem-7.1-2.fc6.noarch.rpm && echo i
# error xorg-x11-proto-devel conflicts with mesa-libGL-devel
# override on 21
 rpm -ivh --nodeps --ignoreos --force xorg-x11-proto-devel-7.2-9.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXau-devel-1.0.3-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXdmcp-1.0.2-2.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXdmcp-devel-1.0.2-2.fc7.i386.rpm && echo i
# rpm -ivh
# rpm -ivh
# libX11 < 1.5 conflicts with SDL-1.2.14-6.el6.x86_64
 rpm -ivh --nodeps --ignoreos --force libX11-1.0.3-8.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libX11-devel-1.0.3-8.fc7.i386.rpm && echo i
 rpm -ivh --nodeps --ignoreos --force ncurses-5.6-6.20070303.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libICE-1.0.3-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libICE-devel-1.0.3-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libstdc++-devel-4.1.2-12.i386.rpm && echo i
# rpm -ivh
 rpm -ivh --ignoreos --force libXfixes-4.0.3-1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXfixes-devel-4.0.3-1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXdamage-1.1.1-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXdamage-devel-1.1.1-1.fc7.i386.rpm && echo i
# rpm -ivh
 rpm -ivh --ignoreos --force libdrm-2.3.0-5.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libdrm-devel-2.3.0-5.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXext-1.0.1-2.1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXext-devel-1.0.1-2.1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libexif-0.6.13-3.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXxf86vm-1.0.1-3.1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXxf86vm-devel-1.0.1-3.1.i386.rpm && echo i
 rpm -ivh --ignoreos --force ncurses-devel-5.6-6.20070303.fc7.i386.rpm && echo i
# rpm -ivh
# elfutils > fc7 conflicts with elfutils-libelf
# elfutils-libs > fc7 conflicts with elfutils-libelf
# override on 21
 rpm -ivh --nodeps --ignoreos --force elfutils-libelf-0.127-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force bzip2-libs-1.0.4-10.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force bzip2-devel-1.0.4-10.fc7.i386.rpm && echo i
# rpm -ivh
# libselinux.so.1 is needed by mesa-libGL
 rpm -ivh --ignoreos --force mesa-libGL-6.5.2-10.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force mesa-libGL-devel-6.5.2-10.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force mesa-libGLU-6.5.2-10.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force mesa-libGLU-devel-6.5.2-10.fc7.i386.rpm && echo i
# rpm -ivh
 rpm -ivh --ignoreos --force libSM-1.0.2-1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libSM-devel-1.0.2-1.i386.rpm && echo i
 rpm -ivh --ignoreos --force alsa-lib-1.0.14-0.4.rc3.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force alsa-lib-devel-1.0.14-0.4.rc3.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libogg-1.1.3-3.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libvorbis-1.1.2-2.fc7.i386.rpm && echo i
# flac-libs  is obseleted by flac
# flac < 1.2.1-11 is obseleted by (installed) flac-libs-1.3.0-5.fc21.x86_64
# override on 21
 rpm -ivh --nodeps --ignoreos --force flac-1.1.4-4.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force readline-5.2-4.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force readline-devel-5.2-4.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libgpg-error-1.4-2.i386.rpm && echo i
 rpm -ivh --ignoreos --force libgpg-error-devel-1.4-2.i386.rpm && echo i
 rpm -ivh --ignoreos --force libgcrypt-1.2.4-1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libgcrypt-devel-1.2.4-1.i386.rpm && echo i
# rpm -ivh
 rpm -ivh --ignoreos --force gnutls-1.4.5-2.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force gnutls-devel-1.4.5-2.fc7.i386.rpm && echo i
# libjpeg.so.62 is needed by lcms
# libtiff.so.3 is needed by lcms
# delay rpm -ivh --ignoreos --force lcms-1.16-3.i386.rpm && echo i
 rpm -ivh --ignoreos --force libieee1284-0.2.9-4.i386.rpm && echo i
 rpm -ivh --ignoreos --force giflib-4.1.3-8.i386.rpm && echo i
# rpm -ivh
 rpm -ivh --ignoreos --force audit-libs-1.5.3-1.fc7.i386.rpm && echo i
# ??? libaudit.so.0 is needed by dbus-1.0.2-4-fc7.i386
# dbus conflicts with xorg-x11-xinit
# rpm -ivh --ignoreos --force dbus-1.0.2-4.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force dbus-devel-1.0.2-4.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libFS-1.0.0-3.1.i386.rpm && echo i
 rpm -ivh --ignoreos --force popt-1.10.2-46.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force freetype-2.3.4-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force freetype-devel-2.3.4-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libfontenc-1.0.4-2.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libfontenc-devel-1.0.4-2.fc7.i386.rpm && echo i
# libfontenc.so.1 is needed by libXfont
# libfreetype.so.6 is needed by libXfont
 rpm -ivh --ignoreos --force libXfont-1.2.8-1.fc7.i386.rpm && echo i
# libXfont.so.1 is needed by libXfont-devel
# libfontenc-devel is needed by libXfont-devel
 rpm -ivh --ignoreos --force libXfont-devel-1.2.8-1.fc7.i386.rpm && echo i
# ------------
# ------------
 rpm -ivh --ignoreos --force xorg-x11-font-utils-7.1-5.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force ttmkfdir-3.0.9-24.fc7.i386.rpm && echo i
# circular dependency next 2
# libFS.so.6 is needed by xorg-x11-xfs-1:1.0.2-3.1.i386
 rpm -ivh --nodeps --ignoreos --force xorg-x11-xfs-1.0.2-3.1.i386.rpm && echo i
# xfs is needed by chkfontpath
# libpopt.so.0 is needed by chkfontpath
 rpm -ivh --nodeps --ignoreos --force chkfontpath-1.10.1-1.1.i386.rpm && echo i
# ..
 rpm -ivh --ignoreos --force xorg-x11-xfs-1.0.2-3.1.i386.rpm && echo i
 rpm -ivh --ignoreos --force chkfontpath-1.10.1-1.1.i386.rpm && echo i
# ----------
# ----------
 rpm -ivh --ignoreos --force xorg-x11-fonts-misc-7.1-3.fc7.noarch.rpm && echo i
# newer fonts-misc obsoletes this fonts-base
 rpm -ivh --nodeps --ignoreos --force xorg-x11-fonts-base-7.1-3.fc7.noarch.rpm && echo i
# libjpeg < 6b-47 is obsoleted by
# 21 override
 rpm -ivh --nodeps --ignoreos --force libjpeg-6b-37.i386.rpm && echo i
# libjpeg-devel is obsoleted by     in cen 7
 rpm -ivh --nodeps --ignoreos --force libjpeg-devel-6b-37.i386.rpm && echo i
 rpm -ivh --ignoreos --force libpng-1.2.16-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libpng-devel-1.2.16-1.fc7.i386.rpm && echo i
# rpm -ivh
 rpm -ivh --ignoreos --force libXcomposite-0.3.1-1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXcomposite-devel-0.3.1-1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXi-1.0.4-1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXi-devel-1.0.4-1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXinerama-1.0.2-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXinerama-devel-1.0.2-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXrender-0.9.2-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXrender-devel-0.9.2-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXrandr-1.2.0-3.fc7.i386.rpm && echo i
# randrproto is needed by libXrandr-devel
# rpm -ivh
# 21 override
 rpm -ivh --ignoreos --force libXrandr-devel-1.2.0-3.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libxslt-1.1.20-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libxslt-devel-1.1.20-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXt-1.0.4-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXt-devel-1.0.4-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXv-1.0.3-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXv-devel-1.0.3-1.fc7.i386.rpm && echo i
# libjpeg.so.62 is needed by libtiff
# override jpeg conflict earlier
 rpm -ivh --ignoreos --force libtiff-3.8.2-7.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libtiff-devel-3.8.2-7.fc7.i386.rpm && echo i
# lcms needs libjpeg.so.62  and  libtiff.so.3
# lcms < 1.17-3 is obseleted by (installed) lcms-libs-1.19-10.fc20.x86_64
 rpm -ivh --nodeps --ignoreos --force lcms-1.16-3.i386.rpm && echo i
 rpm -ivh --ignoreos --force tcp_wrappers-libs-7.6-44.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXtst-1.0.1-3.1.i386.rpm && echo i
 rpm -ivh --ignoreos --force freeglut-2.4.0-11.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force nspr-4.6.6-1.i386.rpm && echo i
 rpm -ivh --ignoreos --force nspr-devel-4.6.6-1.i386.rpm && echo i
# rpm -ivh
# db4 is obsoleted by      in cen 7
 rpm -ivh --nodeps --ignoreos --force db4-4.5.20-5.fc7.i386.rpm && echo i
# cyrus-sasl-lib conflicts with autofs
# rpm -ivh --ignoreos --force cyrus-sasl-lib-2.1.22-6.i386.rpm && echo i
# rpm -ivh --ignoreos --force cyrus-sasl-devel-2.1.22-6.i386.rpm && echo i
 rpm -ivh --ignoreos --force libtool-ltdl-1.5.22-11.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force unixODBC-2.2.12-2.fc7.i386.rpm && echo i
# large number of missing dependencies for sane-backends-libs
# rpm -ivh --ignoreos --force sane-backends-libs-1.0.18-6.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libpcap-0.9.5-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force isdn4k-utils-3.2-54.fc7.i386.rpm && echo i
# duplicate rpm -ivh --ignoreos --force audit-libs-1.5.3-1.fc7.i386.rpm && echo i
# rpm -ivh
 rpm -ivh --ignoreos --force fontconfig-2.4.2-3.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force fontconfig-devel-2.4.2-3.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXcursor-1.1.8-1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXcursor-devel-1.1.8-1.i386.rpm && echo i
 rpm -ivh --ignoreos --force gstreamer-tools-0.10.12-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force gstreamer-0.10.12-1.fc7.i386.rpm && echo i
# rpm -ivh
# file not found
# rpm -ivh --ignoreos --force gstreamer-devel-0.10.12-1.fc7.i386.rpm && echo i
# rpm -ivh
 rpm -ivh --ignoreos --force liboil-0.3.10-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXft-2.1.12-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libthai-0.1.7-5.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libtheora-1.0alpha7-2.fc7.i386.rpm && echo i
# rpm -ivh
 rpm -ivh --ignoreos --force keyutils-libs-1.2-2.fc6.i386.rpm && echo i
# rpm -ivh --ignoreos --force keyutils-libs-devel-1.2-2.fc6.i386.rpm && echo i
# -----
# libcom_err.so.2 is needed by krb5-libs-1.6-6.i386
# rpm -ivh --ignoreos --force krb5-libs-1.6-6.i386.rpm && echo i
 rpm -ivh --ignoreos --force libsepol-devel-2.0.3-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libselinux-devel-2.0.13-1.fc7.i386.rpm && echo i
# large number of dependencies for krb5-devel-1.6-6.i386
# rpm -ivh --ignoreos --force krb5-devel-1.6-6.i386.rpm && echo i
 rpm -ivh --ignoreos --force gettext-0.16.1-8.fc7.i386.rpm && echo i
# libjpeg.so.62 is needed by cups-libs
# libtiff.so.3 is needed by cups-libs
# 21 override
 rpm -ivh --ignoreos --force cups-libs-1.2.10-10.fc7.i386.rpm && echo i
# missing dependencies for openssl-0.9.8b-12.fc7.i386
# rpm -ivh --ignoreos --force openssl-0.9.8b-12.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force openssl-devel-0.9.8b-12.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force atk-1.18.0-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force gmp-4.1.4-12.3.i386.rpm && echo i
# unknown second error jasper
# rpm -ivh --ignoreos --force jasper-1.900.1-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libIDL-0.8.8-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libIDL-devel-0.8.8-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force ORBit2-2.14.7-3.fc7.i386.rpm && echo i
# dbus conflicts earlier
# libdbus-1.so.3 is needed by dbus-glib-0.73-1.fc7.i386
# rpm -ivh --ignoreos --force dbus-glib-0.73-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force cracklib-2.8.9-10.i386.rpm && echo i
# db4 >= 4.6.0 conflicts with pam-0.99.7.1-5.fc7.i386
# rpm -ivh --ignoreos --force pam-0.99.7.1-5.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force pam-devel-0.99.7.1-5.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force pam_krb5-2.2.11-1.i386.rpm && echo i
# 21 obsoleted rpm -ivh --ignoreos --force pam_passwdqc-1.0.2-1.2.2.i386.rpm && echo i
 rpm -ivh --ignoreos --force libidn-0.6.8-4.i386.rpm && echo i
 rpm -ivh --ignoreos --force libidn-devel-0.6.8-4.i386.rpm && echo i
# ?? rpm -ivh --ignoreos --force imake-1.0.2-4.fc7.i386.rpm && echo i
# imake is needed by autoconf-2.61-8.fc7.noarch
# autoconf conflicts with
# rpm -ivh autoconf-2.61-8.fc7.noarch.rpm && echo i
# rpm -ivh automake14-1.4p6-15.fc7.noarch.rpm && echo i
 rpm -ivh --ignoreos --force pcsc-lite-libs-1.3.3-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force SDL-1.2.11-2.i386.rpm && echo i
 rpm -ivh --ignoreos --force cdparanoia-libs-alpha9.8-27.2.i386.rpm && echo i
 rpm -ivh --ignoreos --force libiptcdata-1.0.2-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libmpcdec-1.2.2-4.fc6.i386.rpm && echo i
 rpm -ivh --ignoreos --force libcroco-0.6.1-2.1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libgsf-1.14.3-4.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libraw1394-1.2.1-7.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libavc1394-0.5.3-1.fc6.i386.rpm && echo i
 rpm -ivh --ignoreos --force libdv-1.0.0-1.fc7.i386.rpm && echo i
# libdbus-1.so.3 is needed by hal-libs
# rpm -ivh --ignoreos --force hal-libs-0.5.9-8.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libiec61883-1.1.0-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libbonobo-2.18.0-3.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force popt-1.10.2-46.fc7.i386.rpm && echo i
# libdaemon.so.0 is needed by avahi
# libdbus-1.so.3 is needed by avahi
# rpm -ivh --ignoreos --force avahi-0.6.17-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libacl-2.2.39-3.1.fc7.i386.rpm && echo i
# speex <= 1.2-0.21.rc1 conflicts with (installed) speexdsp-1.2-0.6.rc3.fc23.x86_64
 rpm -ivh --nodeps --ignoreos --force speex-1.2-0.2.beta1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libshout-2.2.2-1.fc6.i386.rpm && echo i
 rpm -ivh --ignoreos --force taglib-1.4-5.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force wavpack-4.41-1.fc7.i386.rpm && echo i
# xorg-x11-font-utils is needed by urw-fonts
 rpm -ivh --ignoreos --force urw-fonts-2.3-6.1.1.noarch.rpm && echo i
 rpm -ivh --ignoreos --force libgsf-devel-1.14.3-4.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force cairo-1.4.4-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force pango-1.16.4-1.fc7.i386.rpm && echo i
# missing dependencies or conflict for gtk2-2.10.11-7.fc7.i386
# gtk2 <= 2.21.2 conflicts with (installed) gdk-pixbuff2-2.32-1.fc23.x86_64
# gtk2 < 2.24.25-2 conflicts with (installed) gtk-update-icon-cache-3.18.2-1.fc23.x86_64
 rpm -ivh --nodeps --ignoreos --force gtk2-2.10.11-7.fc7.i386.rpm && echo i
# OK urw-fonts is needed by libwmf
# /usr/bin/update-gdk-pixbuf-loaders is needed by libwmf-0.2.8.4-14.fc7.i386
# libgdk_pixbuf-2.0.so.0 is needed by libwmf
# OK libjpeg.so.62 is needed by libwmf
 rpm -ivh --ignoreos --force libwmf-0.2.8.4-14.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force SDL-devel-1.2.11-2.i386.rpm && echo i
# libgconf-2.so.4 is needed by gstreamer-plugins-base
# libgnomevfs-2.so.0 is needed by gstreamer-plugins-base
# rpm -ivh --ignoreos --force gstreamer-plugins-base-0.10.12-2.fc7.i386.rpm && echo i
# several dependencies missing for gtk2 and libgcj
# rpm -ivh --ignoreos --force libgcj-4.1.2-12.i386.rpm && echo i
# rpm -ivh --ignoreos --force libgcj-devel-4.1.2-12.i386.rpm && echo i
# missing dependencies for librsvg2
# rpm -ivh --ignoreos --force librsvg2-2.16.1-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force sqlite-3.3.13-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force pulseaudio-lib-0.9.5-5.fc7.i386.rpm && echo i
# nss < 3.12.2.99.3-5 conflicts with host nss-softoken-freebl
# rpm -ivh --ignoreos --force nss-3.11.5-2.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force nss-devel-3.11.5-2.fc7.i386.rpm && echo i
# missing dependencies for openldap
# rpm -ivh --ignoreos --force openldap-2.3.34-0.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force openldap-devel-2.3.34-0.fc7.i386.rpm && echo i
# conflict and missing dependencies for curl
# rpm -ivh --ignoreos --force curl-7.16.2-1.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force curl-devel-7.16.2-1.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force pam_pkcs11-0.5.3-24.i386.rpm && echo i
# rpm -ivh --ignoreos --force GConf2-2.18.0.1-2.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force gnome-vfs2-2.18.1-4.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force libgnome-2.18.0-4.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force gnome-keyring-0.8-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libsoup-2.2.100-1.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force gstreamer-plugins-good-0.10.5-6.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force elfutils-libs-0.127-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXmu-1.0.3-1.fc7.i386.rpm && echo i
# xorg-x11-util-macros is needed by libXmu-devel
# rpm -ivh --ignoreos --force libXmu-devel-1.0.3-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXft-devel-2.1.12-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force cairo-devel-1.4.4-1.fc7.i386.rpm && echo i
# hal is broken
# rpm -ivh --ignoreos --force hal-devel-0.5.9-8.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libmng-1.0.9-5.1.i386.rpm && echo i
# ..
# kdelibs >= 3.5 is needed by kde-settings-3.5-28.fc7.1.noarch
# rpm -ivh --ignoreos --force kde-settings-3.5-28.fc7.1.noarch.rpm && echo i
# ..
# kde-settings-kdm-3.5-28.fc7.1.noarch.rpm requires 3 dependencies next
# kdebase-kdm--UNKNOWN-
# redhat-artwork-kde-7.0.0-9.fc7.i386.rpm
# xorg-x11-xdm-1.1.3-1.fc7.i386.rpm
# rpm -ivh --ignoreos --force kde-settings-kdm-3.5-28.fc7.1.noarch.rpm && echo i
# rpm -ivh --ignoreos --force qt-3.3.8-4.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libmng-devel-1.0.9-5.1.i386.rpm && echo i
# rpm -ivh bitmap-fonts-0.3-5.1.2.fc7.noarch.rpm && echo i
 rpm -ivh --ignoreos --force libXxf86misc-1.0.1-3.1.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXxf86misc-devel-1.0.1-3.1.i386.rpm && echo i
# rpm -ivh xorg-x11-fonts-75dpi-7.1-3.fc7.noarch.rpm && echo i
# rpm -ivh xorg-x11-fonts-100dpi-7.1-3.fc7.noarch.rpm && echo i
# rpm -ivh xorg-x11-fonts-ISO8859-1-75dpi-7.1-3.fc7.noarch.rpm && echo i
# rpm -ivh xorg-x11-fonts-ISO8859-1-100dpi-7.1-3.fc7.noarch.rpm && echo i
 rpm -ivh --ignoreos --force atk-devel-1.18.0-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force pango-devel-1.16.4-1.fc7.i386.rpm && echo i
# rpm -ivh --ignoreos --force gtk2-devel-2.10.11-7.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXfont-1.2.8-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXfont-devel-1.2.8-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXfontcache-1.0.4-1.fc7.i386.rpm && echo i
 rpm -ivh --ignoreos --force libXfontcache-devel-1.0.4-1.fc7.i386.rpm && echo i
 rpm -ivh fonts-ISO8859-2-1.0-17.1.noarch.rpm && echo i
# rpm -ivh xorg-x11-fonts-truetype-7.1-3.fc7.noarch.rpm && echo i
# rpm -ivh --ignoreos --force qt-devel-3.3.8-4.fc7.i386.rpm && echo i
# rpm -ivh bitmap-fonts-0.3-5.1.2.fc7.noarch.rpm && echo co
# rpm -ivh dejavu-lgc-fonts-2.15-1.noarch.rpm && echo i
# rpm -ivh liberation-fonts-0.1-9.fc7.noarch.rpm && echo co
 rpm -ivh fonts-ISO8859-2-75dpi-1.0-17.1.noarch.rpm && echo i
 rpm -ivh fonts-ISO8859-2-100dpi-1.0-17.1.noarch.rpm && echo i
# rpm -ivh xorg-x11-fonts-ISO8859-1-75dpi-7.1-3.fc7.noarch.rpm && echo i
# rpm -ivh xorg-x11-fonts-ISO8859-1-100dpi-7.1-3.fc7.noarch.rpm && echo i
# rpm -ivh xorg-x11-fonts-ISO8859-9-75dpi-7.1-3.fc7.noarch.rpm && echo i
# rpm -ivh xorg-x11-fonts-ISO8859-9-100dpi-7.1-3.fc7.noarch.rpm && echo i
# rpm -ivh xorg-x11-fonts-75dpi-7.1-3.fc7.noarch.rpm && echo i
# rpm -ivh xorg-x11-fonts-100dpi-7.1-3.fc7.noarch.rpm && echo i
 rpm -ivh fonts-bengali-2.1.5-1.fc7.noarch.rpm && echo i
 rpm -ivh xorg-x11-fonts-cyrillic-7.1-3.fc7.noarch.rpm && echo i
# adding additional fonts
# rpm -ivh fonts-arabic-2.0-5.fc7.noarch.rpm && echo font
 rpm -ivh fonts-chinese-3.03-4.fc7.noarch.rpm && echo font
 rpm -ivh fonts-gujarati-2.1.5-1.fc7.noarch.rpm && echo font
# rpm -ivh fonts-hebrew-0.100-4.1.1.noarch.rpm && echo font
 rpm -ivh fonts-hindi-2.1.5-1.fc7.noarch.rpm && echo font
# rpm -ivh fonts-japanese-0.20061016-6.fc7.noarch.rpm && echo font
 rpm -ivh fonts-kannada-2.1.5-1.fc7.noarch.rpm && echo font
 rpm -ivh fonts-KOI8-R-100dpi-1.0-9.1.1.noarch.rpm && echo font
 rpm -ivh fonts-KOI8-R-1.0-9.1.1.noarch.rpm && echo font
 rpm -ivh fonts-KOI8-R-75dpi-1.0-9.1.1.noarch.rpm && echo font
 rpm -ivh fonts-korean-1.0.11-9.1.1.noarch.rpm && echo font
 rpm -ivh fonts-malayalam-2.1.5-1.fc7.noarch.rpm && echo font
 rpm -ivh fonts-oriya-2.1.5-1.fc7.noarch.rpm && echo font
 rpm -ivh fonts-punjabi-2.1.5-1.fc7.noarch.rpm && echo font
# rpm -ivh fonts-sinhala-0.2.2-1.fc7.noarch.rpm && echo font
 rpm -ivh fonts-tamil-2.1.5-1.fc7.noarch.rpm && echo font
 rpm -ivh fonts-telugu-2.1.5-1.fc7.noarch.rpm && echo font
# rpm -ivh ghostscript-fonts-5.50-16.fc7.noarch.rpm && echo font
# rpm -ivh xorg-x11-fonts-Type1-7.1-3.fc7.noarch.rpm && echo font
 echo Monday May 22 2017
# end of fed7deps

