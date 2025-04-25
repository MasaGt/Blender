### 削除と溶解

#### ポイント

- Edit Mode で頂点/辺/面を選択した状態で `x` を押すと削除/溶解メニューが表示される

---

### 削除 (Delete)

- その名の通り、選択した頂点/辺/面を削除する機能

<br>

- #### 頂点の削除

    - 選択した頂点と**その頂点に接している辺と面**を削除する

    <img src="./img/Delete&Dissolve/Blender-Delete-Vertices_1.gif" />

    <br>

    - 面を選択し、頂点の削除を行うと**選択した面の頂点の接する辺と面も削除する**

    <img src="./img/Delete&Dissolve/Blender-Delete-Vertices_2.gif" />

<br>
<br>

- #### 辺の削除

    - 選択した頂点と**その辺に接している面**を削除する

    <img src="./img/Delete&Dissolve/Blender-Delete-Edges_1.gif" />

    <br>

    - 面を選択し、辺の削除を行うと**選択した面の辺に接する他の面も削除する**

    <img src="./img/Delete&Dissolve/Blender-Delete-Edges_2.gif" />

<br>
<br>

- #### 面の削除

    - 選択した面を削除する

    <img src="./img/Delete&Dissolve/Blender-Delete-Faces_1.gif" />

<br>
<br>

- #### 辺と面のみ削除

    - 多分あまり使わないのでスルー

<br>
<br>

- #### 面のみ削除

    - 選択した面は消えるが、**辺は残す**

    <img src="./img/Delete&Dissolve/Blender-Delete-Only-Faces_1.gif" />

<br>
<br>

参考サイト

[【Blender】削除・溶解の違い](https://saru-blender.com/delete)

---

### 削除 (Dissolve)

- 選択した頂点/辺/面を溶かすイメージ

<br>

- #### 頂点の溶解

    - 選択した頂点と**その頂点に接している辺**を溶かす

    <img src="./img/Delete&Dissolve/Blender-Dissolve-Vertices_1.gif" />

    <br>

    - 面を選択し、頂点の溶解を行うと**選択した面の頂点の接する辺も溶解する**

    <img src="./img/Delete&Dissolve/Blender-Dissolve-Vertices_2.gif" />

<br>
<br>

- #### 辺の溶解

    - 選択した辺と**その辺に接している頂点**を溶かす

    <img src="./img/Delete&Dissolve/Blender-Disssolve-Edges_1.gif" />

<br>
<br>

- 面の溶解

    - 選択した面を溶かして一つの面にするイメージ

    - ★隣り合っていないとうまくいかない

    <img src="./img/Delete&Dissolve/Blender-Dissolve-Faces_1.gif" />

<br>
<br>

参考サイト

[【Blender】削除・溶解の違い](https://saru-blender.com/delete)

---

### 注意点

- #### 溶解した面は subdivide できない

    <img src="./img/Delete&Dissolve/Blender-Dissolve-Subdivide_1.gif" />

    <br>

    - ナイフで切り分けることで subdivide と同じ結果にすることはできる

    <img src="./img/Delete&Dissolve/Blender-Dissolve-Subdivide_2.gif" />