# latex-remote-container-template
LaTeX用のコンテナー環境

# 機能
- タブでpdfを閲覧(Ctrl+Alt+v)
- 保存時オートフォーマット
- 保存時オートビルド
- pdf->texの参照(pdfをCtrl+クリック)
- tex->pdfの参照(Ctrl+Alt+j)

# pLaTeX以外の対応
pLaTeX以外に以下に対応
- pdfLaTeX
- upLaTeX
- XeLaTeX
- LuaLaTeX
.vscode/settings.jsonの`"latex-workshop.latex.recipe.default"`を変更することでビルド対象のLaTeXの種類を変更可能

# 正常に機能しない場合
Dockerfileを編集してtexlive-fullパッケージのインストールを追加してコンテナーをリビルドしてみてください(容量が大きいので注意)．
