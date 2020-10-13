<!--
目的: information set decodingについて理解する
キーワード: information set、手順、Lee-Brickell、Leon、Stern
-->

# 情報集合とは

### Definition 情報集合 (information set)
$\bf{G}$を$[n, k]$-線形符号の生成行列、$I$を$\{1, \ldots , n\}$の部分集合、${\bf G}_I$を${\bf G}=[{\bf g}_1, \ldots , {\bf g}_n]$の$i \in I$に対応する列${\bf g}_i$を並べた$k \times k$部分行列とする。${\bf G}_I$が正則行列であるとき、$I$を**情報集合**と呼ぶ。
</br></br>


### Theorem
${\bf C} \subseteq {\bf K}^n$を誤り訂正能力$t \geq 1$の線形符号とする。$w \in {\bf C}$を符号語、$e \in {\bf K}^n$をハミング重み$t$以下の誤りベクトルとし、$w'=w+e$とする。このとき、$L_I(w')=w$を満たす情報集合$I$が存在する。