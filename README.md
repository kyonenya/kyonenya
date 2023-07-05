# kyonenya

## 技術

- Next.js, React（フロントエンド）
- Node.js（バックエンド）
- TypeScript

## 作ったもの

### 1. [kyonenya.github.io](https://github.com/kyonenya/kyonenya.github.io)

- メインで運用しているブログサイト
- ノーフレームワーク、ブラウザ標準のAPIだけで作成したSPA（シングルページアプリケーション）
- 使用技術：Vanilla JS, TypeScript, Web Components

### 2. [manuscript](https://github.com/kyonenya/manuscript)

- 自分が書き溜めている研究草稿を管理するためのWebアプリ。日記アプリ [Day One](https://dayoneapp.com) からのJSONインポートや記事の一括印刷に対応
- Next.js でフロントエンドとバックエンドをまとめて一つのアプリとして開発中
  - next@13.4 の React Server Components と Server Actions に対応済
	  - [refactor: Next.js 13.4 App Routerへの移行 #21](https://github.com/kyonenya/manuscript/pull/21)
- 使用技術：Next.js, ~~tRPC, Tanstack Query~~->Server Components & Server Actions, Prisma, PostgreSQL, ~~Chakra UI~~→Tailwind CSS, Vercel, Supabase Auth, Isomorphic JavaScript (Universal JavaScript)

### 3. [npm - search summary](https://www.npmjs.com/package/search-summary)

- テキスト検索の結果文字列を生成するutil関数をnpmパッケージとして切り出して公開しておいた
  - 上二つのアプリで使用中
- 使用技術：TypeScript, 関数型プログラミング
 