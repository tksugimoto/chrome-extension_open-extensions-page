# これはなに？
Chrome拡張を一覧表示して検索/管理ページを開く/更新/有効化/無効化できるページをポップアップする

# 機能
* 拡張を一覧表示
	* 表示されたリンククリックで管理ページの対象拡張部分を開く
* 拡張を検索
	* 大文字小文字無視
	* 対象
		* タイトル
		* 説明文
* Rキーで拡張の再起動
	* 無効化 -> 有効化
	* 既に無効な場合は有効化
	* クラッシュ後など挙動がおかしい場合用
		* ※ content_scriptや権限などの追加は反映されないため開発中の拡張のリロードとしては使えない
* Dキーで拡張の無効化
* Oキーでオプションページを開く
	* ※ 拡張が有効 & オプションページが存在する場合のみ
