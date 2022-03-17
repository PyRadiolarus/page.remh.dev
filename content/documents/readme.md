---
title: "GPA Calculator for Yamagata University の使い方"
date: 2022-03-17T21:36:09+09:00
draft: false
---

このページでは、GPA Calculator for Yamagata University
(以下、本プログラム) の使い方について説明します。

1. 学務情報システムにログインする
    はじめに、学務情報システム(CampusSquare)にログインします。
2. メニューから「成績」を選ぶ
    次に、左側のメニュー「成績」のところにある、「単位修得状況照会」をタップ/クリックします。
3. 範囲を指定する
    表示範囲を選択する画面が表示されるので、任意の期間を選択します。
4. 成績を表示する
    英語科目名の出力については **"しない"**を選んでください。その後、「画面に表示する」ボタンをタップ/クリックします。
5. 表示された成績をコピーする
    画面に表示された成績のうち、No.1のものから1番下の合否の欄まで選択、コピーします。
6. 貼り付ける
    コピーした成績を[本プログラム](https://calc.remh.dev/)に貼り付けます。成績の表示方法については、画面の指示に従ってください。

使い方の説明は以上になります。不明点等ありましたら、私の[Twitter](https://twitter.com/4voltex/)までお願いします。

#### 余談

このプログラムはPythonで作成しました。なお計算時に入力された成績データは、計算目的以外で使用することはありません。
また、コード等はGithubで公開しています。興味のある方は[こちら](https://github.com/PyRadiolarus/yucalc-gpa)からどうぞ。

開発環境：

1. macOS Big Sur 11.3.1
2. VS Code 1.59.1
3. Python 3.9.6
4. Streamlit 0.88.0
5. Heroku-20 Stack

#### ライセンス {#license}

本プログラムのソースコードはMITライセンスに基づき公開しています。また本説明等に関してはCC
BY 4.0に基づき公開しています。

詳細は[こちら](https://github.com/PyRadiolarus/yucalc-gpa/blob/4d1d44ee1e9f638912283b1b2eac40321845009e/LICENSE.txt)からお読みください。

Written by
[PyRadiolarus](https://github.com/PyRadiolarus/)
