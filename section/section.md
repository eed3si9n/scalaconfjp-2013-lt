!SLIDE

脱お客様
=======

pull req の送り方
----------------

-[@eed3si9n](https://twitter.com/eed3si9n)
-[@eed3si9n_ja](https://twitter.com/eed3si9n_ja)

#SUB or how I learned to stop worrying about bad English and love open source.

!SLIDE

コップ本:

> Scala という名前は「スケーラブルな言語」を意味する。

#SUB The name Scala stands for "Scalable language."

!SLIDE

拡張性の高い言語
--------------

- 中置記法、implicit など

#SUB infix, implicit, etc enables natural extension.

!SLIDE

ライブラリで何でもできる
--------------------

#SUB you can do anything with libraries.

!SLIDE

Java, C#, C++
-------------

- アメリカの本社が標準ライブラリを作ってる
- 「本家」vs 「分家」

#SUB std libs written by the hq in the US.

!SLIDE

Scala
-----

- ML, twitter, github

#SUB both the lang and libs are developed openly.

!SLIDE

Scala
-----

- 必要なものがあればコミュニティで作る文化。

#SUB community-driven culture.

!SLIDE

コミュニティ
----------

- 英語圏が主流。もっと絡んでいこう。

#SUB the mainstream is English based.

!SLIDE

普段使ってるライブラリ
-------------------

- バグを見つけた

#SUB suppose you found a bug in a library.

!SLIDE

愛<span style="color:#FF1385">♥</span>を示す
===========================================

#SUB show your love.

!SLIDE

愛<span style="color:#FF1385">♥</span>とは
-----------------------------------------

- 信頼関係
- お互いが成功して欲しいと思っている

#SUB trust, and wishing for each other's success.

!SLIDE

伝わることが大事
--------------

- twitter で「使ってます。awesome!」
- blog 記事で「皆も使おう。awesome!」
- ML も参加する。

#SUB say it out loud.

!SLIDE

どこにバグを報告するか
-------------------

1. ガイドラインを読む
2. ML (google groups)
3. github issue

#SUB where to report bugs.

!SLIDE

物的証拠を積み上げる
=================

-事実と意見を分ける

#SUB prepare evidence. separate facts from opinion.

!SLIDE

バグ報告の3項目
-------------

1. repro steps (再現手順)
2. problems (問題)
3. expectation (期待されるふるまい)
4. notes (僕の考えたバグが起こっている理由)

!SLIDE

steps (再現手順)
---------------

- 開発者自身のコンピュータ上で問題を再現する手順
- スタックトレースのみとか無理
- markdown でフォーマットする

#SUB steps to reproduce on _dev_'s machine.

!SLIDE

problems (問題)
---------------

- 観測可能な事実を詳しく
- 意図的な動作かもしれない

#SUB what _you_ think is the problem.

!SLIDE

expectation (期待)
------------------

- 検証可能な期待される振る舞い
- 明らかな場合は "it works" もアリ

#SUB acceptance criteria.

!SLIDE

notes (備考)
------------

- RFC など根拠となるもの
- バグが発生理由の解析 (普通は必要無い)

#SUB justifications and analysis.

!SLIDE

バグ報告の例
----------

- Broken pipe [sbt/sbt#327](https://github.com/sbt/sbt/issues/327)
- xs:any's namespace [eed3si9n/scalaxb#147](https://github.com/eed3si9n/scalaxb/issues/147)
- multipart/form-data [unfiltered/unfiltered#1](https://github.com/unfiltered/unfiltered/issues/1)

!SLIDE


level 2: 再現データ
------------------

- github 上にバグを自動的に再現するプロジェクトを作る
- 開発者の手間が省ける

#SUB a github project with repro data.

!SLIDE

level 3: pull req
-----------------

- 問題を修正するコードを送る

#SUB sending fix code.

!SLIDE

pull req
--------

1. プロジェクトの作法を尊重する
2. トピックブランチを立てる
3. テストを書く

#SUB a few tips on sending a pull req.

!SLIDE

プロジェクトの作法を尊重する
------------------------

- ML は必ず参加
- 開発状況を把握する
- コミットコメントの形式

#SUB respect the project.

!SLIDE

トピックブランチを立てる
---------------------

- ブランチごと取り込まれるので必ず立てる

#SUB make a topic branch.

!SLIDE

テストを書く
----------

- バグを再現するテストを書く
- 当然テストは全て実行する

#SUB repro the bug using tests.

!SLIDE

実装の注意
---------

- 互換性に注意する。ライブラリの場合、勝手にシグネチャを変更しない
- 命名規則に合わせる
- タブ文字/空白文字インデントなど
- pull req 後レビューが入ることがある

#SUB compatibility, naming, and formatting.

!SLIDE

level 4: 機能の追加
-----------------

- background (背景)
- what this changes (変更点の説明)
- ドキュメントも更新する
- 既存のコードに手を入れる場合は ML に打診する

#SUB feature enhancements.

!SLIDE

pull req の例
-------------

- jsonp fix [unfiltered/unfiltered#8](https://github.com/unfiltered/unfiltered/pull/8)
- STArray fix [scalaz/scalaz#155](https://github.com/scalaz/scalaz/pull/155)
- String quotation [sbt/sbt#396](https://github.com/sbt/sbt/pull/396)
- subtitles [softprops/picture-show#32](https://github.com/softprops/picture-show/pull/32)

#SUB yea, these subtitles.

!SLIDE

ご清聴ありがとうございました
------------------------

#SUB thanks!

!SLIDE
