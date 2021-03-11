# test
**太字** or __太字__

*斜体* または _斜体_

~~打消し戦~~

# 例
## このプログラムについて
加速度のデータをトリミングするプログラムです
## 入力
加速度ファイル(csv)

| Time |  ax  | ay | az |
| ---- | ---- | --- | --- |
|  12:31:12345  |  0.123  |  0.0123  |  0.623  |
|  12:31:12346  |  0.112  |  0.0131  |  0.523  |
|  …  |  …  |  …  |  …  |

## 出力
トリミング後の加速度ファイル(csv)
| Time |  ax  | ay | az |
| ---- | ---- | --- | --- |
|  12:31:12345  |  0.123  |  0.0123  |  0.623  |
|  12:31:12346  |  0.112  |  0.0131  |  0.523  |
|  …  |  …  |  …  |  …  |
## 使い方
プログラムを実行すると、加速度ファイルを選ぶ画面が出てくるので、処理する加速度ファイルをすべて選ぶ（複数選択可能）

…

保存先ディレクトリを選択する

指定したディレクトリにトリミング後の加速度ファイルが保存される
