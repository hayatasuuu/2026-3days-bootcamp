# Playground Series S6E3 - Customer Churn Prediction

[Kaggle Playground Series S6E3](https://www.kaggle.com/competitions/playground-series-s6e3/overview) のコンペに取り組むリポジトリです。

## コンペ概要

- **タスク**: 顧客が解約するかどうかを予測する二値分類
- **評価指標**: AUC
- **目的変数**: Churn

## ディレクトリ構成

```
.
├── notebooks/                  # 実験ノートブック
│   ├── baseline-20260320.ipynb # ベースライン（tenure, MonthlyCharges の2特徴量）
│   └── exp01-label-encoding.ipynb # カテゴリ特徴量の追加（PaymentMethod, Contract）
├── data/                       # コンペデータ（.gitignore対象）
├── pyproject.toml
└── uv.lock
```

## セットアップ

```bash
uv sync
```

## 実験ログ

| 実験 | 内容 | 特徴量数 |
|------|------|----------|
| baseline | 数値カラムのみ（tenure, MonthlyCharges） | 2 |
| exp01 | + PaymentMethod, Contract（LabelEncoding） | 4 |
