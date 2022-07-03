説明変数行列Xから行列Aを掛け、目的変数yを予測する。

<img src="https://latex.codecogs.com/svg.image?XA=y&space;" />

この時、実数値yとの誤差の二乗和を最小にするようにAを設定したい。

誤差を微分し極小値を求めると、この式が成り立つ。

<img src="https://latex.codecogs.com/svg.image?A&space;=&space;(X^{T}X)^{-1}X^{T}y" />

これをnumpyで実装し、ボストンの住宅価格で誤差を取得した。
