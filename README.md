# texlive-ja-devcontainer-template

VS Code Remote Developmentの機能を用いて、LaTeX環境を容易に構築するサンプルコードです。

[![](https://images.microbadger.com/badges/image/korosuke613/ubuntu-texlive-ja-devcontainer.svg)](https://microbadger.com/images/korosuke613/ubuntu-texlive-ja-devcontainer "Get your own image badge on microbadger.com")


Dockerイメージは、[ubuntu-texlive-ja](https://hub.docker.com/r/korosuke613/ubuntu-texlive-ja)を利用しています。

(**Dockerが必要です**)

## setup

1. `git clone https://github.com/korosuke613/texlive-ja-devcontainer-template.git`
2. VS Codeで`texlive-ja-devcontainer-template`を開く。
3. 拡張機能[Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)を追加する。
4. 左下の`><`アイコンを押して、`Rebuild Container`を実行する。
5. 待つ。
6. ワークスペースが開いたら、terminalを開き、`latexmk sample.tex`を実行する。
7. 上手くコンパイルできたらsetup完了！

## build

```bash
latexmk sample.tex
```

`sample.pdf`という実行ファイルができているはず。
