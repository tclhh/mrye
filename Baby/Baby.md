## Baby 

### 0x00 字符串搜索

因为是 Bugku 第一题 , 直接使用 `IDA` 字符串搜索功能 ( `shift + F12` )：

![search](image/search.jpg)

双击到目标位置后 , 继续双击交叉引用：

![xref](image/xref.jpg)

可以看到上面的汇编把 `flag` 藏在汇编代码中 , 在 `main` 函数中并不会打印。直接 `IDA` 选中值按 `r` 即可得到 `flag`：

![end](image/end.jpg)