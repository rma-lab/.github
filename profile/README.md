# rma-lab

研究支援（RMA: Research Management and Administration）のツールを作って公開しています。
URA・研究推進担当者・研究者向けです。AIを活用した研究支援の取り組み **AI4RA** の一環として開発しています。

## ツール

- **[kaken-atlas](https://github.com/rma-lab/kaken-atlas)** — 科研費の採択課題 約20.6万件（2019–2025年度開始）を言語モデルの埋め込みで意味空間に配置した「科研費 学術地図」。検索・種目フィルタ・なげなわ選択による集計ができ、点をクリックするとKAKENの課題ページに飛べます。科研費 基盤研究(C) 26K15524 の研究プロジェクトです。→ **[ブラウザでそのまま使えます](https://rma-lab.github.io/kaken-atlas/)**
- **[kaken-history](https://github.com/rma-lab/kaken-history)** — 科研費データベース（KAKEN）のデータから「最初の科研費 → 大型科研費までの道のり」を集計し、レポート・ヒストグラム・ガントチャートのPDFを生成します。→ **[ブラウザでそのまま使えます](https://rma-lab.github.io/kaken-history/)**
- **[SPReAD-checker](https://takayuki1997.github.io/SPReAD-checker/)** — SPReAD公募の申請書類（Excel・PDF）の形式チェックを、文科省配布の公式チェックプログラムを使ってブラウザ上で実行します。

## 方針

- 研究支援の実務で使えるものを目指していますが、"lab" の名のとおり試験運用段階のツールも含まれます。フィードバックを歓迎します
- 氏名や申請書類など取り扱いに注意が必要なデータは、情報管理に配慮して設計しています（ブラウザ内で処理し、外部に送信しない等）
- コードはオープンソース（MIT License）で公開しています

個人による取り組みであり、特定の機関の公式プロジェクトではありません。不具合・要望は各リポジトリの Issues へお寄せください。
