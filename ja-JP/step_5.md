## ループを追加する

処理を継続して実行させるために、ループを追加することができます。プログラムを何回も手動で実行しなくてもよいのです。

1. まず、プログラムの先頭に`import`文を追加します。：
    
    ```python
    from time import sleep
    ```

    これを使用して、ピクセル表示の間でプログラムをスリープします。

2. `while True:`をコードに追加します。ピクセルの位置指定、色指定、`set_pixel`と`sleep`のすべてがwhileループ内にあります：
    
    ```python
    while True:
        x = randint(0, 7)
        y = randint(0, 7)
        r = randint(0, 255)
        g = randint(0, 255)
        b = randint(0, 255)
        sense.set_pixel(x, y, r, g, b)
        sleep(0.1)
    ```

3. コードを実行すると、ピクセルがランダムに表示され続けます！

4. スリープ時間をさらに短くするように変更してみてください。
