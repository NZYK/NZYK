# About me

Webアプリケーションエンジニアです。

業務では Ruby on Rails/ Vue.js / Python を中心に、Webアプリケーションの設計・開発・運用を行っています。バックエンド寄りですが、必要に応じてフロントエンドやインフラにも触れています。

技術の仕組みを理解することが好きで、業務とは関係なく自分で小さく実装して検証してみたりしがちです。

## My stacks

- Ruby / Ruby on Rails
- Python / FastAPI / Arq
- TypeScript / Vue.js
- Docker / ECS
- MySQL / Redis / Elasticsearch
- AWS / GCP
- CircleCI / GitHub Actions
- Rollbar

## Public repos overview

### [RubyとFFIを通じて見る他言語連携](https://github.com/NZYK/calc_with_rust)

RubyからRustで実装した関数をFFIで呼び出す実験的なgemです。

ABIやポインタを使った値の受け渡し、メモリ管理、Ruby実装との性能比較などを行いました。検証内容をまとめた[発表資料](https://github.com/NZYK/calc_with_rust/blob/master/marp/presentation.md)もあります。

### [WebGL2でGPGPUを行う](https://github.com/NZYK/wbgl)

WebGL2を使い、パーティクルの位置計算や衝突判定をGPU上で行う実験的なプロジェクトです。

CPUとGPUによる処理の違いを比較できる[デモ](https://nzyk.github.io/wbgl/)と、GPU・WebGLの仕組みからまとめた[発表資料](https://github.com/NZYK/wbgl/blob/main/marp/presentation.md)があります。

### [FastAPIとinjectorの構成を考える](https://github.com/NZYK/injector-fastapi-aiohttp-redis-tutorial)

PythonのDIライブラリである `injector` とFastAPIを組み合わせ、外部リソースの生成やライフサイクルを管理しやすい構成を検討したリポジトリです。

## Articles

調査や検証で得た知見をQiitaに書いています。

- [CircleCIのキャッシュ戦略を、落とし穴と対策例から整理する](https://qiita.com/no_zoo/items/73c3cd648d653c128309)
- [redis.ConnectionPoolとRedisクライアントの運用を検証する](https://qiita.com/no_zoo/items/f3e8984f9b2f5ad04050)
- [Rails・Devise・Sessionのログイン処理を整理する](https://qiita.com/no_zoo/items/3f7fd5cb9d1e0cde300a)

そのほかの記事: [Qiita](https://qiita.com/no_zoo)
