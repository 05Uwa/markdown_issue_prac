## VSCodeでmermaidを利用する方法や便利な拡張機能

- mermaidとは
 コード図やガントーチャートやフロー図などが書ける
- mermaidを利用するときの手順
  1. Visual Studio Code で Markdown All in Oneをインストールします。
  2. インストールをしたあと、まずmermaidコードを打ち込んでみましょう

graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
  3. コードを打ち込んだことによりMermaid記法をプレビューに表示させることができます。
  4. ハイライト表示とは、Mermaid記法のコードに色を付け識別しやすくします。
  5. Markdown PDF はMarkdownを画像やPDFに出力したいとき、コマンドパレットで出力形式を選択しフォルダにあるファイルに出力させることができます。


- Visual Studio Codeのおすすめ拡張機能
  1. [Mermaid記法をプレビューに表示する](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)
mermaidをプレビューに表示させるときに便利な機能
  2. [Mermaid記法をハイライト表示](https://marketplace.visualstudio.com/items?itemName=bpruitt-goddard.mermaid-markdown-syntax-highlighting)

  3. [Mermaid記法で表示される図を画像やPDFに出力](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)


