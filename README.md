# 2024年度 エンピリカルソフトウェア工学

## 目的

- 実際のソフトウェア開発でどのようなことが行われているかを実践する．
  - そのために，何らかのアプリケーション（CLIアプリケーション）の開発を行い，ソフトウェア開発の流れを学ぶ．

## 利用する技術

- 開発
  - git/[GitHub](https://github.com/), [GitLab](https://gitlab.com/)
    - [Conventional Commits](https://www.conventionalcommits.org/ja/v1.0.0/)
  - ビルドツール
    - [Gradle](https://gradle.org/)
    - [Pants](https://www.pantsbuild.org/)
    - [Bazel](https://bazel.build/)
    - [Buck](https://buck.build/)
    - [Please](https://please.build/)
    - [Blade](https://github.com/chen3feng/blade-build)）
  - リリース管理
    - [Semantic Versioning](https://semver.org/lang/ja/)
    - [DOI（Digital Object Identifier）](https://www.doi.org)
  - Web API
    - REST, [GraphQL](https://graphql.org)
- テスト
  - UnitTestツール
  - 各種サービス
    - [codebeat](https://codebeat.co/)
    - [Codacy](https://www.codacy.com/)
    - [Coveralls](https://coveralls.io/) など）
- デプロイ
  - CI/CD
  - [Homebrew](https://brew.sh/index_ja), [Chocolatey](https://community.chocolatey.org/) など
  - [Docker](https://docker.com/), [Podman](https://podman.io/), [Finch](https://github.com/runfinch)
- ドキュメント
  - README, badge
    - [Markdown](https://daringfireball.net/projects/markdown/)
  - ソフトウェアライセンス
    - [MIT](https://opensource.org/license/mit)
    - [GNU GPL](https://www.gnu.org/licenses/gpl-3.0.html)
    - [Apache License](https://www.apache.org/licenses/)など．
  - 静的サイトジェネレータ
    - [Jekyll](http://jekyllrb-ja.github.io/)
    - [Hugo](https://gohugo.io/)
    - [gatsbyjs](https://www.gatsbyjs.com/)など
  - 設定記述言語
    - Toml, Yaml, JSON, XML
  
### 利用する言語候補

- [Rust](https://www.rust-lang.org/ja)
  - https://rust-cli.github.io/book/index.html
- [Go](https://go.dev/)
- [TypeScript](https://www.typescriptlang.org/)（[deno](https://deno.land/)）
- [Kotlin](https://kotlinlang.org/)
- Java（モダンな書き方）
  - [All Loops Are a Code Smell](https://medium.com/swlh/all-loops-are-a-code-smell-6416ac4865d6)
  - [GraalVM](https://www.graalvm.org/) で native code にする．

## 教材候補

- Rust
  - [Command Line Apps in Rust](https://rust-cli.github.io/book/index.html#command-line-apps-in-rust)
  - [Command Line Rust](https://www.oreilly.com/library/view/command-line-rust/9781098109424/)
  - [プログラミング言語Rust](https://doc.rust-jp.rs/book-ja/)
- Kotlin
- TypeScript
- Deno
  - [Effective Deno](https://zenn.dev/uki00a/books/effective-deno)

## 開発候補

### 

## 進め方

- 第１講（2024-04-09）
  - 言語を決める．
- 第２講（2024-04-16）〜第13講（2024-07-02）
  - 開発
- 第14講（2024-07-09），第15講（2024-07-16）
  - 発表

## 参考資料

- [Command Line Interface Guidelines](https://clig.dev)
  - CLIアプリはどうあるべきかが書かれたサイト．
- [tamada/developing_flows](https://github.com/tamada/developing_flows)
  - ソフトウェア開発でプログラムを書き始める前に行わなければならないことを中心に書いた手引き書．
- [シェルスクリプトを学ぶ人のための「新しいUNIX哲学」 〜 ソフトウェアツールという考え方](https://qiita.com/ko1nksm/items/c55d067b55bbd561df11)
  - これまでに出版されている4つのUNIX哲学を踏まえて，現代のUNIX哲学について解説している．
