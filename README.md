# CCF
<del>只是玩玩</del>
## 题目1 相邻数对
- 时间限制: 1 秒
- 空间限制: 256 MB
- 问题描述
</br>给定n个不同的整数，问这些数中有多少对整数，它们的值正好相差1。
- 输入格式
</br>输入的第一行包含一个整数n，表示给定整数的个数。
</br>第二行包含所给定的n个整数。
- 输出格式
</br>输出一个整数，表示值正好相差1的数对的个数。
- 输入样例
</br>6
</br>10 2 6 3 7 8
- 输出样例
</br>3
- 样例说明
</br>值正好相差 1 的数对包括(2, 3), (6, 7), (7, 8)。
</br>评测用例规模与约定1<=n<=1000，给定的整数为不超过 10000 的非负整数。

## 题目2 画图
- 时间限制: 1 秒
- 空间限制: 256 MB
- 问题描述
</br>在一个定义了直角坐标系的纸上，画一个(x1,y1)到(x2,y2)的矩形指将横坐标范围从x1到x2，纵坐标范围从y1到y2之间的区域涂上颜色。
</br>下图给出了一个画了两个矩形的例子。第一个矩形是(1,1) 到(4, 4)，用绿色和紫色表示。第二个矩形是(2, 3)到(6, 5)，用蓝色和紫色表示。图中，一共有15个单位的面积被涂上颜色，其中紫色部分被涂了两次，但在计算面积时只计算一次。在实际的涂色过程中，所有的矩形都涂成统一的颜色，图中显示不同颜色仅为说明方便。
![draw](/draw/draw.png)
</br>给出所有要画的矩形，请问总共有多少个单位的面积被涂上颜色。
- 输入格式
</br>输入的第一行包含一个整数n，表示要画的矩形的个数。
</br>接下来n行，每行4个非负整数，分别表示要画的矩形的左下角的横坐标与纵坐标，以及右上角的横坐标与纵坐标。
- 输出格式
</br>输出一个整数，表示有多少个单位的面积被涂上颜色。
- 输入样例
</br>2
</br>1 1 4 4
</br>2 3 6 5
- 输出样例
</br>15
- 评测用例规模与约定
</br>1<=n<=100，0<=横坐标、纵坐标<=100。

## 题目3 字符串匹配
- 时间限制: 1 秒
- 空间限制: 256 MB
- 问题描述
</br>给出一个字符串和多行文字，在这些文字中找到字符串出现的那些行。你的程序还需支持大小写敏感选项：当选项打开时，表示同一个字母的大写和小写看作不同的字符；当选项关闭时，表示同一个字母的大写和小写看作相同的字符。
- 输入格式
</br>输入的第一行包含一个字符串S，由大小写英文字母组成。
</br>第二行包含一个数字，表示大小写敏感的选项，当数字为0时表示大小写不敏感，当数字为1时表示大小写敏感。
</br>第三行包含一个整数n，表示给出的文字的行数。
</br>接下来n行，每行包含一个字符串，字符串由大小写英文字母组成，不含空格和其他字符。
- 输出格式
</br>输出多行，每行包含一个字符串，按出现的顺序依次给出那些包含了字符串S的行。
- 输入样例
</br>Hello
</br>1
</br>5
</br>HelloWorld
</br>HiHiHelloHiHi
</br>GrepIsAGreatTool
</br>HELLO
</br>HELLOisNOTHello
- 输出样例
</br>HelloWorld
</br>HiHiHelloHiHi
</br>HELLOisNOTHello
- 样例说明
</br>在上面的样例中，第四个字符串虽然也是 Hello，但是大小写不正确。如果将输入的第二行改为 0，则第四个字符串应该输出。
- 评测用例规模与约定
</br>1<=n<=100，每个字符串的长度不超过 100。
