ASGIで動く  

デプロイボタンは追加していく予定です  
blog内に静的サイトを入れると認証されていない時にそのサイトが表示されます。  
画像は使えません。  
Cookieに yuki=True を設定すると認証されます(Tは大文字でないと認証されません)  
サーバーの起動時に掲示板の公式インスタンスに接続します。定期的にサーバーを再起動してください。  

Renderを使用する場合の手順
1. GitHubアカウントの作成
2. リポジトリの作成(適当な名前のプライベートリポジトリにすることをおすすめします)
3. Import Codeを押し https://github.com/taiga905/yuki-youtube-slim-3/ と入力  
4. render.yamlを開き鉛筆のマーク(編集)を押し, Nameの横の yuki-youtube-slim をサイトのURLの最初の部分にしたい文字列に変更する(yuki-yだと, URLは https://yuki-y.onrender.com になる)  
5. Deploy to Renderボタンを押し, Service Group Name に適当な文字列を入れApply(事前にRenderのアカウントを作っておく)
<br>
# デプロイボタン
<br>
<a href="https://render.com/deploy?repo=https://github.com/taiga905/yuki-youtube-slim-3">
<img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>
