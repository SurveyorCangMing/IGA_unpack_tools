# IGA_unpack_tools
Some useful tools to unpack game file of Innocent Grey or Noesis.(`.iga`, `.s`, `.dat`)\
( not for isogeometric analysis )
## igtool
extract and create the `*.dat` files used by Innocent Grey and Noesis
### Useage
Unpack: `igtool -x scripts.dat`\
Pack: `igtool -c scripts~ scripts.dat`
### Known to work with
* Innocent Grey\
  Caucasus: Nanatsuki no Nie (クロウカシス - 七憑キノ贄)\
  PP pianissimo (ＰＰ-ピアニッシモ- 操リ人形ノ輪舞)\
  Cartagra \~Tsuki kurui no Yamai\~ (カルタグラ～ツキ狂イノ病～)\
  Kara no Shoujo (殻ノ少女)\
  Nagomibako Innocent Grey Fandisc (和み匣 Innocent Greyファンディスク)
* Noesis\
  Furifure (フリフレ)\
  Houkago no Senpai(放課後の先パイ )\
  Marble Bloomers(マーブル★ブルマ)
## exiga
This tool extracts IGA0 (`*.iga`) archives.
### Useage
Just drag your `.iga` file on to the `exiga.exe`\
or `exiga scripts.iga` in cmd.
## igscrpit
This tool can unpack and pack `.s` file.
### Useage
Unpack: `igscript -p 00_0000.s 00_0000.txt`\
Pack: `igscript -c 00_0000.s 00_0000.txt new\00_0000.s`
**If the extracted txt file size is 0KB:**
Use these following command:\
Unpack: `igscript -x -p 00_0000.s 00_0000.txt`\
Pack: `igscript -x -c 00_0000.s 00_0000.txt new\00_0000.s`
### Known to work with
* Innocent Grey
  Caucasus: Nanatsuki no Nie(クロウカシス - 七憑キノ贄)\
  PP pianissimo(ＰＰ-ピアニッシモ- 操リ人形ノ輪舞)\
  Cartagra \~Tsuki kurui no Yamai\~(カルタグラ～ツキ狂イノ病～)\
  Kara no Shoujo(殻ノ少女)\
  Nagomibako Innocent Grey Fandisc(和み匣 Innocent Greyファンディスク)\
  Eisai Kyouiku(英才狂育)\
  FLOWERS(The whole series)
* Noesis
  Cure Girl\
  Furifure(フリフレ)\
  Furifure 2(フリフレ2)\
  Houkago no Senpai(放課後の先パイ )\
  Marble Bloomers(マーブル★ブルマ)
