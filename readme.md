# Appimage For Wine
## ���
AppImage ��һ�ְ�Ӧ�ô���ɵ�һ�ļ��ĸ�ʽ�������ڸ��ֲ�ͬ��Ŀ��ϵͳ������ϵͳ(Debian��RHEL��)�����а�(Ubuntu��Deepin��)�������У������һ���޸ġ�
����Appimage�����Ѽ���ִ�г������������ŵ�һ���ļ������档Ȼ�����ÿ�ִ���ļ�������·����ʹ�ó����ִ�в���������ǰϵͳ���������ļ��о��൱�ڳ���ִ��ʱ��ϵͳ������Ȼ���ļ���ѹ�����������Appimage��
����Appimageʱ���ѹ���ļ��У�Ȼ���������еĿ�ִ�нű���
## Wine
Wine ����Wine Is Not an Emulator�� �ĵݹ���д����һ���ܹ��ڶ��� POSIX-compliant ����ϵͳ������ Linux��Mac OSX �� BSD �ȣ������� Windows Ӧ�õļ��ݲ㡣
��Wine��������Ƚ϶࣬���ұ��밲װi386�ܹ�����ִ��Win32λ��������ܴ����һ��Appimage����ʡȥ��װ�����õȷ������衣
## AppDir
�ȴ������Appimage���ļ��У�Ȼ��������Ҫ�Ѽ�Wine�Ŀ�ִ�г���
��Դ���صİ���װ�󣬿�ִ���ļ������ֲ���ϵͳ��ͬ·�������������ֶ����룬ָ��prefix�����Ѽ�Wine�������ļ���
���ҷ���PlayOnLinux�ṩ����õ�[ѹ����](https://www.playonlinux.com/wine/binaries/linux-x86/)���������°汾��Wine -- PlayOnLinux-wine-3.5-linux-x86.pol��
��ѹ�鿴�ļ�Ŀ¼��

![](/images/1.png)
ɾ���޹ص�files��playonlinuxĿ¼����WineĿ¼�Ƶ�AppDir�£�

![](/images/2.png)

## �Ѽ�ϵͳ����
������������Wine�����п�ִ���ļ�������������û��ϵͳ�������˴δ������wine32��������Ҫ��װi386ϵͳ������
��ѡ����apt����Ѱ��������
```shell=
sudo apt install wine32:i386

```
�õ�������
> libxdmcp6:i386 libwebp6:i386 libcomerr2:i386 libkrb5-3:i386 libgssapi-krb5-2:i386 libsnappy1v5:i386 libopenjp2-7:i386 libcups2:i386 libdbus-1-3:i386 libdrm-nouveau2:i386 libsasl2-modules-db:i386 libldap-2.4-2:i386 libcrystalhd3:i386 liblcms2-2:i386 libopenal1:i386 va-driver-all:i386 libsndio6.1:i386 libswresample2:i386 libtxc-dxtn-s2tc:i386 libsystemd0:i386 libpciaccess0:i386 libxcb-present0:i386 libglapi-mesa:i386 libpixman-1-0:i386 libxrender1:i386 libicu57:i386 libelf1:i386 libogg0:i386 libgpg-error0:i386 libbsd0:i386 zlib1g:i386 libwrap0:i386 libavahi-common-data:i386 libgmp10:i386 libavahi-common3:i386 libvdpau1:i386 libncurses5:i386 libmp3lame0:i386 libc6:i386 libxcursor1:i386 libnuma1:i386 libk5crypto3:i386 libxcb-shm0:i386 libsasl2-2:i386 libxcb-render0:i386 gcc-6-base:i386 libwavpack1:i386 vdpau-driver-all:i386 libx11-6:i386 libopus0:i386 libexpat1:i386 libvpx4:i386 libltdl7:i386 libxshmfence1:i386 libodbc1:i386 libllvm3.9:i386 libgcc1:i386 libsm6:i386 libdrm-amdgpu1:i386 libtiff5:i386 libva1:i386 libxau6:i386 libxcomposite1:i386 libx264-148:i386 libsasl2-modules:i386 libpulse0:i386 libmpg123-0:i386 libx265-95:i386 libxvidcore4:i386 libtinfo5:i386 libxcb1:i386 libxtst6:i386 libxi6:i386 libkrb5support0:i386 libzvbi0:i386 libpcre3:i386 libvorbisenc2:i386 libcap2:i386 libxinerama1:i386 libspeex1:i386 libuuid1:i386 libvdpau-va-gl1:i386 libgcrypt20:i386 libjack-jackd2-0:i386 libavcodec57:i386 libkeyutils1:i386 libselinux1:i386 liblz4-1:i386 libxrandr2:i386 libavutil55:i386 libtheora0:i386 libsndfile1:i386 libdrm2:i386 libgomp1:i386 libglu1-mesa:i386 libxfixes3:i386 wine32:i386 libsoxr0:i386 libwebpmux2:i386 libhogweed4:i386 libfontconfig1:i386 libasyncns0:i386 libgl1-mesa-dri:i386 libspeexdsp1:i386 libdb5.3:i386 libosmesa6:i386 libasound2:i386 libasound2-plugins:i386 libgpm2:i386 libxxf86vm1:i386 libnettle6:i386 libxdamage1:i386 libshine3:i386 libgl1-mesa-glx:i386 libjbig0:i386 libxml2:i386 libflac8:i386 libidn11:i386 libgnutls30:i386 libedit2:i386 libdrm-intel1:i386 libpcap0.8:i386 libtwolame0:i386 libfreetype6:i386 libgsm1:i386 libva-x11-1:i386 libffi6:i386 libp11-kit0:i386 libdrm-radeon1:i386 libva-drm1:i386 mesa-vdpau-drivers:i386 ocl-icd-libopencl1:i386 libvorbis0a:i386 libssl1.1:i386 libtasn1-6:i386 libice6:i386 i965-va-driver:i386 libcairo2:i386 liblzma5:i386 libstdc++6:i386 libavahi-client3:i386 libxcb-glx0:i386 libxcb-dri2-0:i386 libsensors4:i386 libsamplerate0:i386 libxcb-dri3-0:i386 libjpeg62-turbo:i386 libavresample3:i386 libx11-xcb1:i386 libxcb-sync1:i386 libwine:i386 mesa-va-drivers:i386 libxslt1.1:i386 libxext6:i386 libpng16-16:i386

��������������
```shell=
apt download files
```
������deb������AppDir/debs�У�ʹ��dpkg��ѹ�ļ���
```shell=
find ./debs -exec dpkg -x {} ./ \;
```
ִ���������deb���е����ݶ���ѹ�����ˣ�

![](/images/3.png)
## ld-linux.so
���Ǹ�����ض�̬��Ľ��������ڳ�������Ӳ����ָ���ģ�

![](/images/4.png)

����32λ������/lib/ld-linux.so.2,64λ��/lib64/ld-linux-x86-64.so.2��
���ļ�������libc6�У������Ѿ���ѹ��libc6:i386.deb��ld-linux.so.2 �� AppDir/lib �С�
��һ���취�ǣ��ֶ����� AppDir/lib/ld-linux.so.2 �� /lib�����������Ҫÿ��ʹ�������غ�ִ�д˲�����

����һ����ʽ�Ǹı��ִ���ļ���Ӳ���������·����ִ�У�
```shell=
cd AppDir/bin
sed -i -e 's|/lib/ld-linux.so.2|/tmp/ld-linux.so.2|g' ./*
```
�ı�����·��Ϊ/tmp/ld-linux.so.2��Ȼ����ִ��Appimageʱ������������/tmp/ld-linux.so.2 ָ�� AppDir/lib/ld-linux.so.2��
## ���
��дAppRun��
```shell=
#!/bin/bash
HERE="$(dirname "$(readlink -f "${0}")")"

export LD_LIBRARY_PATH="$HERE/usr/lib":$LD_LIBRARY_PATH
export LD_LIBRARY_PATH="$HERE/usr/lib/i386-linux-gnu":$LD_LIBRARY_PATH
export LD_LIBRARY_PATH="$HERE/lib":$LD_LIBRARY_PATH
export LD_LIBRARY_PATH="$HERE/lib/i386-linux-gnu":$LD_LIBRARY_PATH

LD_SO="/tmp/ld-linux.so.2"

if [ ! -e $LD_SO ] ; then
  echo "Create ld-linux.so.2"
  ln -s $(readlink -f "$HERE"/lib/ld-linux.so.2 ) $LD_SO
fi

function finish {
  echo "Wine Cleaning up"
  rm $LD_SO
}
trap finish EXIT

"$HERE/bin/wine" "$@"
```
��ʱWine�Ѿ�����ִ�У���ȫ������ϵͳ������ִ�д�����
```shell=
export ARCH=x86_64; appimagetool-x86_64.AppImage AppDir
```
�����Wine��Appimage�����
