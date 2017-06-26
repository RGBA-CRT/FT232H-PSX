# FT232H-PSX
- FT232Hを使ってPS1のコントローラとメモカを読み書きするテストプログラム  
  PSX memcard reader/writer with FT232H  
- 実験プログラムなのでだいぶ雑なコードになってます。
- メモカのフォーマットはmcr(ヘッダなし生データ)と同一です。
- ビルドには[こちらの[AB-FT232HLib]](https://github.com/RGBA-CRT/AB-FT232HLib)ライブラリを1階層上に配置する必要があります。

# 接続
 * FT232H SPI <===> PSX PAD PORT SPI  
適度にプルアップとかしてください

# 機能
 * READ PAD STATUS(digital/analog)
 * DUMP MEMCARD(128KB)
 * WRITE MEMCARD(128KB)
 
# SS
![PAD](https://raw.githubusercontent.com/RGBA-CRT/FT232H-PSX/master/SS/pad.png "PAD")  
![read](https://raw.githubusercontent.com/RGBA-CRT/FT232H-PSX/master/SS/read.png "read")  
![write](https://raw.githubusercontent.com/RGBA-CRT/FT232H-PSX/master/SS/write.png "write")  
