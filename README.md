# googletest を C 言語の単体テストに使う例

C++だけで使う分には、[この記事](https://qiita.com/yohm/items/db6597ffb87fa5480cea)を参考にすればOK


Cのコードをテストするときに必要な対応。

- `project(プロジェクト名 LANGUAGES CXX C)` ← `C`を追加
- `set(CMAKE_C_STANDARD 99)` を実行
