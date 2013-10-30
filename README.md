簡易計算機
=========

供 JavaScript 教學用

要完成項目
--------

* 基本的加減乘除。
* 數字歸零。
* 小數點與正負號。
* 顯示位數限制，超過顯示位數時要顯示 Error 。

進階項目
-------

* MC / M+ / M- / MR 等記憶功能。

實作規範
-------

### Screen

1. 最大位數，不含正負號，應可以顯示 12 位數數字。
2. 計算結果若是超過 12 位數，就顯示 "ERROR" 。
3. 顯示正負號。
4. 顯示運算子。
5. 顯示 Memory 符號。

### 數字鍵

1. 完成按下數字鍵時，在 Screen 上顯示該數字。
2. 再次按下數字鍵時，要在原數字的右邊加上新數字。
3. 當 Screen 顯示為 "0" 時，按下數字鍵要取代 "0" 。

### 小數點鍵

1. 一個數字串只能有一個小數點。
2. 當按下小數點鍵時，不會立刻顯示小數點，而是在下一次按數字鍵時，顯示在新增數字的左邊。

### 歸零鍵

1. 清除所有計算結果，並將 Screen 顯示為 "0" 。
2. 清除運算子顯示。
3. 不清除 Memory 。

### 正負號鍵

1. 當 Screen 顯示為 "0" 時，正負號鍵無作用。
2. 如果目前顯示數字沒有負號，則在其左方加上負號；反之則移除負號。

### 運算鍵

1. 按下加減乘除鍵時，要暫記目前 Screen 上的「數值」，並保留 Screen 的「顯示數字」。
2. 再次按下數字鍵時，要清空 Screen ，並顯示新的數字。

### 等於鍵

1. 當 Screen 沒有顯示運算子時，等於鍵無作用。
2. 當已經有運算子時，則將暫記的數值與目前 Screen 上所呈現的數值做運算，並將結果顯示在 Screen 上。
3. 當運算結果超出 12 位數時，則在 Screen 顯示 "ERROR" 。

