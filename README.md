## 保護猫ハウスのホームページ
公開URL：[https://yanagisawa-noriko.github.io/my-cat-shelter/](https://yanagisawa-noriko.github.io/my-cat-shelter/)

専門学校1年次の授業で作成した、保護猫活動を紹介するWebページです。<br>
使用技術は **HTML/CSSのみ** です。

実際に運営している保護猫ハウスです。<br>
新しい里親との出会いを支援しています。<br>
せっかく作ったページを、 **GitHub Pagesで公開してみよう！** と思い、試してみました。 

### 🛠️リポジトリ作成の流れ
- GitHubにログイン
- Repositories で New をクリック<br>

【項目に入力】
- Repository name　→my-cat-shelter
- Description　→空き家活用と保護猫活動をテーマにしたWebページ
- Public/Private　→選択✅ **Public（公開）**

### 🔄ローカルからGitHubにアップ（push）
- cd path/to/your/project(プロジェクトフォルダに移動)
- git init(初期化)

  - ※ ブランチ名がmasterだったらリネーム（最近はmainが主流）<br>
  - ※ git branch -m main

- git remote add origin 【ｈttps://github.com/～～】(GitHubからURLをコピペ)
- git add .
- git commit -m "最初のアップロード"
- git push -u origin main

### 🌍GitHub Pagesにデプロイ！
- GitHubでリポジトリページを開く
- 上部タブの「⚙ Settings」をクリック！【Code Issues Pull requests ・・・】の並びの右端
- 左サイドバーで「Pages」を選択
- Source（公開元）を選ぶ：
  - Branch: main
  - / (root) を選択
- Save ボタンを押す！
→ 公開URLが表示される！✨✨
