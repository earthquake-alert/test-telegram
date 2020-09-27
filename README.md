# Test Telegram

テスト用

## Use test

- 32-35_01
- 32-35_04
- 32-35_06
- 32-39_05
  - `https://earthquake-alert.github.io/test-telegram/telegram/32-39_05/index.xml`
- 32-39_11
  - `https://earthquake-alert.github.io/test-telegram/telegram/32-39_11/index.xml`

## Tree

- telegram
  - 32-35_01
    - `32-35_01_01_100806_VXSE51`: #1①震度速報：地震発生後90秒から5分程度
    - `32-35_01_02_100514_VXSE52`: #1②震源に関する情報：地震発生後3分程度で津波警報等を発表しない場合
    - `32-35_01_03_100514_VXSE53`: #1③’震源・震度に関する情報：(海外)
    - `32-35_01_03_100806_VXSE53`: #1③震源・震度に関する情報：地震発生後3分程度から数十分程度(便宜上震度3以上のみを表示)
  - 32-35_04
    - `32-35_04_01_100831_VXSE51`: #4①小さい地震Aでも地震Bの影響を受け発表基準に達したため震度速報を発表
    - `32-35_04_02_100831_VXSE51`: #4②地震Bに対する震度速報
    - `32-35_04_03_100831_VXSE52`: #4③地震Bの震源確定し地震情報(震源に関する情報)を発表
    - `32-35_04_04_100831_VXSE53`: #4④地震Bの地震情報(震源・震度に関する情報)発表
    - `32-35_04_05_100831_VXSE51`: #4⑤地震Bの追加入電により震度4地域が増えた
    - `32-35_04_06_100831_VXSE53`: #4⑥地震Bの追加入電により震度4地域が増えた
  - 32-35_06
    - `32-35_06_01_100915_VXSE52`: #6①地震情報(震源に関する情報)
    - `32-35_06_02_100915_VXSE52`: #6②地震情報(震源に関する情報)（取り消した場合の例）
    - `32-35_06_03_100915_VXSE53`: #6③地震情報(震源・震度に関する情報)
    - `32-35_06_04_100915_VXSE53`: #6④追加入電に伴う地震情報(震源・震度に関する情報)
    - `32-35_06_05_100915_VXSE53`: #6⑤追加入電に伴う地震情報(震源・震度に関する情報)
    - `32-35_06_06_100915_VXSE53`: #6⑥地震情報(震源・震度に関する情報)（取り消した場合の例）
  - 32-39_05
    - `32-39_05_01_100831_VXSE53`: #5地震情報(震源・震度に関する情報)（外国、調査中）
    - `32-39_05_02_100831_VXSE53`: #5地震情報(震源・震度に関する情報)（外国、外国津波観測、調査中）
    - `32-39_05_04_100831_VXSE53`: #5地震情報(震源・震度に関する情報)（外国、外国津波観測、調査中）
    - `32-39_05_05_100831_VXSE53`: #5地震情報(震源・震度に関する情報)（外国、外国津波観測、調査中）
    - `32-39_05_06_100831_VXSE53`: #5地震情報(震源・震度に関する情報)（外国、外国津波観測、調査中）
    - `32-39_05_07_100831_VXSE53`: #5地震情報(震源・震度に関する情報)（外国、外国津波観測、調査中）
    - `32-39_05_08_100831_VXSE53`: #5地震情報(震源・震度に関する情報)（外国、外国津波観測、調査中）
    - `32-39_05_12_100831_VXSE53`: #5地震情報(震源・震度に関する情報)（外国、外国津波観測、警報発表）
    - `32-39_05_12_100915_VXSE53`: #5地震情報(震源・震度に関する情報)（取り消した場合の例）
  - 32-39_11
    - `32-39_11_01_120615_VXSE51`: #11①震度速報
    - `32-39_11_05_120615_VXSE53`: #11⑤震源・震度に関する情報（巨大地震）

## Licence

- サンプルデータ
  - 気象庁（http://xml.kishou.go.jp/jmaxml_20200826_Samples.zip）
- それ以外
  - MIT
