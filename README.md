[normal ver. site](https://zenn24ct.github.io/task-management/normal)

[cla ver. site](https://zenn24ct.github.io/task-management/cla)

[simple ver. site](https://zenn24ct.github.io/task-management/simple)
# ToDoリスト

シンプルで使いやすいタスク管理アプリ

## 特徴

- ブラウザで動作する単一HTMLファイル
- データは自動的にローカルストレージに保存
- インストール不要、オフラインで使用可能
- レスポンシブデザイン対応

## 主な機能

### タスク管理
- タスクの追加・削除
- 完了/未完了の切り替え
- 優先度設定（高・中・低）
- 作成時刻の記録

### フィルター機能
- すべて表示
- 未完了のみ
- 完了済みのみ
- 高優先度のみ

### 統計表示
- 全タスク数
- 未完了タスク数
- 完了済みタスク数

### その他
- 完了済みタスクの一括削除
- リアルタイム保存
- 通知表示

## 使い方

1. HTMLファイルをブラウザで開く
2. テキスト入力欄にタスクを入力
3. 優先度を選択（デフォルト: 中）
4. 「タスクを追加」ボタンをクリックまたはEnterキー
5. チェックマークをクリックで完了/未完了を切り替え
6. 削除ボタンでタスクを削除

## ショートカット

- `Enter` - タスクを追加

## 技術仕様

- 純粋なHTML/CSS/JavaScript
- 外部ライブラリ不要
- LocalStorage使用
- モダンブラウザ対応

## ブラウザ対応

- Chrome
- Firefox
- Safari
- Edge

## ファイル構成

- 単一HTMLファイル
- すべてのCSS/JavaScriptを含む
- 外部依存なし

## データ保存

- ブラウザのLocalStorageに自動保存
- ブラウザを閉じてもデータは保持
- ブラウザのキャッシュをクリアするとデータは削除される

## カスタマイズ

### 色の変更
CSSの`body`セクションの`background`プロパティを編集

### 優先度の追加
1. `PRIORITY`定数に新しい優先度を追加
2. HTMLの`select`オプションに追加
3. CSSでスタイルを定義

### フィルターの追加
1. HTMLにフィルターボタンを追加
2. `TaskManager.getFilteredTasks()`に条件を追加

## ライセンス

フリーソフトウェア - 自由に使用・改変可能
