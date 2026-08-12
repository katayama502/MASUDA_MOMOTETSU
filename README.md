# ますだトレジャーレール — Netlify公開版

島根県益田市の実在スポット・店舗45地点をめぐるブラウザすごろくです。ビルドやAPIキーは不要で、そのままNetlifyへ公開できます。

## 最短の公開方法

1. このZIPを解凍します。
2. [Netlify Drop](https://app.netlify.com/drop)を開きます。
3. 解凍した `netlify-deploy` フォルダを画面へドラッグ＆ドロップします。
4. 発行された `https://〜.netlify.app` のURLを開きます。

## Git連携で公開する場合

1. このフォルダの中身をGitHubリポジトリのルートへ配置します。
2. Netlifyで「Add new site」→「Import an existing project」を選びます。
3. 対象リポジトリを選択します。
4. Build commandは空欄、Publish directoryは `.` のまま公開します。

`netlify.toml` が公開ディレクトリと基本的なセキュリティヘッダーを自動設定します。

## ファイル構成

- `index.html`：ゲーム本体
- `netlify.toml`：Netlify公開設定
- `_redirects`：URLアクセスをゲーム本体へ戻す設定
- `README.md`：この説明書

## 注意事項

- 実道路モードのGoogleマップと店舗写真は外部サービスを読み込むため、インターネット接続が必要です。
- 店舗の営業時間・営業状況は変更されることがあります。訪問前に各カードのGoogleマップ・公式情報をご確認ください。
- ゲーム内の価格・収益・所有表現はフィクションです。
- 本作は益田市および「桃太郎電鉄」シリーズの公式作品ではありません。

# MASUDA_MOMOTETSU
