# marp-theme

## 使い方

VSCodeの場合

[Marp for VSCode](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)を使う場合、以下のようにテーマを設定できます。

```json
{
  "markdown.marp.themes": [
    "https://raw.githubusercontent.com/mofmof/marp-theme/main/mofmof.css"
  ]
}
```


この設定をして、以下のようなmarkdownファイルを作成できます。

```
---
marp: true
theme: mofmof
header: mofmof
footer: mofmof
---

<!-- _class: title -->

# サンプル

---

# すごいぞMarp

1. 1
2. 2
3. 3

```

こんなデザインです。

![image](https://user-images.githubusercontent.com/6434981/235052761-0e55e43f-aef7-416b-98ce-d3d0696bf7ea.png)

