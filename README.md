# DIY SFC CARTRIDGE
## 概要
スーファミ用のフラッシュROMカートリッジ基板の自作。
<img width="954" height="409" alt="Image" src="https://github.com/user-attachments/assets/cedea6fb-3dfc-4956-9566-e98fc81921a8" />

・フラッシュメモリを2つ載せると8Mbitになります。1つだけ載せると4Mbitです。この場合はROM信号をCHIP0に直結しますので、74HC139が不要です。

・PICマイコンには「SuperCIC」を書き込んでCICとして機能させます。

## ファイル説明
・SFC_FLASH.COMP : カートリッジ基板のプリント基板データ。CADLUS X用。

・SFC_WR.COMP : フラッシュROMライターのプリント基板データ。CADLUS X用。

・wr_sfc.py : フラッシュROM書き込みプログラム。Raspberry Pi+Python用。

・sfc.prg : フラッシュROM書き込みプログラム。Raspberry Pi+Pi STARTER用。

## 部品リスト
### カートリッジ基板
・4Mbit フラッシュメモリ SST39SF040-70-4C-PHE

・PICマイコン PIC12F629-I/P

・74HC139/74LS139

・リセッタブルヒューズ

・積層セラミックコンデンサもしくは電解コンデンサ

### フラッシュROMライター
・16bit I/Oエキスパンダ MCP23S17

・カードエッジコネクタ

・抵抗

・LED

・リセッタブルヒューズ

・積層セラミックコンデンサもしくは電解コンデンサ
