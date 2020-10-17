# amATO (あまと)
## cssを、プレゼンテーションで

### 構想
- Markdown x CSSでリッチかつお手軽にプレゼンテーション資料を作りたい
    - [Google製品ページ](https://store.google.com/jp/product/pixel_5)のようなリッチさを目指す
- ZennのようにGitHub連携など
- S3にデータ保存
- url限定共有が可能
- サーバサイドはNode.js or Scala?
- フロントはVue.jsを
- インフラはAWS or Heroku?
- とにかく開発速度を優先
    - Herokuにさくっと配置したいかも → Heroku docker run?
    - モノシリックな構成で
    - Infrastructure as code → Terraform with Heroku
- GitHub ActionsでCI/CD
- Googleアカウント連携のみ
