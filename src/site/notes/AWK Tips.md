---
{"dg-publish":true,"permalink":"/awk-tips/","tags":["awk"]}
---

1. awk is a line-based processing tool
2. -F indicates separator of each column/field, which is space in default
3. $0 means the entire row, $x means the xth column
4. BEGIN{} 表示在处理数据之前的工作，可以用来打印表头
5. 可以用3里面的表示来对每一列做逻辑判断，~是包含，!是否定，&&是与
6. END{} 显示处理完数据之后的工作，比如打印总结信息
7. printf和C语言使用方法相似
