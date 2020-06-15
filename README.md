# ffmpeg_20.04-1_amd64.deb_ubuntu-20.04
ffmpeg , ubuntu 20.04 , библиотеки относимые к гую , возможно ускоряют запуск некоторых программ типа obs-studio и других которым как и видео в браузере нужна отрисовка чем быстрее тем лучше и быстрее будет происходить запуск obs и подобных. Возможно ещё может отвечать за контраст видео картинки подаваемых с таких серверов как ютуб , твитч и подобные видео хостинги так что если картинка изменилась и стала более качественной то можно не удивляться так как кодек полученный на хорошо настроенной системе будет очень качественным , а в частности это мною собранный графический стек который я ранее сделал для версии убунту 20.04.

sudo apt purge libavcodec-dev libavutil-dev -y && sudo apt purge ffmpeg -y 

install deb package ffmpeg: https://yadi.sk/d/zP0XOL8iRJ77nw

help command

ffplay -h

ffmpeg -h

ffprobe -h

------------------------------------------------------------------------------------------------------------------------

My build flags / флаги которые удалось поставить

./configure --prefix=/usr --libdir=/usr/lib/x86_64-linux-gnu --disable-x86asm --enable-gpl --enable-version3 --enable-sdl2 --enable-fontconfig --enable-gnutls --enable-iconv --enable-libass --enable-libdav1d --enable-libbluray --enable-libfreetype --enable-libmp3lame --enable-libopencore-amrnb --enable-libopencore-amrwb --enable-libopenjpeg --enable-libopus --enable-libshine --enable-libsnappy --enable-libsoxr --enable-libtheora --enable-libtwolame --enable-libvpx --enable-libwavpack --enable-libwebp --enable-libx264 --enable-libx265 --enable-libxml2 --enable-libzimg --enable-lzma --enable-zlib --enable-gmp --enable-libvidstab --enable-libvorbis --enable-libvo-amrwbenc --enable-libmysofa --enable-libspeex --enable-libxvid --enable-libaom --enable-libmfx --enable-ffnvcodec --enable-cuvid --enable-nvenc --enable-nvdec --enable-libopenmpt



