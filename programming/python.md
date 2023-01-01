`if` `else if` `else` ってあるじゃん。　　
Pythonは `else if` => `elif`になるじゃん。　　
jsとかcでは
```js
if (true) printf("Hello, World!");
```
って`{}`を省略できるんだけど、ここで一つ  
if文,else文はあっても**else if文は存在しない**んだよね
つまり
```js
if(条件1) {
    // 処理1
} else if(条件2) {
    // 処理2
} else {
    // 処理3
}
```
と
```js
if (条件1) {
    // 処理1
} else {
    if (条件2) {
        // 処理2
    } else {
        // 処理3
    }
}
```
は内部的には**全く同じ処理をしてる**ということ  
ただしPythonには`elif文`があるから処理が1つ多いと  

薄々思ってたんだけど、[ncss](https://github.com/SatooRu65536/ncss)
を作る上で合ってたと分かった  
なんか面白くね
