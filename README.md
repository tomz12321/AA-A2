# AA-A2
* 如何 complie:

到 AA-A2 folder底下

執行 javac -cp .:samplePlayer.jar BattleshipMain.java

* 如何 execute:

到 AA-A2 folder底下

執行 java BattleshipMain -l newlog.txt config.txt loc1.txt loc2.txt random random

===

Random的寫完了。

Greedy 的完成了一半，一個暫時可以跑的，但邏輯不對。

Probabilistic 的只定下了Hunting mode 的規則，但他的Targeting mode 應該跟Greedy會是一樣的。

===

他指令會把結果印在 newlog.txt 這個文檔裡面，你就可以檢查他run出來的結果是否是你想要的。

===

Task C 會比較難，大概是用attached 的那個圖

從 [5,5] 開始 順時針螺旋向外試射 [5,5] -> [5,6] -> [6,6] -> [6,5]

先做到那樣，可以執行以後 (出一版code)

再實作另一個方法，就是把 probability = 8 的 放在一個 list 裡面

把 probability = 7 的 放在一個 list 裡面

把 probability = 6 的 放在一個 list 裡面

把 probability = 5 的 放在一個 list 裡面

把 probability = 4 的 放在一個 list 裡面

亂數 pop 出來

以上大概是 ** Hunting mode ** 的邏輯

至於 **Targeting mode ** , 等我把 GreedyGuessPlayer 實作出來以後，

再應用過去吧~ 

TaskB 跟 TaskC 在Targeting mode應該是一樣的。
