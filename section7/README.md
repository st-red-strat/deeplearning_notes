# 7. アルゴリズム学習
深層学習を少し勉強してみると、色々なタスクを訓練できるな、となるわけですが、そこで素朴な疑問なのですが
* 「学習」といえば算数である（？）算数のように、訓練から算術やアルゴリズムを実装できるようになるのだろうか？

と思った方がいるかもしれません。これはかなり興味深い問いのように僕には感じられます。ただし、これまで説明してきた深層学習の手法は、基本的には画像などのドメインを暗黙のうちに仮定しており、その帰納バイアスをそのままアルゴリズムの推論タスクに用いても上手く汎化しません。しかし、2014年にニューラルネットワークを万能チューリングマシンのように動作させるアイデアを皮切りに、近年ではいくつものアルゴリズム学習機を作ることが可能になってきています。ここではそれを実装を踏まえ解説します。

