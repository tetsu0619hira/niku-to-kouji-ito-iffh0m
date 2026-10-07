# 肉と麹 ito — 提案用デモ

公式サイトではありません。制作：平林哲大。店舗情報は依頼文の指定値を使用し、未確定事項を【要確認】で表示。公開先は GitHub public / GitHub Pages / main / root。検索除外は noindex。

## 参考サイトと採用・変更点（制作前に検索・実ページを閲覧）
- https://hakko-monzen.com/ — 写真とロゴの導入、コンセプト→ニュース→メニュー→席→店舗情報→予約の6節。予約導線、白×赤のサンセリフと広い余白。昼夜の区分・席・駐車場が探しやすい点を採用し、itoでは予約とランチ時間を冒頭へ移動。
- https://www.kuradai-miso.com/kuradai-hassai — 店内大写真と店名、紹介→料理（昼・夜）→店舗情報の3節。Instagram・地図導線、暖色と明朝体・大きな余白。時間・価格・駅からの距離・席数の整理を採用し、実店舗写真は使わず明るい汎用素材と未確認表示に変更。
- https://kotsuzumi.co.jp/kotsuzumionri/ — 鼓傳の建物写真とブランド導入、紹介→ランチ→喫茶→予約→アクセスの5区分（検索取得内容を含む）。予約・Instagram導線、白と深い緑・明朝調。完全予約制と営業日告知の明示を参考に、itoでは電話・地図をスマホ下部に固定。既存レイアウト・文章・ロゴは転用しない。

参考選定時の評判確認：HAKKO MONZENはホットペッパーの利用者評価、蔵代醗彩は食べログの好意的な個別レビュー、小鼓御里は地域媒体での紹介と個別レビューを確認。評価の基準は媒体ごとに異なるため数値はデモに転用しない。小鼓御里には休業表示があるため、現在の営業推薦ではなく情報設計の参考として利用。
- https://www.mail.hotpepper.jp/strJ001225875/lunch/
- https://tabelog.com/kyoto/A2601/A260202/26044314/dtlrvwlst/
- https://www.ryoutan.co.jp/town/omise/2024/11/96977/

## 写真素材

Pexelsの汎用イメージ写真。店舗の写真、料理の実物写真、米麹そのものの写真ではない。全写真に重ねキャプション。画像は同梱しホットリンクなし。
- `img/rice.jpg`：ID 31555430 / Waskyria Miranda / 米と陶器。 https://www.pexels.com/photo/speckled-ceramic-bowl-with-uncooked-rice-31555430/
- `img/grain.jpg`：ID 31555431 / Waskyria Miranda / 米粒の質感。 https://www.pexels.com/photo/close-up-of-white-rice-in-ceramic-bowl-31555431/
- `img/tea.jpg`：ID 28719189 / Alina Skazka / 木と茶器。 https://www.pexels.com/photo/minimalist-tea-setting-on-wooden-board-28719189/
- 取得形式：`https://images.pexels.com/photos/<ID>/pexels-photo-<ID>.jpeg?auto=compress&cs=tinysrgb&w=1200`。茶器写真は同梱前にJPEG圧縮。ライセンス：https://www.pexels.com/license/

## 構成と更新

ビル2階・昼の時間→予約のおすすめ→お店について→昼メニュー→夜コース→営業時間とアクセス→問い合わせ。フォームなし。スクリプト不要のアンカー方式で、JavaScript無効時も全導線を利用可能。Google Fontsのみ外部フォント、地図は指定の住所検索iframe。Googleマップの外部リンクは依頼文のURLをそのまま保持。

確認待ち：英字表記、メニュー・セット内容・価格、麹調味料、夜営業、予約方法と受付時間、ネット予約リンク掲載可否、席・駐車場・入口、モバイルオーダー、臨時休業の案内方法、紹介文の承認。架空の価格や営業カレンダーは追加していない。
