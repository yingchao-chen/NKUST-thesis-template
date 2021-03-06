## NKUST Thesis LaTeX

![](https://www.nkust.edu.tw/var/file/0/1000/img/513/182513897.png)

### 前言

此模板修改自國立高雄科技大學建工校區電子工程系網路計算實驗室歷屆學長留下之板型進行修改優化。如果您發現這個板型有問題，請向我們提交 Issus，也非常歡迎您提交 PR 協助修正問題。

### 說明

依照[國立高雄科技大學學位論文格式規範](https://ceed.nkust.edu.tw/app/index.php?Action=downloadfile&file=WVhSMFlXTm9MekV3TDNCMFlWOHhPRFEzWHpJMk5qRXhNakJmTVRZMk9EVXVjR1Jt&fname=WSGGTSB00010A1KK50LKRKHGSTTW25B1RKFG40NPQPRLFG40ROFCLL54WWOODGOK44CCIH15A404GDJGVWPKTS14B0MOGCHCCC35DCTSZWB030FC145424DCGCLK0115JCLKSXHGTWFGSWHCUS30A110)之內容，排列順序依序為：

1. 封面
2. 書名頁
3. 碩博士論文授權書
4. 論文指導教授推薦書
5. 論文口試委員會審訂書
6. 中文摘要
7. 英文摘要
8. 誌謝或序言
9. 目錄
10. 表目錄
11. 圖目錄
12. 論文本文
13. 參考文獻
14. 附錄
15. 自傳或簡歷 (未提供)
16. 書背

### 使用

使用前請先確認您已經安裝下列套件，如果缺少這些套件可能導致編譯失敗

* `make`
* `texlive`


> 註： 板型目前仍再修改警告，未來可能會從 `pdflatex` 這個編譯器轉換到 `xelatex`。

您可以直接下載[穩定版本](https://github.com/yuhao-kuo/NKUST-thesis-template/releases)/[開發版本](https://github.com/yuhao-kuo/NKUST-thesis-template/archive/master.zip)，或是使用 git 獲取專案。

編譯採用 `make` 當作工具，編譯參數如下表。

| 命令 | 功能描述 |
|---|---|
| `make all` | 編譯 $LaTeX$ 專案 |
| `make clean` | 清除所有暫存檔 |
| `make distclean` | 清除所有編譯產生的檔案(包含PDF檔案) |

### 架構說明

* ***Chapters*** : 主文
* ***Configurations*** : 設定檔案
* ***Exteranls*** : 外部匯入的PDF檔案
* ***Figures*** : 文中的所有圖片
* ***Instance*** : 封面/書名頁/封面/摘要/誌謝
* ***Packages*** : 套件
* ***References*** : 參考文獻 bib 檔案
* ***Scripts*** : Makefile 腳本
* ***Templates*** : 非本文文件版型
* ***build*** : 編譯結果


### 鳴謝

感謝參與這個專案的[貢獻者](https://github.com/yuhao-kuo/NKUST-thesis-template/graphs/contributors)以及前輩們！


