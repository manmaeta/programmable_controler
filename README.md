# programmable_controler
## Raspberry Pi  High-Precision AD/DA Expansion Boardのwikiを参考にして、サンプルプログラムの"ads1256_test.c"が実行可能か確認してください。
## wikiのURL：https://www.waveshare.com/wiki/High-Precision_AD/DA_Board
## "ads1256_test.c"と同じフォルダに"ads_yogo.c"とdataフォルダを配置してください。


## "ads_yogo.c"ではラズパイAD/DA BoardのAD inputの7番ピンの出力電圧を記録します。
## 出力電圧の測定結果がdataフォルダ内にCSVファイルで保存されます。
## ソースコード"ads_yogo.c"の843行目のsetTimeを変更することで、測定時間を変更できます。
