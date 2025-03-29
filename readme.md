ASGIで動く  
デプロイボタンは追加していく予定です  
blog内に静的サイトを入れると認証されていない時にそのサイトが表示されます。  
画像は使えません。  
Cookieに yuki=True を設定すると認証されます。  
サーバーの起動時に掲示板の公式インスタンスに接続します。定期的にサーバーを再起動してください。  

Renderを使用する場合の手順  
1. GitHubアカウントを作成する  
2. リポジトリを作る(適当な名前のプライベートリポジトリにすることをおすすめします)
3. Import Codeを押し, <a href="https://github.com/taiga905/yuki-youtube-slim-3/">https://github.com/taiga905/yuki-youtube-slim-3/</a> と入力  
4. render.yamlを開いて編集(鉛筆のマーク)を押し, Nameの横の yuki-youtube-slim をサイトのURLの最初の部分にしたい文字列に変更する (yuki-yでは URLは https://yuki-y.onrender.com となる)  
5. Deploy to Renderボタンを押し, Service Group Nameに適当な文字列を入れApply(事前にRenderのアカウントを作っておく)
<br>
いろんなデプロイボタンです。使えたら教えて下さい。
<br>
<a href="https://render.com/deploy?repo=https://github.com/taiga905/yuki-youtube-slim-3">
<img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render">
</a>
<br>
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https%3A%2F%2Fgithub.com%2Ftaiga905%2Fyuki-youtube-slim-3)<br>
[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&name=yuki-tango-level&repository=https%3A%2F%2Fgithub.com%2Ftaiga905%2Fyuki-youtube-slim-3&branch=main)<br>
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://deploy.azure.com/?repository=https%3A%2F%2Fgithub.com%2Ftaiga905%2Fyuki-youtube-slim-3)
