
# 飯塚研で使ったファイルのまとめ

## 🌟 概要
飯塚研究室で使ったファイルをここに置いています。

## 📁 ディレクトリ構成
- `AnalogTraining/` `DigitalTraining`：トレーニング用ファイル
- `FPGA/`：デジタルトレーニングで書いたFPGA用コード
- `PLL論文/`：卒論の前段階として読んだPLLの博士論文関連

## 🛠 使用ツール
- シミュレータ：Icarus Verilog / ModelSim
- 波形ビューア：GTKWave
- エディタ：VSCode + 拡張機能

## 💡 メモ・備忘録
- ビルド手順：
  ```bash
  iverilog -o build/top.out src/top.v
  vvp build/top.out
  ```

- 波形ファイル（`.vcd`）をGTKWaveで開くとき：

  ```bash
  gtkwave dump.vcd
  ```

- .mdをPDFで保存するとき

  1. 対象の.mdファイルを開き、右上のプレビューマークをクリック
  2. 右側に表示されたプレビュー内で右クリック
  3. Export/Chrome (Puppeteer)/PDFをクリックで保存完了

## 📌 TODO

* [ ] モジュールの階層化
* [ ] テストベンチの整理
* [ ]

## 💬 備考

このリポジトリは個人学習用です。外部提供や公開の予定はありません。

---