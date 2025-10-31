※README は、AIに書いてもらいました。
# 🍄 Mario Game

HTMLとJavaScriptで実装されたクラシックマリオゲームです。ブラウザで動作し、モダンなWeb技術を使用したプラットフォーマーゲームです。

## 📋 概要

このプロジェクトは、スーパーマリオブラザーズのWeb版実装です。プレイヤーはマリオを操作して、敵を避け、ステージを進めクリアを目指します。

**🎮 ライブデモ**: https://moshimur.github.io/mario-game/

## ✨ 機能

- **マリオキャラクターの操作**: 矢印キー（← →）またはADキーで移動、スペースキーでジャンプ
- **敵システム**: 倒すべき敵キャラクターが登場し、敵の数がリアルタイム表示
- **スコアシステム**: ゲーム進行に応じてスコアが加算
- **ゲームオーバー画面**: ゲーム終了時に敵の数とスコアを表示
- **ブラウザベース**: 追加インストール不要ですぐにプレイ可能
- **Git Pages対応**: GitHub Pagesで自動ホスティング

## 🚀 はじめに

### 必要な環境

- モダンなWebブラウザ（Chrome、Firefox、Safari、Edgeなど）

### クイックスタート

**オンラインでプレイ**:

ブラウザで以下のURLにアクセス：
```
https://moshimur.github.io/mario-game/
```

**ローカルで実行**:

```bash
# リポジトリをクローン
git clone https://github.com/moshimur/mario-game.git
cd mario-game

# ローカルサーバーで実行（Python 3の場合）
python -m http.server 8000

# ブラウザでアクセス
# http://localhost:8000
```

## 🎮 ゲーム操作

| キー | アクション |
|------|-----------|
| ← → / A D | 左右移動 |
| Space | ジャンプ |

## 📁 プロジェクト構成

```
mario-game/
├── index.html            # メインHTMLファイル
├── style.css             # スタイルシート
├── script.js             # ゲームロジック
└── README.md             # このファイル
```

## 🎯 ゲームプレイ

1. ゲーム開始時にマリオが画面に表示されます
2. キーボード操作でマリオを左右に移動
3. スペースキーでジャンプして敵や障害物を避ける
4. 敵を倒しながらステージを進める
5. ゲームオーバーになるとスコアと敵の数が表示されます

### ゲーム画面表示

- **敵: N**: 現在のゲーム内に存在する敵の数
- **スコア: N**: 現在のゲームスコア
- **GAME OVER**: ゲーム終了時に表示

## 💻 技術スタック

- **HTML5**: ゲーム構造とセマンティクス
- **CSS3**: スタイリングとアニメーション
- **JavaScript (ES6)**: ゲームロジック・物理演算・アニメーション
- **Canvas API** または **DOM**: グラフィックス描画
- **GitHub Pages**: ホスティングプラットフォーム

## 🛠️ 開発

### ローカル開発環境

```bash
# リポジトリをクローン
git clone https://github.com/moshimur/mario-game.git
cd mario-game

# ローカルサーバーを起動
# Python 3
python -m http.server 8000

# または Node.js
npx http-server

# または Python 2
python -m SimpleHTTPServer 8000
```

### コード編集

主要なファイル：
- `index.html` - ゲームのHTML構造
- `style.css` - ゲームのスタイルとアニメーション
- `script.js` - ゲームロジック、キャラクター制御、敵AI、衝突判定

### 開発のヒント

1. **ゲームスピードの調整**: `script.js` で物理エンジンのパラメータを調整
2. **敵の難易度**: 敵の速度や数を `script.js` で変更
3. **ステージの編集**: レベルレイアウトをHTMLまたはJavaScriptで調整

## 🤝 貢献

このプロジェクトへの貢献を歓迎します。以下の手順に従ってください：

1. リポジトリをフォークしてください
2. フィーチャーブランチを作成します (`git checkout -b feature/AmazingFeature`)
3. 変更をコミットします (`git commit -m 'Add some AmazingFeature'`)
4. ブランチをプッシュします (`git push origin feature/AmazingFeature`)
5. プルリクエストを作成します

### 改善提案

- 新しい敵キャラクターの追加
- パワーアップアイテムの実装
- サウンドエフェクトとBGMの追加
- レベルの増加
- モバイル操作対応の強化
- ゲームバランスの調整
- パフォーマンス最適化

## 📝 ライセンス

このプロジェクトはMITライセンスの下で公開されています。詳細は[LICENSE](LICENSE)ファイルを参照してください。

## 👨‍💻 作成者

- **moshimur** - [GitHub Profile](https://github.com/moshimur)

## 🙏 謝辞

- Original Super Mario Bros. by Nintendo
- Webゲーム開発コミュニティ
- 全ての貢献者

## ❓ FAQ

**Q: ゲームが起動しません**

A: 以下を確認してください：
- ブラウザのコンソールを確認（F12キーで開発者ツールを開く）
- JavaScriptエラーが表示されている場合は、リポジトリのIssueで報告
- キャッシュをクリアしてページをリロード（Ctrl+Shift+Delete）

**Q: モバイルで遊べますか？**

A: はい。タッチ対応は予定中です。現在のバージョンではデスクトップキーボードでの操作が推奨されています。

**Q: レベルをカスタマイズできますか？**

A: はい。`script.js` でレベルデータを編集することでカスタマイズ可能です。

**Q: ハイスコアは保存されますか？**

A: 現在のバージョンでは、ブラウザを閉じるとスコアはリセットされます。LocalStorageでの保存機能は今後実装予定です。

## 📞 サポート

問題が発生した場合や改善提案がある場合は、以下の方法でお知らせください：

- [GitHub Issues](https://github.com/moshimur/mario-game/issues)
- [GitHub Discussions](https://github.com/moshimur/mario-game/discussions)

---

**楽しいマリオゲーム体験をお楽しみください! 🎮**
