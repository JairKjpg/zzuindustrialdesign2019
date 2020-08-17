---
layout:     post   				    # 使用的布局（不需要改）
title:     typora及markdown使用入门				# 标题 
subtitle:   使用markdown高效排版  #副标题
date:       2020-08-16 				# 时间
author:     JairK 						# 作者
header-img: img/post-bg-rwd.jpg 	#这篇文章标题背景图片
catalog: true 						# 是否归档
tags:								#标签

    - typora
    - 高效率
    - markdown
    - 版式設計

---

# typora及markdown使用入门

## typora的介绍以及使用

### markdown标题

1. 使用#标记

   ```markdown
   # 一级标题
   ## 二级标题
   ### 三级标题
   #### 四级标题
   ##### 五级标题
   ###### 六级标题
   
   井号和标题中间有空格
   ```

### markdown段落格式

1. #### 段落换行

   1. 使用两个以上的空格+回车
   2. 使用空行来换行

2. #### 字体

   ```markdown
   *斜体文本*
   _斜体文本_
   **粗体文本**
   __粗体文本__
   ***粗斜体文本***
   ___粗斜体文本___
   ```

### markdown列表

1. #### 无序列表 

   ```markdown
   * 第一项
   * 第二项
   * 第三项
   
   + 第一项
   + 第二项
   + 第三项
   
   
   - 第一项
   - 第二项
   - 第三项
   ```

   <img src="https://www.runoob.com/wp-content/uploads/2019/03/89446A8E-6D83-4666-AACC-980145D5F070.jpg" alt="img" style="zoom: 50%;" />

   

2. #### 有序列表

   ```markdown
   1. 第一项
   2. 第二项
   3. 第三项
   
   数字加“.”
   ```

   <img src="https://www.runoob.com/wp-content/uploads/2019/03/560384BB-2B00-41D5-ACF2-18972F7F2775.jpg" alt="img" style="zoom: 80%;" />

3. #### 列表嵌套

   ```markdown
   1. 第一项：
       - 第一项嵌套的第一个元素
       - 第一项嵌套的第二个元素
   2. 第二项：
       - 第二项嵌套的第一个元素
       - 第二项嵌套的第二个元素
       
   注意：在子列表前添加四个空格
   ```

   <img src="https://www.runoob.com/wp-content/uploads/2019/03/8ED795DA-F124-4E70-BA71-57CD9CF958A4.jpg" alt="img" style="zoom:150%;" />

### markdown区块

1. #### 区块、区块的嵌套

   ```markdown
   > 区块引用
   > 菜鸟教程
   > 学的不仅是技术更是梦想
   
   > 最外层
   > > 第一层嵌套
   > > > 第二层嵌套
   ```

   <img src="https://www.runoob.com/wp-content/uploads/2019/03/AA0A4A6A-33A7-48C7-971F-73FFC8FE85B0.jpg" alt="img" style="zoom: 60%;" />

2. #### 区块中使用列表

   ```markdown
   > 区块中使用列表
   > 1. 第一项
   > 2. 第二项
   > + 第一项
   > + 第二项
   > + 第三项
   ```

   <img src="https://www.runoob.com/wp-content/uploads/2019/03/E3BF6399-6483-4C7A-8502-AE75E8D66C96.jpg" alt="img" style="zoom:110%;" />

3. ####　列表中使用区块

   ```markdown
   * 第一项
       > 菜鸟教程
       > 学的不仅是技术更是梦想
   * 第二项
   ```

   <img src="https://www.runoob.com/wp-content/uploads/2019/03/1B894FB4-53AC-4E2D-BA30-F4AE4DFA8B97.jpg" alt="img" style="zoom:80%;" />

### markdown代码

1. #### 代码区块

   ```markdown
   ​```javascript
   $(document).ready(function () {
       alert('RUNOOB');
   });
   ​```
   ```
   
2. #### 代碼段

   ```markdown
   `test`
   ```

### markdown链接

1. #### 普通链接

   ```markdown
   这是一个链接 [菜鸟教程](https://www.runoob.com)
   ```

   ​		这是一个链接[菜鸟教程](https://www.runoob.com)

2. #### 直接使用链接地址

   ```markdown
   <https://www.runoob.com>
   ```

   ​		<https://www.runoob.com>

3. #### 高级链接

   ```markdown
   这个链接用 1 作为网址变量 [Google][1]
   这个链接用 runoob 作为网址变量 [Runoob][runoob]
   然后在文档的结尾为变量赋值（网址）
   
     [1]: http://www.google.com/
     [runoob]: http://www.runoob.com/
   ```

   ​		这个链接用 1 作为网址变量 [Google][1]
   ​		这个链接用 runoob 作为网址变量 [Runoob][runoob]
   ​		然后在文档的结尾为变量赋值（网址）	

   [1]: http://www.google.com/
   [runoob]: http://www.runoob.com/

### markdown图片

1. #### 直接引用

   ```markdown
   ![alt 属性文本](图片地址)
   
   ![alt 属性文本](图片地址 "可选标题")
   
   开头一个感叹号 !
   接着一个方括号，里面放上图片的替代文字
   接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的 'title' 属性的文字。
   
   ![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)
   
   ![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "RUNOOB")
   ```

   ![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)

   ![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "RUNOOB")

2. #### 使用变量

   ```
   这个链接用 1 作为网址变量 [RUNOOB][1].
   然后在文档的结尾为变量赋值（网址）
   
   [1]: http://static.runoob.com/images/runoob-logo.png
   ```

   ​		这个链接用 1 作为网址变量 [RUNOOB][1].
   ​		然后在文档的结尾为变量赋值（网址）

   [1]: http://static.runoob.com/images/runoob-logo.png

### markdown表格

1. #### 格式

   ```
   |  表头   | 表头  |
   |  ----  | ----  |
   | 单元格  | 单元格 |
   | 单元格  | 单元格 |
   ```

   | 表头   | 表头   |
   | ------ | :----- |
   | 单元格 | 单元格 |
   | 单元格 | 单元格 |

2. #### 对齐方式

   ```
   - **-:** 设置内容和标题栏居右对齐。
   - **:-** 设置内容和标题栏居左对齐。
   - **:-:** 设置内容和标题栏居中对齐。
   
   | 左对齐 | 右对齐 | 居中对齐 |
   | :-----| ----: | :----: |
   | 单元格 | 单元格 | 单元格 |
   | 单元格 | 单元格 | 单元格 |
   ```

   | 左对齐 | 右对齐 | 居中对齐 |
   | :----- | -----: | :------: |
   | 单元格 | 单元格 |  单元格  |
   | 单元格 | 单元格 |  单元格  |

### markdown与latex

1. $$+回车
$$
\frac{3}{4x+3}
$$

2. $$\int_0^{2\pi} \pi d\theta$$
3. $\int_0^{2\pi} \pi d\theta$
4. 不知道这个$$\int_0^{2\pi} \pi d\theta$$（double dollors）是文段的，还是$\int_0^{2\pi} \pi d\theta$（single dollors）是文段。这个在typora均为文段内。不过在GitHub page上的表现会有出入。

### markdown与todo-list

- [ ] 项目1
- [x] 项目1

### markdown高级技巧

#### 技巧1 支持HTML元素

支持的 HTML 元素有：`<kbd> <b> <i> <em> <sup> <sub> <br>`等

```
使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑
```

#### 		使用 <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> 重启电脑

#### 技巧2 转义

Markdown 使用反斜杠转义特殊字符

```
**文本加粗** 
\*\* 正常显示星号 \*\*
```

**文本加粗** 
\*\* 正常显示星号 \*\*

#### 技巧3 公式

$$+回車,使用内置的latex解釋器 。

#### 技巧4 流程图、时序图(顺序图)、甘特图















