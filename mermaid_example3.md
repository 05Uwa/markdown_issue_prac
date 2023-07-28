## mermaidで記述できるダイアグラムのチュートリアル（７つのダイアグラムから１つを選択して記述）

# チュートリアル
#フローチャート
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
1. フローチャートでは、「graph」というキーワードに続けて図形の向きを指定します。
2. 向きは以下のようなオプションがあります。

TB: 上から下へ (Top-Bottom)
BT: 下から上へ (Bottom-Top)
RL: 右から左へ (Right-Left)
LR: 左から右へ (Left-Right)
TD: 同じく上から下へ (Top-Down)