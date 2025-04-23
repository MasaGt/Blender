### 押し出し (Extrude)

- 押し出し (Extrude) とは、頂点・辺・面を押し出す事ができる機能のこと

    - イメージ的には引っ張ったり、押し込んだりする感じ

<br>

- #### 面の押し出し

    - 前提条件: Edit Mode にて面の編集モードで面を選択

    - 方法1: `左クリック` → `Extrude Faces` を選択

    - 方法2: `e` (ショートカットキー)

    - 方法3: 左のメニューバーにある `Extrude Region` を選択

    <img src="./img/Extrude&Inset/Blender-Extrude-Faces_1.gif" />

<br>

- #### 辺の押し出し

    - 前提条件: Edit Mode にて辺の編集モードで辺を選択

    - 方法1: `左クリック` → `Extrude Edges` を選択

    - 方法2: `e` (ショートカットキー)

    - 方法3: 左のメニューバーにある `Extrude Region` を選択

    <img src="./img/Extrude&Inset/Blender-Extrude-Edges_1.gif" />

<br>

- #### 頂点の押し出し

    - 前提条件: Edit Mode にて頂点の編集モードで頂点を選択

    - 方法1: `左クリック` → `Extrude Vertices` を選択

    - 方法2: `e` (ショートカットキー)

    - 方法3: 左のメニューバーにある `Extrude Region` を選択

    <img src="./img/Extrude&Inset/Blender-Extrude-Vertices_1.gif" />

<br>
<br>

参考サイト

[【Blender】押し出し・面の差し込み](https://saru-blender.com/extrude)

---

### 差し込み (Inset)

- 面の差し込みとは選択した面の内側に新しい面を差し込む機能

- ★差し込みは面にしかできない

- #### 面の差し込み方法

    - 前提: Edit Mode にて面の編集モードで面を選択

    - 方法1: `左クリック` → `Inset Faces` を選択

    - 方法2: `i` (ショートカットキー)

    - 方法3: 左のメニューバーにある `Inset Faces` を選択

    <img src="./img/Extrude&Inset/Blender-Inset-Faces_1.gif" />

<br>
<br>

参考サイト

[【Blender】押し出し・面の差し込み](https://saru-blender.com/extrude)

---

### 様々な面の押し出し方法

- 面の押し出しにのみ、様々な押し出し方法が提供されている

- 面を選択し `option (⌥)` + `e` を押すと、面の押し出し方法が表示される

    <img src="./img/Extrude&Inset/Blender-Extrude-Faces-Menu_1.png" />

<br>

- #### 法線に沿って押し出し (Extrude Faces Along Normals)

    - 選択した面を法線方向 (垂直方向) に押し出す

    <img src="./img/Extrude&Inset/Blender-Extrude-Faces-Normals_1.gif" />

    引用: [【Blender】押し出し・面の差し込み](https://saru-blender.com/extrude)

<br>

- #### 個々の面に沿って押し出し (Extrude Individual Faces)

    <img src="./img/Extrude&Inset/Blender-Extrude-Faces-Individuals_1.gif" />

    引用: [【Blender】押し出し・面の差し込み](https://saru-blender.com/extrude)

<br>

- #### 多様体を押し出し (Extrude Manifold)

    - ★★元の頂点や辺が削除され、きれいに面を押し込むことができる押し出し方

    <img src="./img/Extrude&Inset/Blender-Extrude-Faces-Manifold_1.gif" />

    引用: [【Blender】押し出し・面の差し込み](https://saru-blender.com/extrude)

    <br>

    - 通常の面の押し出しでは、面を押し込んだ時に元の頂点や辺が壁みたいに残る

    <img src="./img/Extrude&Inset/Blender-Extrude-Faces_2.gif" />

    引用: [【Blender】押し出し・面の差し込み](https://saru-blender.com/extrude)

<br>

- #### 押し出し ~ 繰り返し (Extrude Repeat)

    - 押し出しを任意の回数繰り返す

    <img src="./img/Extrude&Inset/Blender-Extrude-Faces-Repeat_1.gif" />

    引用: [【Blender】押し出し・面の差し込み](https://saru-blender.com/extrude)

<br>
<br>

参考サイト

[【Blender】押し出し・面の差し込み](https://saru-blender.com/extrude)