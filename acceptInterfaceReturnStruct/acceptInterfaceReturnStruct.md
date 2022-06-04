呼び出す側でinterfaceを定義
### usecaseに合わせて定義する

interfaceを引数にした関数の作成

テストがやりやすくなったり、リファクタリングの影響範囲を小さくできるなどのメリットがある

- インターフェースは構造体を利用する側のパッケージに定義する
- 引数をインターフェースで抽象化して受け取る
- NewXxxx()などをするときは構造体やポインタなどの実態を返す
- 構造体が使われる時になってからインターフェースを定義する