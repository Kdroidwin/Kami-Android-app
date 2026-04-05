# Kami-Android-app
おすすめ　アプリ集
- [ブログのアプリ集](https://kdroidwin.hatenablog.com/entry/2023/09/05/105304) - 初心者向け記事
- [予備のCodebergリポジトリ](https://codeberg.org/Kdroidwin/Kami-Android-app) - バックアップ
- これも追加すべきアプリがあったら教えてください。

- ⭐️⭐️超おすすめ
- ⭐️　 おすすめ（実用性が高い）
- `Proprietary`       
開発元が独占的に所有・管理しているソフトウェアや技術
ソースコードは公開されず、改変・再配布に制限がある。
プロプライエタリだから危険、オープンソースだから安全というわけではないです。

- `TD`   
トラスト前提（trust-based distribution）
主に第三者がビルド同一性を検証できない配布モデルにこのマークが付けられる。
このマークがない場合F-Droidでインストールできることが多い。

- 🔍
クライアント側の第三者監査あり
Proton系、Bitwarden、Mullvad VPN　など


- ⚰️
開発終了/2年以上更新していない

- ⚠️
プライバシーに少し問題があるアプリ

これらのマークはつけ忘れの恐れがあるのでissueやPullRequestしていただけると幸いです。

# ガイド
- 基本的にF-DroidやAccrescentからインストールしてください。Obtainiumを使う際もこのことを覚えておいてください。
- IzzyOnDroidはマルウェアあったケースもあるので注意してください。
- 公式ストアやGitHubでも検証されていないアプリには注意
- GooglePlayストアではなくAuroraStoreを使ってトラッカーや権限などを確認してください。
- Shizukuを使えばインストールは簡単になります。
[参照](https://x.com/Kdroidwin1/status/2037463883263479944?s=20)


# チュートリアル
- ObtainiumとAurorastoreをインストール
- Shizukuを導入




## 目次
- [動画](#動画)
- [ファイル関連](#ファイル関連)
- [音楽](#音楽)
- [ブラウザ](#ブラウザ)
- [5ch](#5ch)
- [SNS](#sns)
- [SMS](#sms)
- [メール](#メール)
- [本](#本)
- [カメラ関連](#カメラ関連)
- [画像関連](#画像関連)
- [APK関連](#apk関連)
- [アプリストア/ アプリ更新](#アプリストア-アプリ更新)
- [インストーラー](#インストーラー)
- [自動化](#自動化)
- [キーボード/ ボタンマッパー](#キーボード-ボタンマッパー)
- [ランチャー関連](#ランチャー関連)
- [システム](#システム)
- [AI](#ai)
- [カレンダー](#カレンダー)
- [天気](#天気)
- [電卓](#電卓)
- [時計](#時計)
- [PDF](#pdf)
- [メモ、記録](#メモ記録)
- [バッテリー](#バッテリー)
- [録音](#録音)
- [ポイント](#ポイント)
- [翻訳](#翻訳)
- [交通](#交通)
- [学習](#学習)
- [マップ関連](#マップ関連)
- [セキュリティ](#セキュリティ)
- [通信](#通信)
- [エミュレーター](#エミュレーター)
- [ゲームエミュレーター](#ゲームエミュレーター)
- [PCゲーム / ノベルゲーム系](#pcゲーム--ノベルゲーム系)
- [ゲーム関連ツール](#ゲーム関連ツール)
- [その他ゲーム](#その他ゲーム)
- [非推奨](#非推奨)


## 動画

- [YouTube ReVanced extended (anddea)](https://kdroidwin.hatenablog.com/entry/2024/05/01/142342)⭐️`TD` - Premiumとそれ以上の機能が使える。再生速度2倍以上、低評価表示(正確ではない)、SponsorBlock機能などがある。改造はクライアント側の機能なので、Premium限定動画は見れない。非rootユーザーは ReVanced/GmsCore のインストールが必須。
- [PipePipe](https://github.com/InfinityLoop1308/PipePipe)⭐️ - NewPipe のフォーク。アカウントなしでYouTubeやニコニコ、Bilibiliなどが見れる。SponsorBlock機能あり。
- [Tubular](https://github.com/polymorphicshade/Tubular) - NewPipe フォーク。SponsorBlock と RYD 対応。
- [StanDroid](https://github.com/kusamaru/StanDroid)`TD` - たちみどろいどのフォーク。ニコニコ動画を快適に見れるアプリ。広告ブロック機能、バックグラウンド再生。
- [Stremio](https://www.stremio.com/downloads) `Proprietary,TD`- メディアプレーヤー。アドオン経由でストリーミング再生ができる。アドオン追加推奨。
- [Animiru](https://github.com/Quickdesh/Animiru)⭐️`TD` - Aniyomi のフォーク。漫画機能をカットしてUIを改善したもの。Jellyfin も使える。myanimelist等のトラッカーも使用可能。
- [Miru](https://github.com/miru-project/miru-app)`TD` - ビデオ、コミック、小説の拡張機能をサポートする多用途アプリ。
- [M3UAndroid](https://github.com/oxyroid/M3UAndroid)`TD` - IPTVプレイヤー。M3Uプレイリストを使って世界中のTV番組を再生可能。  
  - [世界中の番組](https://iptv-org.github.io/iptv/index.m3u)  
  - [日本のみ](https://iptv-org.github.io/iptv/countries/jp.m3u)
- [VLC media player](https://nightlies.videolan.org/) - オープンソース。ほとんどの動画拡張子に対応している。画面に合わせてフィットできる。GooglePlay版は更新が遅いので非推奨。
- [mpvKt](https://github.com/abdallahmehiz/mpvKt) - mpv-android をベースにし、Jetpack Compose で構築された Android 用メディアプレーヤー。VLCよりカスタマイズ豊富。
- [mpvExtended](https://github.com/marlboro-advance/mpvEx) `TD`- mpv-android をベースにした多機能メディアプレーヤー。ファイル管理もできる。
- [Nextplayer](https://github.com/anilbeesetti/nextplayer) - シンプルなメディアプレーヤー。UIがかなり良い。
- [Xtra](https://github.com/crackededed/Xtra) - Twitchクライアント。広告なし、オープンソース。動画をダウンロードできる。
- [PurpleTV](https://purpletv.notion.site/Official-PurpleTV-Wiki-3d8d931ade15493dbb3dfe0ce0f6a5cc) `Proprietary,TD` - 旧TwitchMOD。公式TwitchのUIと同じ。

## ファイル関連

- [1DM](https://play.google.com/store/apps/details?id=idm.internet.download.manager) ⚠️⭐️`Proprietary,TD`- ダウンロードアプリ。YouTubeや有料サブスクを除くほぼ全ての動画サイトから動画をダウンロードや画像等ファイル抽出できる。torrentや画像、字幕ファイルなども対応。  
  有料版は広告非表示やテーマ変更が可能。
- [DownloadNavi](https://github.com/TachibanaGeneralLaboratories/download-navi) - FLOSSがいいならこちら。
- [LibreTorrent](https://github.com/proninyaroslav/libretorrent) - torrentクライアント。OSS。Material You、Android 15対応。
- [qBittorrent-Manager](https://github.com/Yash-Garg/qBittorrent-Manager) - qBittorrent(PCソフト)向けのリモートサーバー管理アプリ。導入難易度はそこそこ高い。
- [Unchained](https://github.com/LivingWithHippos/unchained-android) - Real Debrid と連携し、ホスティングサービスなどからダウンロード。
- [YTDLnis](https://github.com/deniscerri/ytdlnis) - yt-dlp のGUI版。動画ダウンローダー。SealPlusよりダウンロード設定が豊富。SponsorBlock対応。
- [Nyanpasu](https://apkpure.net/nyanpasu/com.zhenxiang.nyaa)`TD` - nyaa のアプリ。トラッカー機能あり。
- [PikPak](https://mypikpak.com/en-US) `Proprietary,TD`- 6GBまで無料のオンラインクラウドストレージ。torrentサイトのマグネットリンクからアップロードなしで6GBまでダウンロード可能。使わなければほぼ不要。
- [Nextcloud](https://apps.nextcloud.com/apps/android_nextcloud_app) - オープンソースのクラウドストレージおよびファイル共有プラットフォーム。自分のサーバーにインストールして使える。NASを使う手もある。
- [MiXplorer](https://www.apkmirror.com/apk/hootan-parsa/mixplorer-hootanparsa/)⭐️`Proprietary,TD` - 圧縮解凍、FTP、SMB、HTTPサーバー、nomedia作成、無限タブ、クラウドストレージ、USB OTG対応など、非常に高機能なファイラー。
- [MiXplorer Beta](https://www.apkmirror.com/apk/hootan-parsa/mixplorer-beta/)⭐️`Proprietary,TD` - MiXplorer の beta版。
- [MixArchive](https://www.apkmirror.com/apk/hootan-parsa/mix-archive/)`Proprietary,TD` - MiXplorer でzipファイル等を開くアドオン。
- [MixTagger](https://www.apkmirror.com/apk/hootan-parsa/mix-tagger/) `Proprietary,TD`- 動画や音楽にタグ付けできるアドオン。
- [Folder Sync](https://play.google.com/store/apps/details?id=dk.tacit.android.foldersync.lite) `Proprietary,TD`- ファイル同期アプリ。フォルダを定期的にSDカードやクラウドへコピーできる。
- [Syncthing-fork](https://github.com/researchxxl/syncthing-android) - オープンソースのファイル同期アプリ。クラウド不要。完全無料・無制限。
- [SD Maid SE](https://github.com/d4rken-org/sdmaid-se) `TD`- 不要なデータやゴミファイルを見つけて削除し、キャッシュや残存ファイルを整理するシステムクリーナー。

## 音楽

- [OuterTune](https://github.com/DD3Boh/OuterTune) `TD`- InnerTune の強化フォーク。高度なアカウント同期、ローカルメディア再生、複数キュー、新UI。
- [SimpMusic](https://github.com/maxrave-dev/SimpMusic) ⭐️- YouTube Music の非公式クライアント。広告なし、バックグラウンド再生、ダウンロード可。SponsorBlock、ReturnYouTubeDislike などあり。
- [Metrolist](https://github.com/MetrolistGroup/Metrolist) `TD`- YouTube Musicの非公式クライアント　
- [echo](https://kdroidwin.hatenablog.com/entry/2025/07/30/145603) `TD`- YouTube Music などに対応した音楽プレイヤー。
- [Musicolet](https://play.google.com/store/apps/details?id=in.krosbits.musicolet) ⭐️`Proprietary,TD`- シンプルでカスタマイズ性も高い使いやすい音楽再生プレイヤー。設定のバックアップ、曲への画像埋め込み、イヤホンボタンのカスタマイズなどが可能。
- [Poweramp](https://play.google.com/store/apps/details?id=com.maxmpz.audioplayer&hl=ja&gl=US) `Proprietary,TD`- カスタマイズ豊富な音楽プレイヤー。Musicolet と人気を二分している。
- [Oto Music](https://play.google.com/store/apps/details?id=com.piyush.music&hl=en_US)`Proprietary,TD` - シンプルで使いやすい音楽再生プレイヤー
- [pulsar](https://play.google.com/store/apps/details?id=com.rhmsoft.pulsar) `Proprietary,TD`- 上記以外の候補。
- [Retro Music](https://f-droid.org/en/packages/code.name.monkey.retromusic/) - 上記以外の候補。
- [Booming Music](https://github.com/ProjectOrbital/BoomingMusic?tab=readme-ov-file) - 上記以外の候補。
- [RootlessJamesDSP](https://f-droid.org/ja/packages/me.timschneeberger.rootlessjamesdsp/) - イコライザー。
- [BoostX](https://github.com/AumGupta/BoostX) `TD`- Androidデバイスの音量をシステム制限以上にブースト。
- [SongSync](https://github.com/Lambada10/SongSync) `TD`- 同期可能な歌詞ファイルを検索してダウンロードできる。マイナーな曲は非対応。
- [AntennaPod](https://github.com/AntennaPod/AntennaPod) - ポッドキャスト(インターネットラジオ)アプリ。

## ブラウザ

- [Cromite](https://github.com/uazo/cromite) ⭐️⭐️`TD`- プライバシーに配慮したChromium系ブラウザ。chrome拡張機能が使える。
- [IronFox](https://gitlab.com/ironfox-oss/IronFox) ⭐️⭐️`TD`- Firefox のフォークでMullの後継。arkenfox-user.js を使用し、Torブラウザの一部機能が使える。TorやCromiteを除くとAndroid最高クラスのプライバシー重視ブラウザ。ほとんどのアドオンが入るが、uBOのみ推奨。
- [Tor browser](https://www.torproject.org/ja/download/#android) ⭐️`TD`- オニオンルーティングで通信を多段リレーし、匿名化できるブラウザ。ダークウェブにもアクセス可能。
- [Iceraven-OLED](https://github.com/GoodyOG/Iceraven-OLED)⭐️`TD` - Firefox の機能強化版 Iceraven の OLED 版。ホーム画面ショートカットが優秀。
- [berry browser](https://play.google.com/store/apps/details?id=jp.ejimax.berrybrowser) `Proprietary,TD`- 候補。
- [ElixirBrowser](https://github.com/SF-FLAM/ElixirBrowser) `Proprietary,TD`- 候補。
- [WebLibre](https://github.com/FaFre/WebLibre) ⭐️- 候補。
- [Feeder](https://github.com/spacecowboy/Feeder) ⭐️- RSSリーダー。全文表示が可能。ブロックリスト対応。
- [Native Alpha](https://github.com/cylonid/NativeAlphaForAndroid)`TD` - WebViewを利用したブラウザ。広告ブロック可能。
- [Web Search Customizer](https://play.google.com/store/apps/details?id=com.brouken.websearch) `Proprietary,TD`- chmate のコピー画面下の検索ボタンや Amazon アプリのウェブ検索を好きなブラウザに変えられる。Firefox系ユーザーは不要。
- [Select Text to Search](https://f-droid.org/ja/packages/me.zhanghai.android.textselectionwebsearch/) - Androidのテキスト選択メニューにウェブ検索を追加する。

## 5ch

- [ChMate](https://play.google.com/store/apps/details?id=jp.co.airfront.android.a2chMate)⚠️ `Proprietary,TD`- おすすめの5ちゃんねるブラウザ。
- [ChMate dev版](https://deploygate.com/distributions/fc60f65f7ac36afc03e7570f42cf0108884641ca) ⚠️`Proprietary,TD`- dev版。
- [したらばStorm](https://play.google.com/store/apps/details?id=jp.everystorm.shitarabastorm&hl=ja)`Proprietary,TD` - 軽量でChMateライクなUIを持つ5ちゃんねるブラウザ。
- [APIMateR_Shizuku](https://github.com/areteruhiro/apimater_Shizuku) `TD` - ChMateで5ちゃんねるの過去ログをブラウザではなくアプリ内で見れる。巨人小笠原の奴より優秀。
- [必死チェッカーdroid mod](https://github.com/Kdroidwin/hissi) ⚰️`Proprietary,TD`- 5ちゃんの必死チェッカービューワー。ブラウザを開かずに ChMate 内で見れるので便利。全画面表示やリンクコピーボタンなども追加。
- [AAroid](https://apkpure.com/jp/aaroid-%E3%82%A2%E3%82%B9%E3%82%AD%E3%83%BC%E3%82%A2%E3%83%BC%E3%83%88%E7%AE%A1%E7%90%86%E3%80%81%E7%B7%A8%E9%9B%86%E3%83%84%E3%83%BC%E3%83%AB%EF%BC%89/aaroid.nekoneko.adeam.clipmemo) ⚠️⚰️`Proprietary,TD`- AA(アスキーアート)や長文コピペ・定型文の保存、貼り付けを便利にする。マッシュルームとしての起動も可能。

## SNS

- [Twitter Revanced piko](https://github.com/crimera/twitter-apk)⭐️`TD` - Twitterアイコンへ変更、下タブの編集、動画ダウンロード、Twitter feature flags、広告やその他迷惑要素の非表示。
- [SlimSocial for Facebook](https://github.com/rignaneseleo/SlimSocial-for-Facebook) - プライバシーを考慮した軽量なFacebookアプリ。広告ブロック、ダークモード対応。
- [PixEz flutter](https://github.com/Notsfsssf/pixez-flutter) ⭐️`TD` - Pixiv非公式クライアント。人気順検索、広告ブロック、ユーザーミュート機能あり。UIは公式より良い。
- [Myinsta](https://t.me/instasmashrepo) `Proprietary,TD`- Instagram の改造版アプリ。広告ブロックやゴーストモードなど。
- [InstaEclipse](https://github.com/ReSo7200/InstaEclipse) `TD` - Instagram の広告・アナリティクス削除、ゴーストモード。フィードの不要要素を取り除く Xposed / LSPosed モジュール。
- [Infinity](https://github.com/Docile-Alligator/Infinity-For-Reddit?tab=readme-ov-file) `TD` - Reddit クライアント。もちろん英語。Revanced Manager等でアンロック可能。
- [Aliucord](https://github.com/Aliucord/Manager/tree/v1.1.1) `TD` - Discord の非公式改造クライアント。UIは公式と同じ。カスタムプラグイン、複製アカウント、AMOLEDブラックテーマ、メッセージお気に入り、翻訳機能など。
- [Kettu](https://github.com/C0C0B01/Kettu) `TD` - Discord の非公式改造クライアント。Vendetta のフォークである Bunny のさらにフォーク。Aliucord と違い最新。kettuManager からインストール。
- [Nagram](https://github.com/NextAlone/Nagram) `TD` - NekogramX のフォーク。Telegram の非公式クライアント。翻訳機能あり。
- [Forkgram](https://f-droid.org/ja/packages/org.forkgram.messenger/) - Telegram公式フォークの候補。
- [Telespeed](https://github.com/Xposed-Modules-Repo/io.github.tehcneko.telespeed) `TD` - Telegram のダウンロード速度制限解除。
- [Killergram](https://github.com/Xposed-Modules-Repo/com.shatyuka.killergram) `TD` - Telegram のスポンサー付きメッセージを削除する Android Xposed モジュール。
- [LIME](https://github.com/Chipppppppppp/LIME) `TD` - LINE の広告削除、VOOMタブ削除、アプリ内ブラウザ無効化、既読をつけない機能など。
- [LIMEs](https://github.com/areteruhiro/LIMEs)⭐️`TD`  - LIME のフォーク。
- [SimpleX Chat](https://f-droid.org/en/packages/chat.simplex.app/)- メッセージアプリ。
- [OctoDroid](https://f-droid.org/ja/packages/com.gh4a/) - GitHub クライアント。

## SMS
- [QUIK SMS](https://github.com/octoshrimpy/quik) - SMSアプリ。QKSMS のフォーク。
- [Messages](https://f-droid.org/packages/org.prauga.messages/) ⭐️- 現代風デザインを持つSMS/MMS用メッセージングアプリ。自動でOTPを検出。上記のQuickベース。
- [Copy SMS Code - OTP Helper](https://f-droid.org/packages/io.github.jd1378.otphelper/) - 通知を読み取って、通知からOTPとコードを自動的にコピーできる。

## メール
- [Tuta](https://f-droid.org/ja/packages/de.tutao.tutanota/) ⭐️- 最も安全な電子メールサービスを自称する。
- [Proton Mail](https://github.com/ProtonMail/android-mail) ⭐️`TD` 🔍- プライバシー重視の暗号化メールサービス。
- [You Have Mail](https://github.com/LeanderBB/you-have-mail) - Google Play サービス(GMS)のプッシュ通知が使えない環境で Proton Mail の新着メールを通知したい人向け。
- [ThunderBird](https://github.com/thunderbird/thunderbird-android/releases) ⭐️`TD` - メールアプリ。
- [OpenKeychain](https://www.openkeychain.org/) - メールのエンドツーエンド暗号化。

## 本

- [mihon](https://github.com/mihonapp/mihon) `TD` - tachiyomi の後継。漫画を無料で読めるアプリ。自炊したものやネット上などから漫画を読める。  
  TachiyomiSY、aniyomi、Tachidesk(PC向け) などのフォークもある。
- [tachiyomi J2K](https://github.com/Jays2Kings/tachiyomiJ2K) `TD` - tachiyomi フォーク。動的カテゴリー、漫画情報編集、ライブラリでの並び替え、自動移行、ソースごとのカスタムUAなど。
- [tachiyomi s97](https://github.com/Saud-97/TachiyomiS97) `TD` - tachiyomiJ2K のフォーク。一部機能が追加。
- [Yōkai](https://github.com/null2264/yokai)⭐️`TD`  - TachiyomiJ2K のフォーク。NSFW/SFW ライブラリフィルターやローカルソースのメタデータ編集も可能。
- [keiyoushi extensions](https://github.com/keiyoushi/extensions) ⭐️`TD` - tachiyomi / Mihon の拡張機能レポジトリ。
- [Pupil](https://github.com/tom5079/Pupil) `TD` - hitomi ビューアー。
- [Web小説リーダー](https://play.google.com/store/apps/details?id=com.sampleb3.novel) ⚠️`Proprietary,TD`- なろう、カクヨム、pixiv、個人サイトなどに対応したビューアー。
- [Perfect Viewer](https://play.google.com/store/apps/details?id=com.rookiestudio.perfectviewer) `Proprietary,TD`- 最もおすすめする自炊ビューアー。PDF、Zip、RAR対応。フィルターは Lanczos3 推奨。PDFプラグインやファイルソースプラグインも併用推奨。
- [ComittoNxX](https://github.com/ComittoNxA/ComittoNxX) `TD` - Comitto の後継。自炊ビューワー。
- [Kotatsu-Redo](https://github.com/Kotatsu-Redo/Kotatsu-Redo) `TD` - 漫画アプリ

## カメラ関連

- [Google Camera Ports](https://www.celsoazevedo.com/files/android/google-camera/) ⚠️`Proprietary,TD`- Pixel以外にも使える。優秀な補正が可能。[解説](https://smartasw.com/archives/5492)
- [OSS DocumentScanner](https://github.com/Akylas/OSS-DocumentScanner) ⭐️`TD` - 写真をスキャンしてデータ化する。
- [vFlatScan mod](https://forum.mobilism.org/search.php?keywords=vflat&sr=topics&sf=titleonly) ⚠️`Proprietary,TD`-スキャナーアプリ 。

## 画像関連

- [QuickPic Gallery Mod](https://github.com/WSTxda/QP-Gallery-Releases/releases) `Proprietary,TD`- ギャラリーアプリ。アルバムをフォルダごとに分けられる。隠しフォルダ機能あり。  
  32bit非対応のスマートフォンは 10.0α 以上を入れる。
- [Gallary (by Ionut Iacob)](https://github.com/IacobIonut01/Gallery?tab=readme-ov-file) - モダンなギャラリーアプリ。UIは少し Googleフォト に似ている。
- [Aves ギャラリー](https://github.com/deckerst/aves?tab=readme-ov-file) ⭐️- シンプルと多機能を兼ね備えたギャラリーアプリ。
- [Google フォト Revanced](https://kdroidwin.hatenablog.com/entry/2024/08/24/105240) `TD`- 無料で無制限、劣化なしでアップロードできる。GmsCore が必須。
- [immich](https://github.com/immich-app/immich) - セルフホストの画像・動画バックアップ。Googleフォトの代替として使える。上級者向け。
- [Lightroom](https://play.google.com/store/apps/details?id=com.adobe.lrmobile) ⚠️`Proprietary,TD`- Adobe の編集アプリ。Revanced Manager でアンロック可能。
簡易的な加工ならSnapseedで十分
- [ImageToolbox](https://github.com/T8RIN/ImageToolbox) ⭐️`TD` - 画像編集に加えて、圧縮、OCR、PDF変換などができる。
- [PaperKnife](https://github.com/potatameister/PaperKnife) `TD` - プライバシー重視のPDFユーティリティ。結合、分割、圧縮、編集を100%ローカルで実行。
- [Photo Editor mod](https://github.com/PatrickAlex2019/PhotoEditor) ⚠️`Proprietary,TD`- UIがわかりやすく多機能な画像編集ソフト。
- [RealSR -NCNN(RealSR BigImage)](https://github.com/tumuyan/RealSR-NCNN-Android) ⭐️`TD` - Waifu2x-NCNN、SRMD-NCNN、RealCUGAN-NCNN、RealSR-NCNN、Real-ESRGAN、Anime4KCPP ベース。使い方は難しいが高機能で、ローカルで動く Android 最強クラスのアップスケーラー。

## APK関連

- [LuckyPatcher](https://www.luckypatchers.com/download/) `Proprietary,TD`⚠️⚠️- アプリを改造できる。広告をなくしたり、いろいろなアプリの有料プランに無料で入ったり出来る。マルウェアの危険性があるため、インストール非推奨だが一応紹介。非rootで動作するが、Root限定機能もある。
- [APK Explorer&Editor](https://f-droid.org/packages/com.apk.editor/) - アプリを改造できるアプリ。アプリの名前やパッケージ名、アプリ内の表示を変えたり、日本語対応していないアプリを対応させることも可能。
- [Apktool M](https://t.me/apktool_m) ⚠️`Proprietary,TD`- アプリを改造できるアプリ。Playプロテクトに引っかかるときがあるが、おそらく誤作動。
- [AntiSplit M](https://github.com/AbdurazaaqMohammed/AntiSplit-M) `TD` - 分割APK（APKS/XAPK/APKM）を単一の通常の.apkに結合。
- [LSpatch by JingMatrix](https://github.com/JingMatrix/LSPatch)⭐️`TD`  - 非root android単体でアプリやapkファイルにxposedをパッチをとして当てれる。確認できているのは disable flag secure / Adblock reborn（一部アプリ） / LIME など。disable flag secureのパッチを当てると漫画アプリやTVerなどでスクショ可能。
- [NPatch](https://github.com/7723mod/NPatch) `TD` - LSPatchのフォーク。UI変更や高速化、最適化、リファクタリングをしている。
- [ReVanced Manager](https://github.com/ReVanced/revanced-manager) ⭐️`TD` - Revanced patch をあてるためのアプリ。Revancifyのほうが楽かもしれない。
- [App cloner](https://appcloner.app/) ⚠️`Proprietary,TD`- アプリを複製できる。複垢におすすめ。権限の変更やアプリにパスワード、IMEI変更、fakegps、ファイアウォール、AndroidTV向けアプリに変更など様々なことが可能。Insularなどのほうが安全性は高い。
- [AppManager](https://github.com/MuntashirAkon/AppManager) ⭐️- アプリ管理。権限を見たりAPKファイルのバックアップ等が可能。APK抽出したいだけなら[kanade](https://github.com/alexrintt/kanade)を使うとよい。



## アプリストア/ アプリ更新
- [Aurora store](https://f-droid.org/ja/packages/com.aurora.store/) ⭐️⭐️- Playストア代替。匿名で使用可能。
- [Obtainium](https://github.com/ImranR98/Obtainium) ⭐️⭐️- アプリをGithubやF-Droidなどから取得して更新。似たアプリにApkupdaterなどがある。


## インストーラー

- [Install with Options](https://github.com/zacharee/InstallWithOptions) `TD` - Android 14 のターゲット SDK 制限のバイパス、特定のパッケージのダウングレード。分割APKのインストールや複数のアプリの一括インストール。
- [InstallerX-Revived](https://github.com/wxxsfxyzm/InstallerX-Revived) ⭐️`TD` - 最強クラスのAndroidインストーラー代替アプリ。APK / XAPK / APKS / APKM / ZIP内のAPK など対応。低いターゲットSDKのブロックをバイパス可能。無駄な警告をカットする。上級者向け。
- [KingInstaller](https://github.com/fcaronte/KingInstaller) `TD` - GooglePlay経由でインストールしたと見せかけるアプリインストーラー。ADBが使えるユーザーならpm installすれば良いだけでこのアプリは不要。


## 自動化

- [Klickr - Smart AutoClicker](https://github.com/Nain57/Smart-AutoClicker)  - 自動操作。自動的にクリックすることで繰り返しのタスクを楽に。
- [Tasker](https://tasker.joaoapps.com) `Proprietary,TD`- 色々なことを自動化出来る。特定の座標を指定するプラグインあり。
- [TaskErsettings](https://github.com/joaomgcd/TaskerSettings) `Proprietary,TD`- Taskerのヘルパーアプリ。
- [FRep2](https://play.google.com/store/apps/details?id=com.x0.strai.secondfrep) ⚠️`Proprietary,TD`- タッチ操作を記録・再生できるマクロツール。

## キーボード/ ボタンマッパー

- [Key Mapper](https://f-droid.org/ja/packages/io.github.sds100.keymapper/)⭐️ - 物理キーにショートカットを割り当てられる。Button Mapperでは有料の部分も無料で使える。
- [スミレ](https://github.com/KazumaProject/JapaneseKeyboard) `TD` - プライバシー、カスタマイズ性を重視したキーボードアプリ。



## ランチャー関連
- [Lawnchair](https://lawnchair.app/) ⭐️- Pixel Launcherに似たデザインで、カスタマイズ性をそこそこ重視したランチャー。オープンソース。更新頻度が高い。
- [Minma icon pack](https://play.google.com/store/apps/details?id=com.minma.icon.free&hl=en_US) ⚠️`Proprietary,TD`- アイコンパック。ダークでシンプル。
- [KWGT](https://play.google.com/store/apps/details?id=org.kustom.widget) `Proprietary,TD`- カスタムウィジェット作成アプリ。
- [QuickCursor](https://github.com/micku7zu/QuickCursor) `Proprietary,TD`- 指で操作するトラックパッド＋カーソルアプリ。クローズドソース。
- [Side bar screen Swiftly Switch](https://play.google.com/store/apps/details?id=org.de_studio.recentappswitcher.trial) ⚠️`Proprietary,TD`- 扇形サブランチャー。
- [fooview](https://play.google.com/store/apps/details?id=com.fooview.android.fooview) ⚠️⚠️`Proprietary,TD`- コピペや翻訳、フローティングメモでマルチタスクが捗る。開発元が…なのが。
- [Smartspacer](https://github.com/KieronQuinn/Smartspacer) - ウィジェット拡張アプリ。Pixel の At a Glance を root なしで拡張できる。
- [DroidOS](https://github.com/Katsuyamaki/DroidOS) - スマホをPCのような操作に変える Samsung DeX の代替。既存のAndroid上に、独自のウィンドウ管理レイヤーを被せる。
- [YoukiDEX](https://github.com/mrYouki/YoukiDex-Android-Desktop) - スマホをPCのような操作に変える Samsung DeX の代替


## システム
- [Shizuku fork by thedjchi](https://github.com/thedjchi/Shizuku) ⭐️⭐️- ADBコマンドやワイヤレスデバッグを用いてシステムAPIにアクセス。Taskerとの連携が可能、起動の自動化強化されたフォーク。
- [Better Internet Tiles](https://github.com/CasperVerswijvelt/Better-Internet-Tiles) - インターネット クイック設定パネルをAndroid11のようにして、Wifiパネルを復活させる。
- [Essentials](https://github.com/sameerasw/essentials) - 必須ツール。クイック設定のカスタマイズ、アプリロック、ボタンのリマップ、ステータスバーのアイコン表示制御、アプリ凍結、フラッシュライトの強度調整など。
- [Canta](https://github.com/samolego/Canta) ⭐️- システムアプリを簡単に削除。どれをアンインストールすべきかがわかる。
- [ShizuTools](https://github.com/legendsayantan/ShizuTools)⭐️ - システムアプリの削除、アプリのダウングレード、アプリ毎に音量調整、ADBシェルなどの機能が使える凄いアプリである。
- [App Ops Permission manager](https://play.google.com/store/apps/details?id=rikka.appops&hl=ja&gl=US) ⚠️`Proprietary,TD`- アプリ権限を管理。複数のメディアアプリで同時に音楽を再生可能にさせることも可能。Microsoft Visual Studio App Center Analytics、Microsoft Visual Studio App Center Crashes のトラッカーがあるので注意（appcenter.msなどのドメイン）。
- [ColorBlendr](https://github.com/Mahmud0808/ColorBlendr?tab=readme-ov-file) - デバイスのMaterialyouの色変更。微調整。
- [TapTap](https://github.com/KieronQuinn/TapTap) - 背面ダブルタップによるショートカットを追加。
- [System UI Tuner (Tweaker)](https://github.com/zacharee/Tweaker) - ステータスバーの調整など。
- [Amarok](https://github.com/deltazefiro/Amarok-Hider) - アプリを隠すアプリ。
- [Shelter](https://gitea.angry.im/PeterCxy/Shelter) - 「仕事用プロファイル」機能を利用して、アプリをインストールまたは複製できる。隔離されたスペースを提供するオープンソース (FOSS) アプリ。
- [Insular](https://f-droid.org/packages/com.oasisfeng.island.fdroid/) - 「仕事用プロファイル」機能を利用して、アプリをインストールまたは複製できる。隔離されたスペースを提供するオープンソース (FOSS) アプリ。
- [Link sheet](https://github.com/1fexd/LinkSheet) - Android12以降　URLから開かれるアプリの優先順位などを定める。ClearURLs や Fastfoward の機能も使える。
- [Copy](https://play.google.com/store/apps/details?id=com.weberdo.apps.copy) ⚠️`Proprietary,TD`- アプリ上の選択できないテキストをコピー。
- [KDE connect](https://kdeconnect.kde.org/download.html) - 複数デバイス間でやり取り。説明すると長くなるので省略。使いこなせればかなり凄いアプリ。
- [RustDesk](https://github.com/rustdesk/rustdesk) - TeamViewer の代替。セルフホスティング用に設計されたオープンソースのリモートデスクトップアプリ。
- [droidVNC-NG](https://f-droid.org/ja/packages/net.christianbeier.droidvnc_ng/) - Root権限が不要なVNCサーバー。
- [Quick Settings](https://play.google.com/store/apps/details?id=it.simonesestito.ntiles) ⚠️`Proprietary,TD`- クイック設定パネルをカスタマイズ。
- [Fake GPS Location](https://play.google.com/store/apps/details?id=com.lexa.fakegps)⚠️⚠️`Proprietary,TD` - 位置偽装。ポケモンGOとかではおそらく使えない。
- [Fake Sync](https://apkpure.com/jp/fake-sync-add-walking-data-to-fit/com.nauman.fakesync) ⚠️⚠️`Proprietary,TD`- Google Fit の歩数偽造アプリ。
- [Volume Styles](https://play.google.com/store/apps/details?id=com.tombayley.volumepanel&hl=ja&gl=US)⚠️`Proprietary,TD` - 音量調節パネルのデザインを変更。iOS やMIUIなどの見た目も可能。大きさや色を変更したり自作テーマも可能。ただし一部機種はイヤホン接続時のポップアップのときは変更されない。
- [NotiFilter](https://github.com/BURG3R5/NotiFilter) - 通知を自動でフィルタリングするツール。通知を自動タップや自動スワイプするツール。有料のBuzzKill の代替。低バッテリー・低メモリ消費。
- [Gadgetbridge](https://gadgetbridge.org/) - ベンダーアプリ(Sony Sound Connectなど)を必要とせずに、スマートウォッチ、ヘッドフォン、イヤホンなどのさまざまなガジェットをペアリングして管理できる、無料のオープンソースアプリ。
- [Extinguish](https://github.com/Moderpach/Extinguish) - 端末で画面がオフの状態でも他のアプリを動かし続けるためのアプリ。
- [Hail](https://f-droid.org/packages/com.aistra.hail/) - アプリの停止・サスペンドを柔軟に実行できる。バックグラウンドで不要に動き続けるアプリを効率よく制御し、バッテリー消費やリソース使用を抑える。Greenifyなどと似ているがこちらの方が最新OS向けで高機能かつ高性能。

## AI

- [PocketPal AI](https://github.com/a-ghorbani/pocketpal-ai) - インターネット接続を必要とせずにさまざまなAIと対話できます。DeepSeek R1 も可能。
- [VoiceGPT](https://github.com/WSTxda/Plugin-VoiceGPT) - chatGPTをアシスタントアプリにするプラグイン。


## カレンダー
- [ジョルテ](https://play.google.com/store/apps/details?id=jp.co.johospace.jorte) `Proprietary,TD`- カレンダーアプリ。シンプルかつ高機能。バックアップ可能。
- [Etar](https://f-droid.org/ja/packages/ws.xsoh.etar/) - FLOSSの超シンプルなカレンダーアプリ。
- [Fossify Calendar](https://github.com/FossifyOrg/Calendar) ⭐️- カスタマイズ性高めでよりモダンで機能豊富なUIを備えたカレンダーアプリ。ウィジェットも優秀。

## 天気
- [Breezy Weather](https://github.com/breezy-weather/breezy-weather) ⭐️- OSSでデザインが美しい天気アプリ。F-Droid版では気象庁のデータが使えない。

## 電卓
- [Opencalc](https://f-droid.org/ja/packages/com.darkempire78.opencalculator/) - シンプルな電卓。あのアプリのようにFacebookいいねボタンがないので良い。
- [Photo math](https://play.google.com/store/apps/details?id=com.microblink.photomath) ⚠️`Proprietary,TD`- 電卓。途中式も教えてくれる。revanced managerからアンロック可能。

## 時計
- [new-clock](https://github.com/qw123wh/new-clock) - AOSPベースの時計アプリ。

## PDF
- [MJ PDF](https://apt.izzysoft.de/fdroid/index/apk/com.gitlab.mudlej.MjPdfReader) - 高機能なPDFビューアー。PDFダークモード対応。他にも secure pdf 等も。

## メモ、記録
- [tasks](https://github.com/tasks/tasks) ⭐️- ToDOリスト。
- [anihyou](https://axiel7.github.io/anihyou/) - Anilist 非公式クライアント。アニメや漫画やライトノベルの記録。
- [記録](https://play.google.com/store/apps/details?id=jp.bondavi.likes.global&hl=ja) `Proprietary,TD`- 好きなものを何でも記録。メモ。
- [Joplin](https://f-droid.org/ja/packages/net.cozic.joplin/) ⭐️- メモアプリ。Markdownも使える。Dropboxを使ってエンドツーエンド暗号化通信で暗号化しながら同期可能。
- [Obsidian](https://obsidian.md/download) - 個人の知識管理やノート作成のためのアプリ。Markdown形式対応。
- [Orgzly Revived](https://github.com/orgzly-revived/orgzly-android-revived) - モバイル向けのアウトライナー（ノート管理＋ToDoアプリ）
- [Collabora Office](https://www.collaboraonline.com/collabora-office/) - Microsoft Office の代替。Microsoft Officeとの高い互換性と操作性を追求している。Android版もあり。LibreOfficeのフォーク。
- [Notely Voice: AI Voice to Text](https://github.com/tosinonikute/NotelyVoice) - 音声録音して自動で文字に変換する（音声→テキスト）。
- [Notification notes](https://f-droid.org/ja/packages/com.khuttun.notificationnotes/) - メモを通知に表示する。

## バッテリー
- [AccuBattery](https://play.google.com/store/apps/details?id=com.digibites.accubattery) `Proprietary,TD`- バッテリーの劣化具合を確認できる。

## 録音
- [Cube ACR](https://cubeacr.app/) `Proprietary,TD` - 電話録音アプリ。cube ACR helper のインストールが必須。そこまでプライバシーに配慮しているわけではないので注意。インターネット接続させないようにすると良い。このアプリが使えないなら ACR phone & APH を使うと良い。
- [Fossify Voice Recorder](https://github.com/FossifyOrg/Voice-Recorder) - ボイスレコーダー。

## ポイント
- [Googleアンケートモニター](https://play.google.com/store/apps/details?id=com.google.android.apps.paidtasks) ⚠️⚠️`Proprietary,TD`- プライバシーを半分売ってアンケートに答えてポイントゲットできる。他のアンケートサイトに比べると面倒くさくない。

## 翻訳
- [Translate You](https://github.com/you-apps/TranslateYou) - プライバシーに配慮した翻訳アプリ。写真から文字起こし可能だが、そこまで精度は高くない。

## 交通
- [SuicaNFCReader](https://github.com/edenparadisus/SuicaNFCReader)  `Proprietary,TD`- suicaやicoca等の残高確認。

## 学習
- [AnkiDroid](https://github.com/ankidroid/Anki-Android) - 暗記アプリ。ネット上から単語をダウンロードして覚えられる。英語学習などに使える。

## マップ関連
- [GMaps WV](https://f-droid.org/en/packages/us.spotco.maps/) - プライバシーに配慮したGoogleマップアプリ。WebViewを利用。
- [CoMaps](https://www.comaps.app/download/) - プライバシー重視のマップアプリ　OpenStreetMapベース
- [OsmAnd~](https://f-droid.org/en/packages/net.osmand.plus/) - プライバシーに配慮したマップアプリ。航空写真対応。
- [Geo Share](https://f-droid.org/packages/page.ooooo.geoshare/) - 地図リンク（例：Google Maps のURLなど）を他の地図アプリで開いたり、座標をコピーしたりできるツール。マップアプリを2つ以上使っている方におすすめ。
- [Traccar Client](https://github.com/traccar/traccar-client) - GPS 位置情報をリアルタイムで追跡・管理。
- [Headunit Revived](https://github.com/andreknieriem/headunit-revived) - AndroidタブレットをAndroid Auto(車載ディスプレイ)として使う

- [LineageOS関係のアプリ](https://www.apkmirror.com/apk/lineageos/) - 他にもおすすめ。

## セキュリティ

- [KeePassDX](https://www.keepassdx.com/) - オープンソースのオフラインパスワードマネージャー。
- [Bitwarden](https://github.com/bitwarden/android) 🔍⭐️- オープンソースのクラウドパスワードマネージャー。ローカル保存型のKeePassDXを正しく運用すればややセキュリティは上回る可能性があるが、使いやすさはこちらのほうが上。
- [Keyguard for Bitwarden](https://github.com/AChep/keyguard-app) - Bitwarden の Android クライアント。アプリの UX とパフォーマンスに重点を置きつつ、公式 Bitwarden Android アプリが持つすべての機能をサポートする。ただし公式実装との差異があるため、セキュリティは劣る可能性がある。
- [Aegis](https://github.com/beemdevelopment/Aegis) ⭐️- 2FA（二要素認証）アプリ。セキュリティと使いやすさ、良いUIを兼ねそろえている。他のデバイスと同期したい方は Proton Authenticator を勧める。
- [URLCheck](https://github.com/TrianguloY/URLCheck) - URL を開く前に分析（または共有）できるようにする。フィッシング手法からの保護に役立つ。
- [AirGuard](https://github.com/seemoo-lab/AirGuard) - AirTagを発見し、他人からのトラッカーから身を守る。
- [Cryptomator](https://cryptomator.org/downloads/)🔍⭐️ - クラウドストレージサービスに保存されているファイルを暗号化するためのオープンソースのソフトウェア。

## 通信

- [AdGuard](https://adguard.com/ja/adguard-android/overview.html) `TD`- かなりの広告をブロック出来る。LINEの広告も設定によってはブロック可能。NextDNS を使うことでこのアプリと同じくらいのことはできるが、アプリを使ったほうがアプリごとのホワイトリスト・ブラックリスト作成やファイアウォールが可能。
- [WiFi Analyzer](https://github.com/VREMSoftwareDevelopment/WiFiAnalyzer) - WiFi関連のツール。
- [Naiveproxy For Android](https://github.com/Dobiec/NaiveproxyForAndroid) - Shizukuを使用して naiveproxy を実行する。
- [Mullvad vpn](https://mullvad.net/ja) 🔍⭐️⭐️- 有料VPN。ポート転送はないので注意。
- [Air VPN](https://airvpn.org/) - 有料VPN。ポート転送あり。
- [Orbot](https://orbot.app/en/) - Torネットワークのクライアントとして動作し、匿名性の高いTorネットワーク上でのWebブラウジングや電子メール送受信、地図ソフトの使用などを実現する。簡単に言うと、ほとんどのAndroidアプリの通信をTor経由にする。上級者向け。
- [TorServices](https://f-droid.org/ja/packages/org.torproject.torservices/) - Orbotを拡張。
- [ShizuWall](https://github.com/AhmetCanArslan/ShizuWall) ⭐️- 特定のアプリを通信させないようにする。


## エミュレーター

- [UserLAnd](https://f-droid.org/ja/packages/tech.ula/) - Android上でUbuntu、Debian、Kaliなどの各種Linuxを動かせるアプリ。
- [Blackbox64](https://github.com/FBlackBox/BlackBox/releases) - Android仮想環境。rootなしでxposed使用可能。
- [VPhoneOS](https://vphoneos.com/mobile/index/) ⚠️`Proprietary,TD`- Android上で別のAndroidを動かせるAndroidエミュレーター。要rootアプリを使える。要求スペックは高い。32bitアプリも動かせる。
- [Termux（F-Droid ver）](https://f-droid.org/packages/com.termux/) - Linuxを動かせる。SSH接続が可能。Wine（Linux向けWindowsエミュレーター）も使える。revancifyやyt-dlpなども使える。
- [Winlator](https://github.com/brunodev85/Winlator) ⭐️- ExaGearをリバースエンジニアリングして64bit対応させたものと思われる。AndroidでWindowsソフトウェアを動かす最も簡単な方法（Wine使用）。


## ゲームエミュレーター
- [RetroArch](https://www.retroarch.com/index.php?page=platforms) ⭐️- ファミコン、GB、GBC、GBA、DS、3DS、N64、Wii、GC、PSP、PS2などに対応したゲームが遊べる。オープンソース。ちなみに mGBA プラグインはおすすめ。
- [Lemuroid](https://github.com/swordfish90/lemuroid) - NES、SNES、GB、GBA、DS、3DS、N64、PSX、PSPなどに対応したエミュレーター。オープンソース。
- [melonDS](https://github.com/rafaelvcaetano/melonDS-android) ⭐️- DSエミュレーター。オープンソース。
- [Azahar](https://github.com/azahar-emu/azahar) - Citraのフォーク。ニンテンドー3DSのゲームが遊べる。アップスケーリングあり。
- [Eden emulater](https://git.eden-emu.dev/eden-emu/eden) ⭐️- Switchエミュレーター。keys と firmware が必要。
- [Dolphin emulator](https://ja.dolphin-emu.org/download/) - GC / Wii エミュレーター。
- [Cemu Android](https://github.com/SSimco/Cemu) - Wii U エミュレーター。
- [PPSSPP](https://www.ppsspp.org/download/)⭐️ - PSPエミュレーター。アップスケーリングあり。タッチコントローラー設定変更可能。コントローラー対応。
- [Vita3K android](https://github.com/Vita3K/Vita3K-Android) - PS Vita エミュレーター。
- [DuckStation](https://github.com/stenzek/duckstation?tab=readme-ov-file#downloading-and-running) - PS1エミュレーター。
- [NetherSX2](https://github.com/Trixarian/NetherSX2-patch) - PS2エミュレーター。AetherSX2の改造版。パッチを当てる必要がある。AetherSX2 は公式ページのアーカイブからダウンロードすると良い。


## PCゲーム / ノベルゲーム系
- [Kirikiroid2　V2](https://avn2pointzero.wordpress.com/kirikiroid2/) ⚰️⚠️ `Proprietary,TD`   - PC向けノベルゲーム（吉里吉里）が遊べる。xp3ファイルが表示されないバグを修正済み。認証回避済み。
- [Kirikiroid2-Debloated](https://github.com/enaix/Kirikiroid2-debloated)⭐️ - 元の Kirikiroid2 から不要なものを削除している。
- [Artroid](https://myskrpatch.tistory.com/82)⚠️`Proprietary,TD` - PC向けノベルゲーム（Artemis Engine）が遊べる。
- [xsystem35-sdl2](https://github.com/kichikuou/xsystem35-sdl2) - AliceSoft の System 3.x のゲームを遊ぶ。
- [xsystem4-android](https://github.com/kichikuou/xsystem4-android) - AliceSoft の System 4 のゲームを遊ぶ。
- [winlator](https://github.com/brunodev85/winlator) - ExaGear をおそらくリバースエンジニアリングしたもの。開発途上だが64ビットソフトウェアも対応している。

## ゲーム関連ツール
- [Mantis Gamepad Pro Beta](https://play.google.com/store/apps/details?id=app.mantispro.gamepad) ⚠️`Proprietary,TD`- コントローラー用のスクリーンマッピングアプリ。
- [Console Launcher](https://github.com/likeich/console-launcher) `Proprietary,TD`- ゲームランチャー。
- [Screen Orientation Control](https://play.google.com/store/apps/details?id=net.mm2d.android.orientationfaker) `Proprietary,TD`- 画面回転制御。強制的に横画面にできる。

## その他ゲーム
- [shogidroid](http://shogidroid.siganus.com/) `Proprietary,TD`- 将棋アプリ。
- [PGsharp](https://www.pgsharp.com/)⚠️`Proprietary,TD`- ポケモンGO チートアプリ。

## 非推奨
- Videoder ⚠️`Proprietary,TD`
- YMusic ⚠️`Proprietary,TD`
- [Anilab](https://anilab.to) ⚠️`Proprietary,TD`- あるが、Animiru より機能が劣るのであまりおすすめではない。
- [Waifu2x ncnn](https://play.google.com/store/apps/details?id=pro.archiemeng.waifu2x) ⚠️`Proprietary,TD` - 使い方が難しいならありだがクローズドソースで広告＆トラッカーあり。
- [DraStic](https://play.google.com/store/apps/details?id=com.dsemu.drastic) `Proprietary,TD`- DSエミュレーター。すでに終了

- [WEB画像検索・ダウンローダ](https://play.google.com/store/apps/details?id=com.beta9dev.imagedownloader) ⚠️ `Proprietary,TD`- 改悪されているので微妙。1DMのファイル抽出のほうがおすすめ。
- Nekogram ⚠️⚠️⚠️マルウェア
- Cherrygram ⚠️⚠️⚠️マルウェア


