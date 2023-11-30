# robosys2023
[![test](https://github.com/YamatoOsada/robosys2023/actions/workflows/test.yml/badge.svg)](https://github.com/YamatoOsada/robosys2023/actions/workflows/test.yml)

## インストール方法 
このリポジトリを任意の場所にクローンして使用。
```
git clone https://github.com/YamatoOsada/robosys2023.git
```

## plus
標準入力から読み込んだ数字を足す。
### 実行例
```
$ seq 10 | ./plus
55
```
seq 10で出力した数字を1から10まで順に足している。

## minus
標準入力から読み込んだ数字を引く。
### 実行例
```
$ seq 10 | ./minus
-55
```
seq 10で出力した数字を1から10まで順に引いている。

## mul
標準入力から読み込んだ数字を掛ける。
### 実行例
```
$ seq 10 | ./mul
3628800
```
seq 10で出力した数字を1から10まで順に掛けている。

## avg
標準入力から読み込んだ数字の平均を出す。
### 実行例
```
$ seq 10 | ./avg
5.5
```
seq 10で出力した1から10の平均を出している。 

## 必要なソフトウェア
* Python
  * テスト済み: 3.7〜3.10

## テスト環境
* Ubuntu 22.04.3 LTS

## 著作権, ライセンス
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
* このパッケージのコードの一部は，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
     * [ryuichiueda/my_slides robosys_2022 lesson4](https://github.com/ryuichiueda/my_slides/blob/master/robosys_2022/lesson4.md)
     * © 2022 Ryuichi Ueda
* © 2023 Yamato Osada
