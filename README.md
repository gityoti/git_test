# markdown 语法学习[^1]


<a id='jump'>11</a>

|描述|效果|语法|
|:--|:--:|--:|
|单行代码|这是一段文字`ABC`描述|\`突出的文字\`|、
|斜体|*斜体*|`*斜体*`|
|斜体|_斜体_|`_斜体_`|
|加粗|**加粗**|`**加粗**`|
|加粗+斜体|***加粗+斜体***|`***加粗+斜体***`|
|加粗+斜体|**_加粗+斜体_**|`**_加粗+斜体_**`|
|删除线|~~删除线~~|`~~删除线~~`|

# 文字功能
## 显示h1~h6
# h1`# h1`
## h2`## h2`
### h3`### h3`
#### h4`#### h4`
##### h5`##### h5`
###### h6`##### h6`

# 复选框->进度跟踪
- [x] 选项一
- [ ] 选项二
- [ ]  [选项3]

# 公式 #是否会生效? ## `无效`
$ x = {-b \pm \sqrt{b^2-4ac} \over 2a}. $

# 分割线 ## `有效`
\*\*\*
***
\-\-\-
---
\* \* \*
* * *
---
# 列表系列
## 有序列表
1. A
    1. A1
    2. A2
2. B
3. C
## 无序列表
* A
* B
* C

# 代码高亮

*       到底支持多少种代码高亮呢?
[高亮参数列表](https://blog.csdn.net/u012102104/article/details/78950290 "abc")
``` javascript
    var x= 1;
    function a(a,b,c){
        return a+b+c;
    }
    a(1,2,3)
```

# 链接类型 #
*   必须独占一行才能生效? # 有没有什么办法让换行也能够生效?
*   `解决方法` 在 `空格 []()` 必须保持一个空格,否则解析会出现无法转换。
![图片的描述信息](https://upload-images.jianshu.io/upload_images/6860761-fd2f51090a890873.jpg "鼠标移过显示标题")
    图片链接语法`![描述](图片url "title")`,

    超链接语法`[显示的文本](链接url "title")` , 同时支持做锚点跳转
这是一个超链接 [W3C教程]( https://www.w3cschool.cn/lme/6jdv1srr.html )
    `<a id='jump'>11</a>`用于锚的跳转
    `<a id="user-content-jump">11</a>` 页面中会生成
    `user-content-id` 作为跳转的锚点 ``
    [跳转测试](#user-content-jump)
# 表格的扩展 # 为什么会无效呢? # 增加标题

|Tables |Are|Cool|
|-------------|:-------------:|-----:|
|col 3 is|right-aligned|$1600 |
|col 2 is|centered|$12|
|zebra stripes|are neat|$1 |


| Tables        | Are           | Cool  |
| ------------- |:-------------:|-----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

[^1]:这是一个脚注,这个语法时候可以生效?!鼠标经过的时候左下角的链接信息会出现提示?