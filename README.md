# vscode-latex-template
`Visual Studio Code` で執筆する `latex` 環境のテンプレート

## 動作確認環境
- `Windows 7` + `Windows Subsystem for Linux 2 (Ubuntu 18.04)` + `TexLive 2019`
- `Windows 10` + `Windows Subsystem for Linux 2 (Ubuntu 18.04)` + `TexLive 2019`

## 必要なもの
- `TexLive` (`Tex` 処理系)
- `Visual Studio Code`
  - `LaTeX Workshop` (拡張機能)

### TexLive
下記 URL にて 該当 OS の最新版をダウンロード
- [Installing TeX Live over the Internet](https://www.tug.org/texlive/acquire-netinstall.html)

※ `Windows` 用とそれ以外の `OS (Mac, Linux)` 用が用意されている

※ 途中で `TexWorks` のインストールのチェックを外す (`Visual Studio Code` を使うため，不要)

### Visual Studio Code
下記 URL からインストール

- [Visual Studio Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
- 拡張機能の [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)を追加

## コンパイル方法
- 拡張機能の `Latex Workshop` より，`platex`, `uplatex`, `pdflatex` のいずれかを選択してコンパイルが可能
- `.tex` ファイルの保存時，デフォルトでは `pdflatex` でコンパイルされる
