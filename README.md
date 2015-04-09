# CS_Practice C#の練習問題

## C#練習問題�@【変数・配列・foreach・for・while】

Visual C# を使って、次のようなコンソールアプリケーションを作成してください。

(1) 姓と名を格納する変数としてそれぞれ、myLastName, myFirstName を定義し、ご自身の
姓と名を格納してください。

(2) (1)で定義した姓と名を、コンソールへ次のように表示してください。
姓 : Suzuki
名 : Taro

(3) 姓を収納する配列 lastNames を定義し、次のデータを順番通りに収納してください。
Suzuki
Tanaka
Kimura
Shima

(4) 名を収納する配列 firstNames を定義し、次のデータを順番通りに収納してください。
Taro
Hanako
Jiro
Tetsuo

(5) (3)と(4)で定義した姓と名を、コンソールへ次のように表示してください。
ただし、foreach を使うこと。
Suzuki Taro
Tanaka Hanako
Kimura Jiro
Shima Tetsuo

(6) 次の距離をマイルに換算して次のように表示してください。ただし、表示桁を小数点で
揃えること。また、小数点2 位以下は四捨五入して表示すること。なお、1 マイルは
1.609344 km です。
ヒント： (123.45678).ToString("F3") で小数点以下4 位を四捨五入して3 位まで表示

青森→東京 715.0km(444.28 マイル)
飯田橋→渋谷 6.9km( 4.29 マイル)
飯田橋→横浜 33.8km( 21.00 マイル)

(7) 次の部屋の面積を坪単位に換算して、小数第2 位まで画面に表示してください。
なお、1 坪は3.3 平方メートルです。
101 号室 100 平方メートル(30.30 坪)
102 号室 75 平方メートル(22.73 坪)
103 号室 150 平方メートル(45.45 坪)

(8) 整数の配列 ages を作成し、年齢を表す次のデータを収納してください。
18
11
30
15
55
32
10

(9) (8)の配列ages を使って年齢が20 歳以上のとき「成人」と表示してください。
18
11
30 成人
15
55 成人
32 成人
10

(10) (8)の配列ages を使って次のように表示してください。
7-12 歳の場合：小学生、13-15 歳の場合：中学生
18
11 小学生
30
15 中学生
55
32
10 小学生

(11) (10)の表示機能をテストするため、0〜19 までの整数を収納する配列testAges を
新たに作成し、foreach で次のように表示させてください。
0
(中略)
6
7 小学生
(中略)
12 小学生
13 中学生
14 中学生
15 中学生
16
(後略)

(12) 入力された数値を読み取り、それを年齢と解釈して献血が可能な年齢か判別する
プログラムを作成してください。
※献血が可能な年齢→16 歳〜69 歳
・献血が可能な年齢の場合→「献血できます」と表示
・献血が不可能な年齢の場合→「献血できません」と表示

(13) 入力された数値を読み取り、それを年齢および身長として解釈しジェットコース
ターに乗れるか判別するプログラムを作成してください。
条件…６歳以上でかつ身長１２０cm 以上であること
・条件を満たした場合→「乗れます」と表示
・満たしていない場合→「乗れません」と表示
※ 提示されていない仕様があったとしても、それなりに解釈して作ること。

(14) 2 つの値A とB をコンソール入力から読み取り、これらを比較して次のように表示
するプログラムを作成してください。
・A とB が等しい時→「(A の値を出力)と(B の値を出力)は等しい」
・A がB より大きい時→「(A の値を出力)は(B の値を出力)より大きい」
・A がB より小さい時→「(A の値を出力)は(B の値を出力)より小さい」
例）6 は10 より小さい

(15) 在庫の値をコンソール入力から読み取り、在庫数に応じて次のように表示させる
プログラムを作成してください。
・在庫が０の時→「在庫がありません」
・在庫が３個以下の時→「在庫がわずかです」
・それ以外の時→「在庫があります」

(16) (15)のプログラムを、正の整数以外の数値や文字が入力された場合は再度の入力
を促すように変更してください。

(17) テストの成績をコンソール入力から読み取り、点数に応じて次のように表示させ
るプログラムを作成してください。なお、正の整数以外の数値や文字が入力された場合
は再度の入力を促すようにしてください。
・80 点以上→「A 判定」
・70 点〜79 点→「B 判定」
・60 点〜69 点→「C 判定」
・60 点未満→「D 判定」

(18) while 文を使って、「こんにちは」という文字列を5 回表示するプログラムを作成
してください。

(19) for 文を使って、「おはよう」という文字列を100 回表示するプログラムを作成し
てください。

(20) 次のように表示するプログラムを作成してください。
0 : かねだ
1 : かねだあ
2 : かねだああ
3 : かねだあああ
(中略)
10 : かねだああああああああああ

(21) 0 から100 までの数字をすべて合計し、結果を画面に出すプログラムを作成してく
ださい。（合計は5050）

(22) 0 から100 までの数字のうち、４の倍数のみ合計し、結果を画面に出すプログラム
を作成してください。（合計は1300）

(23) while 文を使って1 から20 までのうち偶数のみ表示するプログラムを作成してく
ださい。

(24) for 文を使って、以下のように1 から15 までの数字のうち、３で割り切れる数字
の時に「む!」と表示するプログラムを作成してください。
1
2
3 む!
4
5
6 む!
7
8
9 む!
10
11
12 む!
13
14
15 む!

(25) １から４０までの数字のうち、３で割り切れる時または３が付く時に「む!」と表
示し、８で割り切れる時または８が付く時に「だ!」と表示し、2 つの条件が共に満たさ
れた場合は「無駄無駄無駄無駄無駄」と表示するプログラムを作成してください。
（難易度：高）

(26) 1 から10,000 までの数字のうち、素数を画面に表示させるプログラムを作成して
ください。（難易度：高。知らない用語は検索すること。できなくても気にしないこと。
ただし、これまで学習した内容だけで作成できます。）

(27) 1 から5 まで加算して、次のように表示するプログラムを作成してください。
0+1=1
0+1+2=3
0+1+2+3=6
0+1+2+3+4=10
0+1+2+3+4+5=15

(28) 繰り返し処理を使って、1〜10 までの数字を加算して、次のように表示するプログ
ラムを作成してください。
カウント 合計
1 1
2 3
3 6
4 10
5 15
6 21
7 28
8 36
9 45
10 55

(29) 1 つがいの兎がいます。兎は産まれて2 か月で大人になり、毎月1 つがいずつの子
を産むこととします。兎が死ぬことは考慮しません。この条件のもとで、産まれたばか
りの1 つがいの兎は2 年の間に何つがいの兎になりますか？ 1 ヶ月毎に番の数を表示
するプログラムを作成してください。(難易度：高。参考キーワード：「フィボナッチ数」)

生まれたばかり||生後1 ヶ月||生後2 ヶ月以降||つがいの数
0 ヶ月後||1||0||0||1
1 ヶ月後||0||1||0||1
2 ヶ月後||1||0||1||2
3 ヶ月後||1||1||1||3
(中略)|| || || ||
24 ヶ月後||28657||17711||28657||75025
