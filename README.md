#Lab颜色转换为RGB#
## 概要 ##
  此程序为了测试挑选合适的转换矩阵而写
  
## 结果 ##
测试lab值(57.23,-24.31,-27.26)，结果输出：
```
S:/go_workspace/l2r/l2r.exe  [S:/go_workspace/l2r]
[i]main called.
76 151 183
-9 152 185
82 146 203
86 150 205
34 151 183
-41 150 187
-15 153 212
81 149 204
79 148 207
76 152 205
81 150 174
-29 151 184
113 146 203
-153 152 184
-76 151 184
86 149 206
61 152 208
-125 153 212
-50 152 208
-64 151 204
76 146 206
-143 152 211
-286 153 210
-195 152 210
成功: 进程退出代码 0.

```


标准值：22，151，184
输出结果中最接近的值：34 151 183；差值为12 0 1；该转换矩阵为：
```
2.7454669 -1.1358136 -0.4350269
-0.9692660  1.8760108  0.0415560
 0.0112723 -0.1139754  1.0132541
```
## 总结##
偏差值，算法上或许还有未注意到的可改进之处，。
## 参考 ##
[维基百科上的LAB to XYZ公式](https://zh.wikipedia.org/wiki/Lab%E8%89%B2%E5%BD%A9%E7%A9%BA%E9%97%B4)
[XYZ to RGB的转换矩阵](http://www.brucelindbloom.com/index.html?Eqn_RGB_XYZ_Matrix.html)
[知乎上的gamma修正](https://zhuanlan.zhihu.com/p/24281841)
[一个颜色转换网站](https://www.colortell.com/labto)
## 参见 ##
[博客文章](http://czz2x.club/build/index.php/archives/171/)