# ffmpeg_20.04-1_amd64.deb_ubuntu-20.04
ffmpeg , ubuntu 20.04 , библиотеки относимые к гую , возможно ускоряют запуск некоторых программ типа obs-studio и других которым как и видео в браузере нужна отрисовка чем быстрее тем лучше и быстрее будет происходить запуск obs и подобных. Возможно ещё может отвечать за контраст видео картинки подаваемых с таких серверов как ютуб , твитч и подобные видео хостинги так что если картинка изменилась и стала более качественной то можно не удивляться так как кодек полученный на хорошо настроенной системе будет очень качественным , а в частности это мною собранный графический стек full stack который я ранее сделал для версии убунту 20.04 после установки надо будет перезагрузить компьютер.

sudo apt purge libavcodec-dev libavutil-dev -y && sudo apt purge ffmpeg -y 

install deb package ffmpeg: https://yadi.sk/d/zP0XOL8iRJ77nw

help command

ffplay -h

ffmpeg -h

ffprobe -h

------------------------------------------------------------------------------------------------------------------------

New flags ! 2020

./configure --prefix=/usr --extra-version=1ubuntu1 --toolchain=hardened --libdir=/usr/lib/x86_64-linux-gnu --incdir=/usr/include/x86_64-linux-gnu --arch=amd64 --enable-gpl --disable-stripping --enable-avresample --disable-filter=resample --enable-avisynth --enable-gnutls --enable-ladspa --enable-libaom --enable-libass --enable-libbluray --enable-libbs2b --enable-libcaca --enable-libcdio --enable-libcodec2 --enable-libflite --enable-libfontconfig --enable-libfreetype --enable-libfribidi --enable-libgme --enable-libgsm --enable-libjack --enable-libmp3lame --enable-libmysofa --enable-libopenjpeg --enable-libopenmpt --enable-libopus --enable-libpulse --enable-librsvg --enable-librubberband --enable-libshine --enable-libsnappy --enable-libsoxr --enable-libspeex --enable-libssh --enable-libtheora --enable-libtwolame --enable-libvidstab --enable-libvorbis --enable-libvpx --enable-libwavpack --enable-libwebp --enable-libx265 --enable-libxml2 --enable-libxvid --enable-libzmq --enable-libzvbi --enable-lv2 --enable-omx --enable-openal --enable-opencl --enable-opengl --enable-sdl2 --enable-libdc1394 --enable-libdrm --enable-libiec61883 --enable-nvenc --enable-chromaprint --enable-frei0r --enable-libx264 --enable-shared --disable-x86asm

Optional + --enable-nvdec

_________________________________________________________________________________________________________________________
My build flags / флаги которые удалось поставить

./configure --prefix=/usr --libdir=/usr/lib/x86_64-linux-gnu --disable-x86asm --enable-gpl --enable-version3 --enable-sdl2 --enable-fontconfig --enable-gnutls --enable-iconv --enable-libass --enable-libdav1d --enable-libbluray --enable-libfreetype --enable-libmp3lame --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopenjpeg --enable-libopus --enable-libshine --enable-libsnappy --enable-libsoxr --enable-libtheora --enable-libtwolame --enable-libvpx --enable-libwavpack --enable-libwebp --enable-libx264 --enable-libx265 --enable-libxml2 --enable-libzimg --enable-lzma --enable-zlib --enable-gmp --enable-libvidstab --enable-libvorbis --enable-libvo-amrwbenc --enable-libmysofa --enable-libspeex --enable-libxvid --enable-libaom --enable-libmfx --enable-ffnvcodec --enable-cuvid --enable-nvenc --enable-nvdec --enable-libopenmpt



