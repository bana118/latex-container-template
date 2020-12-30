# latex-remote-container-template
LaTeX用のコンテナー環境

# 機能
- タブでpdfを閲覧(Ctrl+Alt+v)
- 保存時オートフォーマット
- 保存時オートビルド
- pdf->texの参照(pdfをCtrl+クリック)
- tex->pdfの参照(Ctrl+Alt+j)

# 対応エンジン
以下のLaTeXエンジンに対応
- pLaTeX
- pdfLaTeX
- upLaTeX
- XeLaTeX
- LuaLaTeX

デフォルトはpLaTeX  
.vscode/settings.jsonの`"latex-workshop.latex.recipe.default"`を変更することでビルドに使用するエンジンを変更可能

# 正常に機能しない場合
Dockerfileを編集してtexlive-fullパッケージのインストールを追加してコンテナーをリビルドしてみてください(容量が大きいので注意)．
またPDFが開けない場合はVSCodeを再起動してみてください．
