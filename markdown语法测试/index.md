# Markdown语法测试


这篇文章提供了一些可用的 Markdown 语法示例以及一些效果展示。

<!--more-->

## 1 标题语法

```markdown
## 二级标题

### 三级标题

#### 四级标题

#### 四级标题

##### 五级标题
```

## 2 引用

语法

```Markdown
> 引用的内容
```

效果如下

> 引用测试

## 3 强调文本

### 粗体

语法

{{<highlight Markdown>}}
**粗体**
{{</highlight>}}

效果

**粗体**测试

### 斜体

语法

{{<highlight Markdown>}}
***斜体***
{{</highlight>}}

效果

***斜体***测试

### 删除线

语法

{{<highlight Markdown>}}
~~删除~~
{{</highlight>}}

效果

~~删除线~~测试

{{<admonition tip "注意">}}
在使用字体强调语法时，要注意区分全角半角标点符号，使用半角标点才有效果。
{{</admonition>}}

## 4 代码块

语法

```Markdown
`行内代码`
```

{{<highlight markdown>}}
```html
<p>围栏代码块</p>
```
{{</highlight>}}

效果

`行内代码测试`


```html
<p>围栏代码块测试</p>
```

## 5 信息提示

效果

{{<admonition tip "tip测试">}}
提示信息的内容		
{{</admonition>}}

{{<admonition note "note测试">}}
提示信息的内容		
{{</admonition>}}

{{<admonition abstract "abstract测试">}}
提示信息的内容		
{{</admonition>}}

{{<admonition info "info 测试">}}
提示信息的内容		
{{</admonition>}}

{{<admonition success "success测试">}}
提示信息的内容		
{{</admonition>}}

{{<admonition question "question测试">}}
提示信息的内容		
{{</admonition>}}

{{<admonition warning "warning测试">}}
提示信息的内容		
{{</admonition>}}

{{<admonition failure "failure 测试">}}
提示信息的内容		
{{</admonition>}}

{{<admonition danger "danger测试">}}
提示信息的内容		
{{</admonition>}}

{{<admonition bug "bug 测试">}}
提示信息的内容		
{{</admonition>}}

{{<admonition example "example测试">}}
提示信息的内容		
{{</admonition>}}

{{<admonition quote "quote测试">}}
提示信息的内容		
{{</admonition>}}

{{<admonition fas "fas测试">}}
提示信息的内容		
{{</admonition>}}

## 6 分割线

语法

{{<highlight Markdown>}}
--- 三个减号
*** 三个星号
___ 三个下划线
{{</highlight>}}

效果

---
***
___

## 7 列表

### 无序列表

语法

{{<highlight Markdown>}}
- 列表项
+ 列表项
* 列表项
{{</highlight>}}

效果

- 列表项
+ 列表项
* 列表项

### 有序列表

语法

{{<highlight Markdown>}}
1. 列表项
2. 列表项
3. 列表项
{{</highlight>}}

效果

1. 列表项
2. 列表项
3. 列表项

## 8 表格

语法

{{<highlight Markdown>}}
| a   |  v  |   b |
| :-- | :-: | --: |
| a   |  b  |   c |
| a   |  b  |   c |
| a   |  b  |   c |
| a   |  b  |   c |
{{</highlight>}}

效果

| a   |  v  |   b |
| :-- | :-: | --: |
| a   |  b  |   c |
| a   |  b  |   c |
| a   |  b  |   c |
| a   |  b  |   c |

---

> 作者: 海拉鲁大魔王  
> URL: https://io-oss.gitee.io/markdown%E8%AF%AD%E6%B3%95%E6%B5%8B%E8%AF%95/  

