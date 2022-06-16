# Markdown Tutorial


## 常用命令

| 功能       | Typora命令 | Markdown语法 |
| ---------- | ---------- | ------------ |
| 查看源代码 | Ctrl+/     |              |

## 标题

|        功能        | Typora命令 |  Markdown语法  |
| :----------------: | :--------: | :------------: |
|   设置文本为正文   |   Ctrl+0   |                |
| 设置文本为一级标题 |   Ctrl+1   |   `# title`    |
| 设置文本为六级标题 |   Ctrl+6   | `###### title` |

## 文本格式

|   功能   |   Typora命令   |    Markdown语法     |
| :------: | :------------: | :-----------------: |
|   加粗   |     Ctrl+B     |     `**text**`      |
|   倾斜   |     Ctrl+I     |      `*text*`       |
|  下划线  |     Ctrl+U     |    `<u>text</u>`    |
|   组合   |   Ctrl+B+I+U   | `**<u>*text*</u>**` |
|   上标   |                |      `^text^`       |
|   下标   |                |      `~text~`       |
|   高亮   |                |     `==text==`      |
| 取消格式 | 重复快捷键命令 |                     |

### example

- [ ] **这是加粗**
- [ ] *这是倾斜*
- [ ] <u>这是下划线</u>
- [ ] **<u>*这是加粗倾斜下划线*</u>**
- [ ] cm^3^
- [ ] H~2~O
- [ ] ==这是高亮==

## 罗列条目

|     功能     |      Typora命令      |         Markdown语法         |
| :----------: | :------------------: | :--------------------------: |
|   无序条目   |     Ctrl+Shift+]     | `- item`或`+ item`或`* item` |
|   有序条目   |     Ctrl+Shift+[     |    `1. item` , `2. item`     |
|   方块条目   | 菜单栏-段落-任务列表 |         `- [ ] item`         |
| 方块条目勾选 |       点击方块       |         `- [X] item`         |
|  升级或降级  | Ctrl+[ ,Ctrl+] , Tab |                              |

### example

- 水果
  - 苹果
  - 橘子
- 动物
  - 猫
  - 狗

神经网络

1. CNN
2. Transformer
3. GAN

- [x] 矩阵论
- [ ] 函数论

## 插入公式、代码

|   功能   |  Typora命令  |  Markdown语法   |
| :------: | :----------: | :-------------: |
| 行内公式 |              |   `$formula$`   |
| 行间公式 | Ctrl+Shift+M |  `$$formula$$`  |
| 行内代码 |              |  `` `code` ``   |
| 行间代码 | Ctrl+Shift+K | `````code`` ``` |

### example

行内公式：$\int_0^1 x^2dx=\frac{1}{3} $

行间公式：

$$\sum\limits_{ x\in \mathbb{N}}f(x)=f(0)+f(1)+\dots+f(n)+\dots $$

行内代码：`print('Hello world!')`

行间代码块：

```python
def fun(x,y):
    return x+y
```

## 插入表格、图片、链接

| 功能     | Typora命令   | Markdown语法                                                 |
| -------- | ------------ | ------------------------------------------------------------ |
| 插入表格 | Ctrl+T       |                                                              |
| 插入图片 | Ctrl+Shift+I | `![title](path)` 或`<img src="path" alt="title" style="zoom:80%;" />` |
| 插入链接 | Ctrl+K       | `[title](url)`或`[title](# 位置)`                            |

### example

<img src="https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fimg.3dmgame.com%2Fuploads%2Fimages%2Fnews%2F20210226%2F1614322923_858841.png&refer=http%3A%2F%2Fimg.3dmgame.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1657934789&t=7e80d506a9a82ee2f72cf886f647785a" alt="figure1：pokemon" style="zoom:80%;" />

[右击打开链接--进入我的github主页](https://github.com/hfut-zyw)

[右击打开链接--进入本文档的罗列条目处，在github中会失效](# 罗列条目)




