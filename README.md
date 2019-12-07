# programmable_controler

熱電対の出力電圧の測定結果をcsvファイルに保存するプログラム

# 使い方

* 実行環境のテスト

 [Raspberry Pi High-Precision AD/DA Expansion Boardのwiki](https://www.waveshare.com/wiki/High-Precision_AD/DA_Board)を参考にして、サンプルプログラムの"ads1256_test.c"が実行可能か確認してください。

* 本プログラムの配置

"ads1256_test.c"と同じフォルダに"ads_yogo.c"とdataフォルダを配置し，サンプルと同様に実行してください。

# プログラムの内容

"ads_yogo.c"ではラズパイAD/DA BoardのAD inputの7番ピンの出力電圧を記録します。

出力電圧の測定結果がdataフォルダ内にCSVファイルで保存されます。

# オプション

ソースコード"ads_yogo.c"の<u>843行目のsetTimeを変更</u>することで、**測定時間を変更**できます。

[ads_yogo.c:843]
```C
double total =0.0, setTime=180.0; // 測定時間
```