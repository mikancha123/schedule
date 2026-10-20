Komorebi を iPhone のホーム画面で使う

このフォルダー内のファイルを、HTTPS に対応した静的サイトへまとめて公開します。
簡単な方法は GitHub Pages です。

1. GitHub で新しいリポジトリを作成します。
2. index.html、campus-planner.html、campus-planner.webmanifest、campus-planner-sw.js、campus-planner-icon.svg をリポジトリの最上位にアップロードします。
3. リポジトリの Settings > Pages を開き、Build and deployment を Deploy from a branch にします。
4. Branch を main、フォルダーを / (root) にして保存します。
5. GitHub Pages が表示する https://<ユーザー名>.github.io/<リポジトリ名>/ を iPhone の Safari で開きます。
6. Safari の共有ボタンから「ホーム画面に追加」を選び、追加します。

通知は iOS 16.4 以降の iPhone で、ホーム画面に追加したアプリから許可できます。
アプリを開いている間に届きます。
初回にアプリ内の「出力」メニューから通知を有効にしてください。
アプリを閉じている間も通知するには、サーバー側の Web Push 配信機能が別途必要です。

予定、履修、休み期間はブラウザー内に保存され、GitHub へ送信されません。
ただし、Windows と iPhone の保存内容は自動同期されません。端末変更時に引き継ぐ機能は別途必要です。
公開後にファイルを更新した場合、Service Worker が新しい版を取得するまで少し時間がかかることがあります。

バイト給与は「バイト給与を設定」から3つの勤務先名、時給／件数単価、金額を設定します。
各シフト・添削依頼の登録時に勤務先を選ぶと、選択中の月の給与見込みへ反映されます。
見込み額は税金、交通費、割増賃金などを含みません。