---
theme: penguin
layout: intro
fonts:
  sans: 'Robot'
---

# Astroで自分のLPを作ってみた

2023/10/27 @hakshu25

---
layout: image-right
image: /icon.JPG
---

# 自己紹介

- [hakshu](https://twitter.com/hakshu25)
- フリーランス Web エンジニア
- 正社員としては EdTech サービスやヘルスケアサービスの開発に携わってきました
- フロントエンド、サーバーサイド、インフラなど雑多にやってきました
- 最近は React を書いています

<style>
  li {
    font-size: 1.2rem;
  }
</style>

---
layout: center
---

# あれは4月のこと...

---
layout: center
---

# フリーランスの道へ <uim-rocket />


---
layout: center
---

# フリーランスになったし、自分のサイトでも作ってみるか！

---

# 採用した技術

- フレームワーク
  - Astro
- ホスティング
  - Cloudflare Pages
- CI
  - GitHub Actions
- CD
  - GitHub と Cloudflare Pages の連携

<style>
  li {
    font-size: 1.4rem;
  }
</style>

---

# なぜ Astro を選んだのか？

- 使ってみたかったというのが大きい
- Next.js で個人ブログは作ったことあるので、今回は違うものを使ってみたかった
- 静的サイトというところで SSG フレームワークを探していた
- パフォーマンスも高いらしい
  - https://astro.build/blog/2023-web-framework-performance-report/

<style>
  li {
    font-size: 1.4rem;
  }
</style>

---
layout: center
---

# 実際に作ったサイト

---
layout: iframe
url: https://sholab.net/
---

---
layout: text-image
media: /islands-architecture.png
---

# Astro とは？

- コンテンツフォーカスの Web フレームワーク
  - ブログ、ポートフォリオ、ドキュメントサイトなどに適している
  - [cypress のサイト](https://www.cypress.io/)も Astro で作られている
- アイランドアーキテクチャを採用
  - サーバーで静的にレンダリングする海(ページ)に、クライアントで動的にレンダリングする島が浮かんでいる
  - デフォルトで ゼロ JS で動作する
    - クライアントで動的にレンダリングする部分がある場合は JS を使う
  - Deno の Fresh もアイランドアーキテクチャを採用している

出典: https://docs.astro.build/ja/concepts/islands/

<style>
  li {
    font-size: 0.8rem;
  }
</style>

---
layout: image-right
image: /sourcecode.png
---

# Astro とは？

- .astro の拡張子のファイルをコンポーネントとして扱う
  - ファイルの構成は Vue や Svelte に似ている
- マークダウンもページとして扱える
- React, Vue, Svelte などと組み合わせてコンポーネント指向での開発が可能
  - 素の HTML でもコンポーネント使用可能

---
layout: iframe-right
url: https://docs.astro.build/ja/guides/deploy/
---
<style>
  li {
    font-size: 1.2rem;
  }
</style>

# Astro を使ってみて

- コンポーネントベースで開発できる
- デフォルトで TypeScript が使える
- 公式ドキュメントが充実している
  - デプロイレシピやフレームワークの導入方法など
- プラグインとツールも充実している

<style>
  li {
    font-size: 1.2rem;
  }
</style>

---

# ここも触りたい Astro!

- [Astro v3](https://astro.build/blog/astro-3/)
  - 今年の8月にリリースされた
  - View Transitions
    - ページ遷移時のアニメーションを簡単に実装できる
- [コンテンツコレクション](https://docs.astro.build/ja/guides/content-collections/)
  - ブログ記事などのコンテンツをコレクションとして扱える
  - スキーマの定義やクエリでのコンテンツのフィルタリングなどが可能

<style>
  li {
    font-size: 1.3rem;
  }
</style>

---

# まとめ

- Astro を使うことで、快適に LP を作ることができる
- 少し動きを持たせたいレベルのサイトは Astro で作るのが良さそう
- ブログも Astro に置き換えてみたい

<style>
  li {
    font-size: 1.4rem;
  }
</style>

---
layout: end
---

# Thank you! <streamline-emojis-man-astronaut-2 />
