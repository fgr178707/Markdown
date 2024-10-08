# 标题
> \# 一级标题   
> \## 二级标题   
> \### 三级标题   
> \#### 四级标题   
> \##### 五级标题   
> \###### 六级标题    

效果：
> # 一级标题   
> ## 二级标题   
> ### 三级标题   
> #### 四级标题   
> ##### 五级标题   
> ###### 六级标题

# 段落
段落的前后要有空行，所谓的空行是指没有文字内容。若想在段内强制换行的方式是使用**两个以上**空格加上回车（引用中换行省略回车）。

# 区块引用
在段落的每行或者只在第一行使用符号`>`,还可使用多个嵌套引用，如：
> \> 区块引用  
> \>> 嵌套引用  

效果：
> 区块引用  
>> 嵌套引用

# 代码区块
代码区块的建立是在每行加上4个空格或者一个制表符（如同写代码一样）。如    
普通段落：

void main()    
{    
    printf("Hello, Markdown.");    
}    

代码区块：

    void main()
    {
      printf("Hello, Markdown.");
    }

**注意**:需要和普通段落之间存在空行。

# 强调
在强调内容两侧分别加上`*`或者`_`，如：
> \*斜体\*，\_斜体\_    
> \*\*粗体\*\*，\_\_粗体\_\_

效果：
> *斜体*，_斜体_    
> **粗体**，__粗体__

# 列表
使用`·`、`+`、或`-`标记无序列表，如：
> \-（+\*） 第一项
> \-（+\*） 第二项
> \- （+\*）第三项

**注意**：标记后面最少有一个_空格_或_制表符_。若不在引用区块中，必须和前方段落之间存在空行。

效果：
> + 第一项
> + 第二项
> + 第三项

## 2.0 列表
有序列表的标记方式是将上述的符号换成数字,并辅以`.`，如：
> 1 . 第一项   
> 2 . 第二项    
> 3 . 第三项    

效果：
> 1. 第一项
> 2. 第二项
> 3. 第三项

# 分割线
分割线最常使用就是三个或以上`*`，还可以使用`-`和`_`。

> \****
>
> 1
>
> \****

效果：

>****
>1
>****


# 链接

链接可以由两种形式生成：**行内式**和**参考式**。    
**行内式**：
> \[fgr178707主页\]\(https://github.com/fgr178707\)。

效果：
> [fgr178707主页](https://github.com/fgr178707)。

**参考式**：
> \[fgr178707主页1\]\[1\]    
> \[fgr178707主页2\]\[2\]    
> \[1\]:https://github.com/fgr178707
> \[2\]:https://github.com/fgr178707 

效果：
> [fgr178707主页1][1]   
> [fgr178707主页2][2]

[1]: https://github.com/fgr178707
[2]: https://github.com/fgr178707

# 图片(相对路径)
添加图片的形式和链接相似，只需在链接的基础上前方加一个`！`。
> \[图片\]\(image/1.jpg\)。

效果：

> ![图片](image/1.jpg)。


## 图片(链接)

> \[图片\]\(https://raw.githubusercontent.com/fgr178707/fgr178707/main/image/1.jpg \)。

效果：

> ![图片](https://raw.githubusercontent.com/fgr178707/fgr178707/main/image/1.jpg)。

# 反斜杠`\`
相当于**清除效果**作用。使符号成为普通符号。

# 符号``
起到标记作用。如：
>\`ctrl+a\`

效果：
>`ctrl+a`    


# 文档：

用`|`表示表格纵向边界，表头和表内容用`-`隔开，并可用`:`进行对齐设置，两边都有`:`则表示居中，若不加`:`则默认左对齐。

|代码库                              |链接                                |
|:------------------------------------:|------------------------------------|
|fgr178707|[https://github.com/fgr178707](https://github.com/fgr178707)|
|fgr178707|[https://github.com/fgr178707](https://github.com/fgr178707)|

```

> [!NOTE]  
> Highlights information that users should take into account, even when skimming.

> [!TIP]
> Optional information to help a user be more successful.

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.

> [!CAUTION]
> Negative potential consequences of an action.
```

> [!NOTE]
> 
> [!注意]
> 
> 突出显示用户应考虑的信息，即使在浏览时也是如此。

> [!TIP]
> 
> [!提示]
> 
> 帮助用户取得更大成功的可选信息。

> [!IMPORTANT]
> 
> [!重要]
> 
> 用户成功所需的重要信息。

> [!WARNING]
> 
> [!警告]
> 
> 由于存在潜在风险，需要用户立即关注的关键内容。

> [!CAUTION]
> 
> [!谨慎]
> 
> 操作的潜在负面后果。

关于其它扩展语法可参见具体工具的使用说明。
