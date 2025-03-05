# 100try47_agir_app1

## 概要
このプロジェクトは農地面積算出アプリケーションです。GISを活用して農地の面積を計算し、作業計画を管理することができます。

## 機能
- 地図上で農地の面積を計算
- 作業スケジュールの管理
- カレンダーによる視覚的な作業計画

## 技術スタック
- Flask
- SQLAlchemy
- Google Maps API
- JavaScript

## インストール方法
```bash
# 仮想環境の作成
python -m venv venv

# 仮想環境の有効化
source venv/bin/activate  # Linuxの場合
venv\Scripts\activate     # Windowsの場合

# 依存パッケージのインストール
pip install -r requirements.txt
```

## 使用方法
```bash
# アプリケーションの起動
python run.py
```

ブラウザで http://localhost:5000 にアクセスしてください。
