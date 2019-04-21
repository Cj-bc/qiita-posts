Flaskで家計簿を書く
flask python

欲しい家計簿appがなかったので作成しようと思います。

# 動機

- 欲しい機能付きの家計簿がなかった
- いろいろ挑戦してみたかった

# 欲しい機能

- マルチプラットフォーム
  - iPhone
  - Apple Watch
  - CLI

- 様々なサービスとの連携
  - Siri
  - Qfixhowm

# 構成

マルチプラットフォームにするために、サーバーを用意して問い合わせるようにします。

| service     | 言語 |
|:-:|:-:|
| backend鯖   | Python  |
| iPhone App  | Swift   |
| Apple watch | Swift   |
| CLI         | python/Haskell? |
