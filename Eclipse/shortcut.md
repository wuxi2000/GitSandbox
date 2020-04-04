# コード修正

| 名前 | ショートカット | 備考 |
| ---- | -------------- | ---- |
|元に戻す|Ctrl + Z|
|やり直し|Ctrl + Y|
|コメントアウト1行|Ctrl + /|
|コメントアウトN行|Ctrl + Shift + /|
|選択行を1行上/下へ移動|Alt + ↑ or ↓|いちいちクリップボードで切り貼りせずとも移動できて良い！|
|行削除|Ctrl + D|
|選択カーソルから行末まで削除|Ctrl + Shift + Delete|
|前/後の単語を削除|Ctrl + Back space or Delete|
|選択した文字を大/小文字化|Ctrl + Shift + X or Y|
|キャメルケース⇔スネークケース|Ctrl + Alt + K|これはAnyEditToolいれればかも|
|リネーム|Shift + Alt + R|
|メソッドの抽出|Shift + Alt + M|
|コードフォーマット|Ctrl + Shift + F|Javaフォーマッタが動く。保管アクションにいれればいらない|
|インポート編成|Ctrl + Shift + O|不要なimportを削除。保管アクションにいれればいらない|
|クイックリファレンス|Ctrl + 1|
|矩形選択|Shift + Alt + A|矩形選択|

# カーソル
| 名前 | ショートカット | 備考 |
| ---- | -------------- | ---- |
|指定行へジャンプ|Ctrl + L|
|前/次の単語にカーソルをジャンプ|Ctrl + ← or →|
|前/次の単語を選択しながらカーソルをジャンプ|Ctrl + Shift + ← or →|
|行頭/行末にカーソルをジャンプ|Home or End|
|ファイルの先頭/末尾にカーソルをジャンプ|Ctrl + Home or End|
|戻る/進む|Alt + ← or →|マウスに戻る/進むボタンあると便利|
|前/次のメンバーにジャンプ|Ctrl + Shift + ↑ or ↓|
|対応する大括弧にジャンプ|Ctrl + Shift + P|括弧迷子になったときに頼りになります。Editboxも頼りになるけども。|

# 探す
| 名前 | ショートカット | 備考 |
| ---- | -------------- | ---- |
|インクリメンタル検索|Ctrl + J|最近はGlanceに変えてる。Glanceいいよ。Glance。( ˘ω˘)|
|検索と置換ダイアログの表示|Ctrl + F|
|検索ダイアログの表示|Ctrl + H|
|クイックアウトライン|Ctrl + O|その場でアウトラインを表示してくれる。検索もできる。|
|クイック型階層|Ctrl + T|その場で該当クラスの型階層を表示してくれる。一々ビューを開かなくてもできるので便利。|
|呼び出し階層を開く|Ctrl + Alt + H|該当メソッドがどこから呼び出されているか探せる。影響範囲調査などに。|
|ワークスペースから探す|Ctrl + Shift + G|該当メソッドを直接利用している箇所を探せる。|
|型を開く|Ctrl + Shift + T|クラス名を検索して開ける|
|リソースを開く|Ctrl + Shift + R|ワークスペース全体からファイルを検索できる。これがないと巨大システムでは迷子になる。|
|宣言を開く|F3|クラスやフィールドなど宣言されている箇所に飛べる！|
|開いているタブを探す|Ctrl + E|いま開いているタブ一覧がでる。そこからファイルを探せる|

# デバッグ
| 名前 | ショートカット | 備考 |
| ---- | -------------- | ---- |
|ステップイン|F5|次の1行を実行する(メソッド実行ならメソッド内部に入る)|
|ステップオーバー|F6|次の1行を実行する|
|ステップリターン|F7|いまのメソッドを最後まで実行し呼び出し元へ戻る|
|再開|F8|次のブレークポイントまで実行する|
|インスペクション|Ctrl + Shift + I|選択した変数の値をその場で確認(変数ビューでは値変更できる)|
|表示|Ctrl + Shift + D|選択した命令の結果を表示(表示ビューでもできる)|
|ブレークポイントの設定/解除|Ctrl + Shift + B|

※ショートカットと関係ないが条件付きブレークポイント、例外ブレークポイントは便利

# その他
| 名前 | ショートカット | 備考 |
| ---- | -------------- | ---- |
|上書き保存|Ctrl + S|
|すべてを上書き保存|Ctrl + Shift + S|
|閉じる|Ctrl + W|
|すべてを閉じる|Ctrl + Shift + W|
|ウィンドウの最大化|Ctrl + M|最大化時に押せば元に戻る|