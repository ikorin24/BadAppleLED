# Bad Apple LED

2017年の大阪大学の学園祭で展示していた作品です。

32x32の電光掲示板で [Bad Apple](https://www.youtube.com/watch?v=FtutLA63Cp8) の動画を表示します。

![summary image](https://github.com/ikorin24/BadAppleLED/blob/master/img/summary.gif)

## 構成と回路図

マイコンは ATmega328P (Arduino) 16MHz。

[ffmpeg](https://ffmpeg.org/) で事前に動画を二値化無圧縮の独自フォーマットのデータに変換し、SD カードから読みだして再生しています。

ソースコードは現存していません。
