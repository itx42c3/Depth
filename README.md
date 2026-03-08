# Depth

軽量・高速なWindows向けブラウザです。

## ダウンロード

[Releases](../../releases) から最新の `Depth.zip` をダウンロードしてください。

## 実行方法

1. `Depth.zip` を解凍
2. `Depth.exe` を実行

インストール不要です。デスクトップへの自動追加機能は無いため、手動での操作をお願い致します。解凍したフォルダの`Depth.exe`を指定して下さい。

## 動作環境

- Windows 10 (1809以降) / Windows 11 (64bit)

## 機能

- 複数タブ（追加・削除・切り替え）
- OS標準タイトルバー + 独自タブバー・ナビゲーションバー
- キーボードショートカット
- JavaScriptダイアログのネイティブUI統合
- プッシュ通知の許可/拒否（セッション内ドメイン記憶）
- リンクをDepth内の新しいタブで開く
- 右クリックメニューの「新しいウィンドウで開く」→「新しいタブで開く」
- ズーム操作
- ページ内検索
- カスタムスタートページ（[start-depth.netlify.app](https://start-depth.netlify.app/ )）

## ショートカット

| 操作 | ショートカット |
|---|---|
| 新しいタブ | Ctrl+T |
| タブを閉じる | Ctrl+W |
| 閉じたタブを再開 | Ctrl+Shift+T |
| 次のタブ | Ctrl+Tab |
| 前のタブ | Ctrl+Shift+Tab |
| タブ番号指定 | Ctrl+1〜9 |
| アドレスバー | Ctrl+L / F6 |
| 戻る | Alt+← |
| 進む | Alt+→ |
| 更新 | F5 / Ctrl+R |
| 新しいウィンドウ | Ctrl+N |
| ページ内検索 | Ctrl+F |
| ズームイン | Ctrl++ |
| ズームアウト | Ctrl+- |
| ズームリセット | Ctrl+0 |
| 開発者ツール | F12 |

## 技術スタック

- C# 12 / .NET 10
- WPF
- Microsoft WebView2 (Evergreen)
- LiteDB

## ライセンス

MIT
