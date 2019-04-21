初心者向けのhaskellのチュートリアルは何がいいのか
haskell tutorial

最近関数型にはまり、`Haskell`を始めました。
が、**良いチュートリアルがわからない...**
普通に調べても数学の話とかが出てきて余計わからない...(筆者は数学が苦手)
色々と漁ってみたので、独断と偏見に基づいてそれぞれについて書いてみます。

---

# Qiita: Haskell 超入門(@7shi)

|  |  |
|:-:|:-:|
| リンク | [Haskell 超入門](https://qiita.com/7shi/items/145f1234f8ec2af923ef) |
| 最終更新日時 | `2017/01/11`(トップ記事) |
| 言語 | 日本語 |

- Link: 

個人的には一番わかりやすかったです。日本語なのも嬉しい。
懇切丁寧に書いてくださっているので悩んだらおすすめです。
シリーズ展開していますが途中まで作成されています。


# haskell.org: Documentation

|  |  |
|:-:|:-:|
| リンク | [haskell.org documentation](https://www.haskell.org/documentation/) |
| 最終更新日時 | 不明 |
| 言語 | `English` |

- Link: 

チュートリアルのページというよりは、ドキュメント一覧です。


# wiki.haskell.org: learning resources

|  |  |
|:-:|:-:|
| リンク | https://wiki.haskell.org/Learning_Haskell |
| 最終更新日時 | `2019/02/25` |
| 言語 | `English` |

- Link: 

HaskellのWikiの、チュートリアルまとめのページです。
様々なチュートリアルが載っていますが各記事の更新日時に注意...

# wiki.haskell.org: Meta-tutorial

| | |
|:-:|:-:|
| リンク | https://wiki.haskell.org/Meta-tutorial |
| 最終更新日時 | `2012/06/13` |
| 言語 | `English/日本語` |

> The meta-tutorial aims to help you find the Haskell tutorials that you need.
>
> > Meta-tutorialは自分にあったHaskellチュートリアルを探すためにあります。(意訳)

用途別にチュートリアルの紹介がされています。
ちなみにこのページについては[日本語版](https://wiki.haskell.org/Metaチュートリアル)があります。

## Hitchhikers guide to haskell

| | |
|:-:| :-:|
| リンク | https://wiki.haskell.org/Hitchhikers_guide_to_Haskell |
| 最終更新日時 | `2014/05/04` |
| 言語 | `English` |

> チュートリアルの進み方がゆっくりだったり、退屈だったり、意味不明になるのにうんざりだって？ヒッチハイカーのガイドを試してみてください。

> 本テキストは読者にHaskellの実用的な側面を基本のきから紹介することを目的としています。（まず最初にI/Oを説明し、次にdarcs、Persec、QuickCheck、プロファイリングとデバッグと続いた後に最後いくつか説明します） 
> 読者には前提としてHaskellの最低限の基本知識を必要としています。といっても、どのように "hugs" や "ghci" を起動するか、 このレイアウトは2次元である といったくらいのことです。
> さらに本テキストの説明では一気に流れをとばしたりせず、一歩ずつ進めていき、読者が迷子にならないようにするつもりです。
> だから「パニックに陥らないでください」。

ナップザック問題を使ったチュートリアルです。
とはいえ数学苦手な筆者でも問題がなほどのレベルで解説されていました。
**コードは途中から動かない**[^1]ですが、そこまではかなり勉強になりました。
[日本語版](https://wiki.haskell.org/Haskellへのヒッチハイカーガイド)も一応ありますが翻訳途中のようです。
**日本語版は英語版とコードが異なったりするため、バージョンが違うと思われます**

個人的には以下のようなことが勉強になりました:

- 一度英語で手順を考え、それをコードに落とし込んでゆく

```haskell
main = read list of directories and their sizes
       decide how to fit them on CD-Rs
       print solution
```

[^1]: `QuickCheck`を使うコードがコピペでも動かないです。
