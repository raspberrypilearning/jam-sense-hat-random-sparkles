## ランダムモジュールの使用

これまでは自分の乱数を選んだのですが、代わりにコンピュータに選択させることができます。

1. 別のものを追加`インポート`あなたのプログラムの一番上にある行|下にある`import SenseHat`：
    
    ```python
ランダムインポートrandintから
```

2. 今すぐあなたを変更してください`x =` `y =`自動的にランダムな位置を選択する行：
    
    ```python
x = randint（0,7）y = randint（0,7）
```

3. プログラムをもう一度実行すると、別のランダムなピクセルがディスプレイに表示されます。 あなたが以前に選んだのと同じ色になります。

4. 色の値の行を次のように変更します。
    
    ```python
r = randint（0,255）g = randint（0,255）b = randint（0,255）
```

これでプログラムは自動的にランダムな色を選択します。

5. 再度実行すると、ランダムな色のランダムな場所に別のピクセルが表示されます。

6. 数回それを実行すると、より多くのグリッドがランダムなピクセルでいっぱいになるはずです。