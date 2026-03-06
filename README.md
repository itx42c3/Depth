# Depth

軽量・高速なWindows向けブラウザです。

## ダウンロード

[Releases](../../releases) から最新の `Depth.zip` をダウンロードしてください。

## インストール

1. `Depth.zip` を解凍
2. `Depth.exe` を実行

ブラウザ本体はインストール不要です。WebView2ランタイムが未インストールの場合のみ事前にインストールしておいてください。基本、Windows10 / 11環境であれば導入済みです。

## 動作環境

- Windows 10 / 11 (64bit)

## 機能

- 複数タブ（追加・削除・切り替え）
- キーボードショートカット
- JavaScriptダイアログのネイティブUI統合
- プッシュ通知の許可/拒否
- ズーム操作
- ページ内検索
- カスタムスタートページ（[start-depth.netlify.app](https://start-depth.netlify.app/ )）

## ショートカット

| 操作 | ショートカット |
|---|---|
| 新しいタブ | Ctrl+T |
| タブを閉じる | Ctrl+W |
| 閉じたタブを再開 | Ctrl+Shift+T |
| 次/前のタブ | Ctrl+Tab / Ctrl+Shift+Tab |
| タブ番号指定 | Ctrl+1〜9 |
| アドレスバー | Ctrl+L / F6 |
| 戻る / 進む | Alt+← / Alt+→ |
| 更新 | F5 / Ctrl+R |
| 新しいウィンドウ | Ctrl+N |
| ページ内検索 | Ctrl+F |
| ズーム | Ctrl++ / Ctrl+- / Ctrl+0 |
| 開発者ツール | F12 |

## 技術スタック

- C# 12 / .NET 10
- WPF
- Microsoft WebView2 (Evergreen)
- LiteDB

## ライセンス

MIT
