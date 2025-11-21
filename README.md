# Garmin Striker4 照射範囲計算機

Garmin Striker4魚群探知機のエコー照射範囲を計算するWebアプリケーション。湖面に浮かべた魚群探知機から湖底への照射範囲を可視化します。

## 公開URL

https://sanukaku.github.io/striker4-calculator/

スマートフォンでアクセスして使用できます。

## 機能

- **水深選択**: 2m～50mの範囲で水深を選択
  - 数字ボタングリッド（5列レイアウト）
  - +/-ステッパーで隣接する値に移動
  - デフォルト値: 5m

- **同時計算表示**:
  - 77Hz（45度）広角照射
  - 200Hz（15度）狭角照射

- **スマホファースト設計**:
  - タッチ操作に最適化
  - 1画面に収まるコンパクトレイアウト
  - スクロール不要

## 技術仕様

- 単一HTMLファイル構成（index.html）
- 外部CDN・ライブラリ不使用
- 完全オフライン動作
- 外部サーバーとの通信なし

詳細な仕様は [SPECIFICATION.md](SPECIFICATION.md) を参照してください。

## 更新方法

ローカルでindex.htmlを編集後、以下のコマンドで更新：

```bash
cd /c/work/gyotan
git add index.html
git commit -m "更新内容の説明"
git push
```

数分後にGitHub Pagesに自動反映されます。

## リポジトリ情報

- **GitHubリポジトリ**: https://github.com/sanukaku/striker4-calculator
- **公開URL**: https://sanukaku.github.io/striker4-calculator/

## ライセンス

このプロジェクトは個人使用を目的としています。
