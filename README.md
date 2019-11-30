# HW 13: HTML, CSS, GitHub Pages

## 作業說明

這次作業要請大家**手刻**一個 HTML 檔 (`index.html`)，目的是希望大家能了解 HTML 的格式以及 CSS selector 的使用。
(不能透過 Rmd 或其它方式自動產生 HTML，也不能在 HTML 裡面引入其它 CSS library 或 framework)

#### 基本要求 (共 100 分)

1. (40 分，每個 HTML tag 各 10 分)   
**4 種**或 4 種以上的 HTML tag (e.g. `<div></div>`, `<img>`, `<p></p>`, `<a></a>`, ...)
    - 在 HTML 的內文中，必須包含 (請自行決定下列資訊要放入哪些 HTML tag):
        1. **系級**、**學號**、**姓名**
        1. 一段文字 (內容不重要，可以是 [Lorem ipsum](https://zh.wikipedia.org/wiki/Lorem_ipsum))
1. (60 分，每條 CSS 規則各 20 分)   
使用 CSS 裝飾的 HTML element
    - 請將 CSS 寫在 HTML 的 `<style></style>` 裡面。若直接寫在 HTML element 裡面或是使用外部檔案 (i.e. `<link></link>`)，不予計分
    - 只少用到 **3 個 CSS selector** (3 條規則)
    - CSS selector 中，需用到 HTML element 中的 `id` 及 `class` 屬性 (各一次)

    範例：
    ```html
    <style>
        h1 {
            font-weight: bold;
            text-align: center;
        }
        .larger {
            font-size: 1.4em;
        }
        #first {
            color: red;
        }
    </style>
    ```

#### 進階要求 (共 20 分)

在**同一個 repo** 中新增另一個 HTML 檔 (請命名為 `another.html`)。`another.html` 的內容要求同上 (除了「系級、學號、姓名」不用寫)，但不可直接複製 `index.html` 的內容。在你交上的兩份 HTML 檔中 (`index.html` 與 `another.html`)，使用者要能透過文件中的連結來回前往這兩個檔案 (i.e. `index.html` 內要有連結能前往 `another.html`，反之亦然)。


## 作業繳交

1. 請大家**自行**開一個**新的 GitHub repo**，將 `index.html`, `another.html` 與其它 dependencies (如果有的話) 上傳到此 repo。
1. 上傳完成後，請使用 [GitHub Pages](https://pages.github.com) 的功能，將這個 repo 變成網頁
1. 在 [Google 表單](#)中填寫 `index.html` 所在的網址


## 注意事項

- 請在**下週二 18:00** 之前將作業上傳
- 請確認將自己的**系級、學號、姓名**寫在作業檔案內



## 尋求幫助

若有問題，請至 [`rlads2019/hw13` 的 Issues](https://github.com/rlads2019/hw13/issues) 提出，提問前請**務必先閱讀[提問注意事項](https://rlads2019.github.io/lab/#qa-guide)**。

