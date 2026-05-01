# Simple Alarm ⏰

ブラウザで動くシンプルなアラームアプリです。インストール不要、`index.html` を開くだけで使えます。

## 機能

- 時刻を指定してアラームを追加
- アラームのON/OFFトグル
- アラーム削除
- 時刻になったらビープ音 + ブラウザ通知
- ダークモード対応
- LocalStorage でアラームを保存（ページを閉じても保持）

## 使い方

1. `index.html` をブラウザで開く
2. 時刻ピッカーでアラーム時刻を入力し「追加」をクリック（またはEnterキー）
3. アラームが鳴ったら Space または Enter キーで停止

> **Note:** ブラウザ通知を許可すると、タブがバックグラウンドでもアラームを通知します。

## 技術

- 純粋な HTML / CSS / JavaScript（依存なし）
- Web Audio API でビープ音を生成
- Notifications API でブラウザ通知
- `localStorage` でデータを永続化

---

A simple alarm clock that runs in the browser. No installation needed — just open `index.html`.

**Features:** add alarms by time, toggle on/off, delete, beep sound + browser notification, dark mode, persistent storage.
