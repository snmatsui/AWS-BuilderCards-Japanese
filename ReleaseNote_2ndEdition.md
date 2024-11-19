# AWS BuilderCards 2nd Editionリリースのお知らせ
# TL;DR
AWS BuilderCardsの新バージョンとなる、2nd Editionがリリースされることをお知らせ致します。今回は、現在のバージョン(当記事では便宜上、1st Editionと呼びます)から、2nd Editionへの変更点をまとめました。

# 1st Editionからの変更点
まず、皆様にお伝えしなければならないのは、2nd Editionには後方互換性がありません。これは、この後詳しく説明しますが、カードの表記、名称などが1st Editionから2nd Editionになって大きく変更されたからです。このため、例えば1st Editionと2nd Editionのカードを混合してプレイする、というような遊び方は、非推奨となることをご認識ください。
それでは、1st Editionから2nd Editionになって変更された点を、順番にご説明致します。

## 変更点①：TCOクレジットを廃止、クレジットを1種類に集約
1st Editionでは、TCOクレジット、AWSクレジット(またはAWSomeクレジット)の2種類のクレジットがあり、どちらのクレジットもビルダーカードを購入する時に使用していました。2nd EditionではTCOクレジットを廃止しました。これでAWSクレジットの1種類だけになるので、AWSクレジットとは呼ばずに、クレジットと呼ぶことになります。これにより、ゲームがよりシンプルで理解しやすくなり、ゲームがよりシンプルで直感的になり、新規プレイヤーでも理解しやすくなっています。
先ほど、1st Editionと2nd Editionでは互換性がないことをご説明致しました。もしも1st Editionのカードを使い、2nd Editionのルールでプレイするときは、TCOクレジットは無視してください。ただし、TCOクレジットを無視してプレイすることは、プレイヤーによっては混乱を引き起こす原因になり得ます。開発チームとしては、2nd Editionのルールは、2nd Editionのカードでプレイされることを、推奨いたします。

## 変更点②：クイックスタートラウンドの廃止
1st Editionでは、ゲーム開始時に、ビルダーカードの山から各自2枚ずつ引いて、合計12枚のスターターカードおよびビルダーカードが手元にある状態でした。2nd Editionでは、この2枚引く作業が廃止になり、手元にスターターカードが10枚ある状態で開始することになります。

## 変更点③：ミッションカードの追加
2nd Editionでは、ミッションカードという新しい種類のカードが追加されました。ミッションカードはサイドミッションとして、アーキテクチャのベストプラクティスやソリューションが記載されています。プレイヤーは割り当てられた特定のミッションを達成することで、追加のWell-Architectedポイントが得られる仕組みになっており、プレイヤー同士の競争がより戦略的になりました。
ミッションカードは、ゲームの複雑性が増すため、プレイするかどうかはオプションとなっています。もし一緒にプレイするチームの中に、AWSの初学者がいらっしゃる場合は、ミッションカードを使用せずにプレイすることも出来ます。

## 変更点④：スターターカードのカテゴリー追加と、組み合わせ効果の追加
スターターカードはゲーム開始時点でプレイヤーが持つ、オンプレミスのシステムが描かれたカードです。2nd Editionでは、このカードが専用のカテゴリーを持ち、コレクション用のスターターカードと区別しやすくなりました。
また、スターターカードの中に、組み合わせ効果を発動できるカードが追加されました。どのカードに追加されたかは、ここでは伏せておきますので、ぜひ実際にプレイしてみてください。
スターターカードはアイコンが変更されています。

# ネーミング、文言の変更
ここでは、ルールにはさほど影響しませんが、ゲームの進行に影響のある、ネーミングや文言の変更についてまとめました。以下に比較表をまとめています。

| As-Is | To-Be |
| :---- | :---- |
| Marketplace (マーケットプレイス) | Console (コンソール) |
| 1枚のカードを引く | アイコンに変更 |
| 効果を使用した後、このカードはリタイアする | アイコンに変更 |
| カードを購入する | Cloud-Adoption |