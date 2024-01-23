## 01.01. ぞんざいなHello ESYS

まずはC言語プログラミングの復習をしましょう．
今まで受けてきた授業の復習がてら、ウォーミングアップです．
以下のサンプルは「悪い例」です．こんな書き方をしてきた人は，これから心を入れ替えて下さい．
_（間違っているわけではないのですが、誤解を招きかねない書き方です）_

[01-01-HelloESYS-NotSoGood.c]([https://github.com/kameda-yoshinari/C-Programming-OpenGL/blob/main/01/01-01/01-01-HelloESYS-NotSoGood.c)

https://github.com/kameda-yoshinari/C-Programming-OpenGL/blob/main/01/01-01/01-01-HelloESYS-NotSoGood.c

[c](https://github.com/kameda-yoshinari/C-Programming-OpenGL/blob/main/01/01-01/01-01-HelloESYS-NotSoGood.c)

何が悪いのでしょうか？
次のプログラムを見る前に、４つは指摘できるといいですね．

ダウンロードして、このままでコンパイルしてください．
gccがコンパイルコマンドですね。単一ソースファイルの場合、特に指定しなければ実行ファイルは a.out という名前で生成されます．
実行ファイルを実行するときは、先頭に ./ (ドット スラッシュ）をつけてください．
（2021年度からこのような手順を習ってきていないという事態になってしまいました）
lsはディレクトリ内のファイル一覧を表示するbashのビルトインコマンドです．
（ls -l にすると，long listing オプションが入ってファイルの説明が詳しくなります）
fileコマンドはファイルタイプを判定するunixの（linuxの）プログラムです．
（詳しくは $ man file）


$ gcc 01-01-HelloESYS-NotSoGood.c
$ ls
$ ls -l
$ file 01-01-HelloESYS-NotSoGood.c
$ file a.out
$ ./out

プログラムを自分なりに修正してください．それをコンパイルし直してください．
修正はgeditというプログラムが分かりやすいと思います．(emacsでも可）

$ gedit 01-01-HelloESYS-NotSoGood.c
演習

01-01-ex1: ５階計算機システム Ubuntu linux（本授業）において、「ターミナル」とは何を指しますか？

01-01-ex2: このターミナルのようなインタフェースをアルファベット３文字で何と言いますか？その正式名称は何でしょうか？

01-01-ex3: なぜこのテキストばかりのウィンドウを「ターミナル（日本語では端末）」と呼ぶのでしょうか？

01-01-ex4: 似た表現にコンソールという用語があります．なぜコンソールというのか，英語の語源も調べて考えてみなさい．  
