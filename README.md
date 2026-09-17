# Sankenronshu54d reproduction files

兵庫CLIの景気予測力 ―リアルタイム・ヴィンテージによる検証― の図表再現用ファイルです。

## Structure

- `scripts/hyogo_cli_repro.Rmd` : 本文図表（図1～図5、表1～表5）と第3章電子補足図（S1～S7）の再生成
- `data/兵庫cliデータ.xlsx` : 分析データ
- `figures/` : 必要に応じて出力図を保存するためのフォルダ

## Run

RStudioでリポジトリのルートをworking directoryとして開き、`scripts/hyogo_cli_repro.Rmd` を実行してください。
スクリプト中のデータ参照は `data/兵庫cliデータ.xlsx` です。

Required packages: `openxlsx`, `knitr`.
