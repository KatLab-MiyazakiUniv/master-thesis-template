# master-thesis-template

VS Code Remote Developmentの機能を用いて、片山研の修士論文執筆環境を容易に構築するテンプレートです。

## build

```bash
latexmk
```

`MasterPaper.pdf`という実行ファイルができているはず。


## optional
VS Codeのremote container機能を使えば、楽楽執筆が可能です。

1. `git clone https://github.com/korosuke613/texlive-ja-devcontainer-template.git`
2. VS Codeで`texlive-ja-devcontainer-template`を開く。
3. 拡張機能[Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)を追加する。
4. 左下の`><`アイコンを押して、`Rebuild Container`を実行する。
5. 待つ。
6. ワークスペースが開いたら、terminalを開き、`latexmk sample.tex`を実行する。
7. 上手くコンパイルできたらsetup完了！

