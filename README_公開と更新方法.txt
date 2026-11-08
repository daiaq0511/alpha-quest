ALPHA QUEST PWA 公開・更新ガイド

1. GitHubで無料アカウントを作り、新しいPublicリポジトリ（例: alpha-quest）を作成。
2. このZIPを解凍し、フォルダ内のファイル（index.html、sw.js、manifest.webmanifest、icons、assetsフォルダ）をリポジトリのルートにアップロードしてCommit changes。
3. Settings > Pages > Build and deployment > Deploy from a branch > main / (root) > Save。
4. 数分後に表示される https://ユーザー名.github.io/alpha-quest/ をiPhoneのSafariで開く。
5. Safariの共有メニュー > ホーム画面に追加。AQアイコンで起動できます。

更新するたびに:
A. index.htmlや画像など変更したファイルだけを同じリポジトリに上書きアップロードしCommit changes。
B. GitHub Pagesが再公開すると、利用者は同じURL/ホーム画面アイコンから最新版にアクセスできます。必要に応じてアプリを閉じて再起動してください。
C. オフラインキャッシュ構成を変更した場合はsw.js内の CACHE 名をaq-pwa-v2のように更新。

注意:
・現行版は試作。データは各ブラウザのlocalStorageに保存され、別端末への同期・会員認証・本物の共有・AI添削は未実装です。
・Safariのデータ削除や端末変更で記録が消える可能性があります。重要な個人情報や他人の録音を登録しないでください。
・GitHub Pagesの公開リポジトリに置いた資料は原則公開されます。会員限定資料を置かないでください。
・無料枠、規約、設定画面は将来変わる可能性があります。
