# demon
1box.cは重力場中の1つの箱の中のN個の剛体球の運動をシミュレーションする。
これは特別な設定は必要なく、ただコンパイルし実行するだけで利用できる。
衝突方法や壁の条件などを変更したければ簡単にいじることもできる。

gif.txtとplot.txtはセットで、シミュレーション結果をgifファイルとして生成することが出来る。
"position(N=300).txt"があるディレクトリ上で"gnuplot gif.txt"と命令するだけ。
粒子数などを変更したときにはgif.txt中のパラメータを修正すること。
