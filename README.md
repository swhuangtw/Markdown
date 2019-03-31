# Markdown：Syntax

### 標題

Atx 形式則是在行首插入 1 到 6 個 # ，對應到標題 1 到 6 階，例如
Markdown script

    # 這是h1標題 <h1> tag            
    ## 這是h2標題 <h2> tag

Markdown result
# 這是h1標題          
## 這是h2標題 

### 強調

Markdown script

    *這是斜體*
    _這也是斜體_
    **這是粗體**
    __這也是粗體__
    _兩個結合一起 **粗體** 斜體+粗體_

Markdown result

*這是斜體*
_這也是斜體_
**這是粗體**
__這也是粗體__
_兩個結合一起 **粗體** 斜體+粗體_

### 清單

  * 無序清單

Markdown script

    * 項目1
    * 項目2
        * 項目2a
        * 項目2b

Markdown result

* 項目1
* 項目2
  * 項目2a
  * 項目2b

### 清單
  * 有序清單

Markdown script

    1. Item 1
    1. Item 2
        1. Item 3a
        1. Item 3b

Markdown result

1. 項目1
2. 項目2
    1. 項目2-1
    2. 項目2-2

###圖片

Markdown script

    ![GitHub Logo](/images/logo.png)
    ![Alt Text](url)

Markdown result

![GitHub Logo](/images/logo.png)
![Alt Text，連結失效時顯示](https://github.com/swhuangtw/Markdown/blob/master/M.png?raw=true)

###連結

Markdown script

    http://github.com - automatic!
    [GitHub](http://github.com)

Markdown result

http://github.com - automatic!
[GitHub](http://github.com)

###引言

Markdown script

    > 示範文字示範文字示範文字示範文字示範文字示範
    > 示範文字示範文字示範文字示範文字示範文字示範

Markdown result

> 示範文字示範文字示範文字示範文字示範文字示範文字
> 示範文字示範文字示範文字示範文字示範文字示範文字

###行內標記灰底

Markdown script

    示範文字示範文字 `示範文字` 示範文字示範文字示範


Markdown result

示範文字示範文字 `示範文字` 示範文字示範文字示範

###任務清單

Markdown script

    - [x] @mentions, #refs, [links](), **formatting**, and <del>tags</  del> supported
    - [x] list syntax required (any unordered or ordered list supported)
    - [x] this is a complete item
    - [ ] this is an incomplete item    

Markdown result

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> 支援提及、參考、連結、粗體、刪除線
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

###表格

Markdown script

    First Header | Second Header
    ------------ | -------------
    Content from cell 1 | Content from cell 2
    Content in the first column | Content in the second column

Markdown result

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
