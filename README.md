Fuji Xerox Linux 用プリンタードライバーフリーソフトウェアモジュール
===================================================================

Debian パッケージのソースは公開されていない。
元々のソースが GPL-2+ なので、適当に作成してみた。無責任無保証

ソースの取得先
--------------

[富士ゼロックス Linux用 プリンタードライバーフリーソフトウエア・モジュール](http://www.fujixerox.co.jp/download/apeosport/download/c4300series/linux_module.html)


パッケージの作成方法
--------------------

通常の `git-buildpackage` の手順と同じ.

注意
----

FujiXerox さんは

<pre>
本モジュールは有用と思いますが、頒布にあたっては、当社は、いかなる保
証も行ないません。また、本プログラムおよび付随する情報等に対応するプ
リンターの製造・配布元である富士ゼロックス（株）は、本プログラムおよ
び付随する情報等に関するお問い合わせは受け付けておりません。
</pre>

との事。 また、我々も(他者の)サポートをする気はありません。 念のため。
