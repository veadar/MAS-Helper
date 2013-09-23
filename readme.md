#MAS Helper

##このアプリについて

MAS HelperはMac App Storeのアフィリエイトリンク作成支援ツールです。

Mac App Storeの<a href="http://www.apple.com/itunes/affiliates/resources/documentation/itunes-store-web-service-search-api.html">Search API</a>の内<a href="http://www.apple.com/itunes/affiliates/resources/documentation/itunes-store-web-service-search-api.html#lookup">Lookup</a>だけが生きていたので作りました。

##使い方

1. 初回起動時にカスタムテンプレートやアフィリエイトIDを設定します
2. Mac App Storeでアフィリエイトリンクを作成したいアプリを表示
3. URLをクリップボードにコピー
4. MAS Helperを起動するとカスタムテンプレートに則ったアフィリエイトリンクを作成、クリップボードにコピーします
5. 起動してから2分後に自動的に終了
6. Dockアイコンをクリックで再度アフィリエイトリンクを作成
6. 設定をリセットするにはクリップボードにMac App Storeのリンクがない状態でDockアイコンをクリック

##スクリーンショット

![image](https://raw.github.com/veadar/MAS-Helper/master/MAS_Helper.jpg)

##テンプレート中に使える変数一覧

返ってくるJSONの値とほぼ同じ。

<a href="http://hitoriblog.com/?p=3051">AppStoreHelper</a>のテンプレートをちょっと修正すればそのまま使えます。

<dl>
<dt>$artistId$</dt>
<dd>デベロッパーのID</dd>
<dt>$artistName$</dt>
<dd>デベロッパーの名前</dd>
<dt>$artistViewUrl$</dt>
<dd>デベロッパーのWebページのURL</dd>
<dt>$artworkUrl60$</dt>
<dd>小さいアイコンのURL</dd>
<dt>$artworkUrl100$</dt>
<dd>中くらいのアイコンのURL</dd>
<dt>$artworkUrl512$</dt>
<dd>大きいアイコンのURL</dd>
<dt>$averageUserRating$</dt>
<dd>平均レーティング</dd>
<dt>$averageUserRatingForCurrentVersion$</dt>
<dd>現在のバージョンの平均レーティング</dd>
<dt>$currency$</dt>
<dd>通貨単位</dd>
<dt>$description$</dt>
<dd>ソフトウェアの説明</dd>
<dt>$fileSizeBytes$</dt>
<dd>ファイルサイズ(バイト)</dd>
<dt>$formattedPrice$</dt>
<dd>フォーマットされた価格</dd>
<dt>$genres$</dt>
<dd>ジャンル(複数)</dd>
<dt>$price$</dt>
<dd>価格</dd>
<dt>$primaryGenreId$</dt>
<dd>一番目のジャンルのID</dd>
<dt>$primaryGenreName$</dt>
<dd>一番目のジャンルの名前</dd>
<dt>$readableFileSize$</dt>
<dd>読みやすく変換したファイルサイズ</dd>
<dt>$releaseDate$</dt>
<dd>リリース日</dd>
<dt>$releaseNotes$</dt>
<dd>リリースノート</dd>
<dt>$sellerName$</dt>
<dd>販売者の名前</dd>
<dt>$sellerUrl$</dt>
<dd>販売者のURL</dd>
<dt>$ssUrl1$</dt>
<dd>スクリーンショットのURL (一枚目)</dd>
<dt>$ssUrl2$</dt>
<dd>スクリーンショットのURL (二枚目)</dd>
<dt>$ssUrl3$</dt>
<dd>スクリーンショットのURL (三枚目)</dd>
<dt>$ssUrl4$</dt>
<dd>スクリーンショットのURL (四枚目)</dd>
<dt>$ssUrl5$</dt>
<dd>スクリーンショットのURL (五枚目)</dd>
<dt>$ssUrl6$</dt>
<dd>スクリーンショットのURL (六枚目)</dd>
<dt>$trackCensoredName$</dt>
<dd>アプリケーション名</dd>
<dt>$trackContentRating$</dt>
<dd>レーティング</dd>
<dt>$trackId$</dt>
<dd>ソフトウェアのID</dd>
<dt>$trackName$</dt>
<dd>ソフトウェアの名前</dd>
<dt>$trackViewUrl$</dt>
<dd>ソフトウェアのURL+PHG ID</dd>
<dt>$userRatingCount$</dt>
<dd>レーティング数</dd>
<dt>$userRatingCountForCurrentVersion$</dt>
<dd>現在のバージョンのレーティング数</dd>
<dt>$version$</dt>
<dd>バージョン</dd>
</dl>


##ダウンロード

Click Here → [Download](https://github.com/veadar/MAS-Helper/releases)

##Special Thanks & Used Codes

- <a href="http://memogakisouko.appspot.com/MenuBarAppleScript.html">MenuBarAppleScript</a>
- <a href="http://piyocast.com/as/archives/295">小数点以下を指定桁で切り捨て - AS Hole</a>
- <a href="https://www.iconfinder.com/icons/104872/app_icon#size=128">Brands & applications</a>