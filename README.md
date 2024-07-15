#Dreamer - 崩れ往く世界の終わり-

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公が旅をしながら敵を倒して行くゲーム

## ゲームの遊び方
* 矢印キーでキャラクターを移動させる、スペースキーでビーム発射
* 敵のHPが0になったら次に進める
* 場面によって場所が切り替わる

## ゲームの実装
### 共通基本機能
* 背景画像と主人公キャラクターの描画

### 担当追加機能
* Allen（登場人物）が放つビーム機能（担当：林）：スペースキーを押した際に右前方にビームを放つ機能

### ToDo
- [ ] ボスを倒した際の画面の切り替え

### メモ
* クラス内の変数は，すべて，「get_変数名」という名前のメソッドを介してアクセスするように設計してある
* すべてのクラスに関係する関数は，クラスの外で定義してある