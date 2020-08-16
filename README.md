[How to Build a Todo App with React, TypeScript, NodeJS, and MongoDB](https://www.freecodecamp.org/news/how-to-build-a-todo-app-with-react-typescript-nodejs-and-mongodb/)

### 初期設定, 準備
- $ yarn init [(doc)](https://classic.yarnpkg.com/ja/docs/cli/init/#toc-yarn-init)  
  対話型の設定セッションにより``package.json``の作成
- 作成 : .gitignore (node
)
- $ yarn add typescript -g  
  [yarn add](https://classic.yarnpkg.com/ja/docs/cli/add) : 依存関係の追加とパッケージのインストール
- $ yarn add express cors mongoose
- $ yarn add -D @types/node @types/express @types/mongoose @types/cors
- $ yarn add -D concurrently nodemon
- $ tsc --init (tsconfig.jsonの作成)
- 修正 : tsconfig.json [(commit)](https://github.com/RiSEblackbird/TS_Node_MongoDB/commit/94b787c19102c441b156b18b8f303e23584149b7)
- 修正 : package.json [(commit)](https://github.com/RiSEblackbird/TS_Node_MongoDB/commit/e6d56691d47c3821de4abb2e5e023c8ba76aeca6)
### Todoに関する定義
- 作成 : src/types/todo.ts [(commit)](https://github.com/RiSEblackbird/TS_Node_MongoDB/commit/45c69c2aaad6bb5637bbaf148093881966821ff9)  
  'mongoose'の``Document``型を拡張した``Todoインターフェース``を準備
- 作成 : src/models/todo.ts [(commit)](https://github.com/RiSEblackbird/TS_Node_MongoDB/commit/df005a75343738800194ba0a422864d471207f11)  
  ``Todoモデル``のmongoスキーマ定義
### APIコントローラーの作成
- 作成 : src/controllers/todos/index.ts [(commit)]()
