# PC-9821Tips
PC-9821のTIPS集

#### PC-9821 ドライバ アップデート リンク
https://download-drv.com/driver/nec/html/PC-982.htm

#### HSB.EXEのPentium対応方法
HSB for PC-9801  
https://www.vector.co.jp/soft/dos/util/se002233.html
```
D5,08,81,E1,D5,08,3B,C1と並んでいる直後の74,xxを90,90に変更
```

#### UIDE-98M環境での3.5MO フォーマット
I/O DATAのMOUTL.EXEを使う  
https://www.iodata.jp/lib/software/m/355.htm#MS-DOS
```
MOUTL ASPI
```
