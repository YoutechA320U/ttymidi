# ttymidi
オリジナルの[ttymidi](https://github.com/moddevices/mod-ttymidi)にPitchBendとSysExのサポートを追加した https://github.com/sixeight7/ttymidi のPitchBendの値が正常に受信できないバグを修正したものです。

以下のコマンドでコンパイルできます。Raspbian Stretchで動作確認済みです。

gcc ttymidi.c -o ttymidi -lasound -pthread

使い方はオリジナルのttymidiと同じです。