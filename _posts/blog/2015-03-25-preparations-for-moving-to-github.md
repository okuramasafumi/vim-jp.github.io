---
layout: blog
category: blog
title: github への移行準備
---

以下 Bram Moolenaar 氏が vim-dev にポストした内容。

https://groups.google.com/forum/#!topic/vim_dev/Io5A_Zir--k

-----
Google Code がシャットダウンする事になったので、我々は Vim のリポジトリの
為の新しい場所を必要としている。
多くのユーザーが各々の意見を出し、github を推す声が多いようだ。

これには不都合もあり、というのも、github へ移行するということは
Mercurial から git へ移行するということだからだ。
これが気に入る人もいるだろうし、そうでない人もいるだろう。
しばらくかけて慣れる必要があるだろう。
私は個人的には Mercurial コマンドの方が好きだ。使い方がより明確だからだ。
君たちは Mercurial コマンドから git への置き換え方法を見つける事が出来る。
例) https://github.com/sympy/sympy/wiki/Git-hg-rosetta-stone

この手法がちゃんと動作しているのかを確かめる為に、私は SNAPSHOT という形で
リポジトリを作った。我々はマイグレーション確認をする事が出来る。
私は既にパッチを push 出来る事は検証した。
しかしながら、現段階は code.google.com 上に残って開発をして行く事になるだろう。
マイグレーション以降にも既に issues は変更されてきたし今後も続いていくだろう。

これを見て欲しい: https://github.com/vim 

何かうまく行っていなかったらメーリングリストで返答して下さい。

注意: 本当のマイグレーションをする前に、現在の github 上のリポジトリは消してしまうよ!

-----
