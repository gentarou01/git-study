# Gitの勉強
 作成したファイルをリポジトリに追加するときには、 
 -git add コマンドを使います。 add は「足す、追加する」という意味の英単語です。
   -いったん変更情報を登録するこのことをステージングという。
   現在の変更情報の登録（ステージング）状況は次のコマンドで確認できます。
 -git status
   この追加という変更情報をリポジトリにコミットしましょう。

 -git commit -m "はじめてのコミット"
  git commit には必ずコミットコメント（メッセージ）を付ける必要があります。-m オプションに続けて、コメントを記載しましょう。

これでコミットが行われ、リポジトリにデータが登録されました。このコミットログを確認するためには、
-git log


