### PCP定理について

---

### はじめに

+++
probabilistically checkable proof(確率的検査証明)

SNARKs, STARKs, Bulletproofs, Aurora またはそれらの応用である
(Zcash) and scalability (Ignis, StarkDEX, scaling Ethereum…を支える証明

---
### PCPとは
計算複雑性理論における PCP とは、確率的検査可能証明系を持つ決定問題の複雑性クラスである。


証明の中のたった数ビットの部分を知るだけ(検査)で証明が正しいことが言えてしまう


+++
それぞれの検査は少なくとも確率$\frac{1}{2}$で拒否するが

何度も検査が通れば、その証明は正しい

+++ 
### 厳密な定義とその能力

言語:$L$,検証者(oracle):$V$,任意入力:$x \in {0,1}$

- 完全性:$x /in L$ならばあるオラクル$/pi$で$V(/pi,x)$が確率１で受理

- 健全性:$x /in L$ならば任意のオラクル$/pi$に対して$V(/pi,x)$が$\frac{1}{2}$で拒否
 


---
### PCP定理

$NP=PCP[O(\log n),O(1)] $

$O(\log n)$の乱数列と$O(1)$ビットを検索でNPがとける


---





