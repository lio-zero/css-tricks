# CSS Tricks

本仓库的 CSS 技巧是从我另一个仓库 [blog](https://github.com/lio-zero/blog) 的[常用的一些 CSS 技巧一](https://github.com/lio-zero/blog/blob/master/CSS/%E5%B8%B8%E7%94%A8%E7%9A%84%E4%B8%80%E4%BA%9B%20CSS%20%E6%8A%80%E5%B7%A7%E4%B8%80.md)和[常用的一些 CSS 技巧二 — 选择器（伪类与伪元素）](https://github.com/lio-zero/blog/blob/master/CSS/%E5%B8%B8%E7%94%A8%E7%9A%84%E4%B8%80%E4%BA%9B%20CSS%20%E6%8A%80%E5%B7%A7%E4%BA%8C%20%E2%80%94%20%E9%80%89%E6%8B%A9%E5%99%A8%EF%BC%88%E4%BC%AA%E7%B1%BB%E4%B8%8E%E4%BC%AA%E5%85%83%E7%B4%A0%EF%BC%89.md)整理过来的，目的是为了方便后续的阅读和添加新内容。

- [CSS3 中的 counter](#css3-中的-counter)
- [使用 CSS white-space 修复文本重叠](#使用-css-white-space-修复文本重叠)
- [Flexbox 居中元素](#flexbox-居中元素)
- [Gird 居中元素](#gird-居中元素)
- [在 CSS 中更改光标颜色](#在-css-中更改光标颜色)
- [使非密码输入使用符号替代](#使非密码输入使用符号替代)
- [CSS user-select 禁用文本选择](#css-user-select-禁用文本选择)
- [自定义 CSS 选择样式](#自定义-css-选择样式)
- [CSS 变量](#css-变量)
  - [全局范围内定义](#全局范围内定义)
  - [局部范围内定义](#局部范围内定义)
- [text-rendering](#text-rendering)
- [类似原生的 IOS 滚动](#类似原生的-ios-滚动)
- [蚀刻文字](#蚀刻文字)
- [实现文本溢出省略效果](#实现文本溢出省略效果)
- [渐变文字](#渐变文字)
- [文本描边效果](#文本描边效果)
- [系统字体堆栈](#系统字体堆栈)
- [叠纸效果](#叠纸效果)
- [隐藏数字输入微调器](#隐藏数字输入微调器)
- [发光的蓝色输入亮点](#发光的蓝色输入亮点)
- [使用 fieldset 禁用表单](#使用-fieldset-禁用表单)
- [非表单 fieldset 外观](#非表单-fieldset-外观)
- [将 WebKit 的文件上传输入按钮强制向右移动](#将-webkit-的文件上传输入按钮强制向右移动)
- [简单而漂亮的 Blockquote 样式](#简单而漂亮的-blockquote-样式)
- [使用纯 CSS 创建三角形](#使用纯-css-创建三角形)
- [制作一个列宽相等的表格](#制作一个列宽相等的表格)
- [重置所有样式](#重置所有样式)
- [在 HTML 中的字符串中保留空格和换行符](#在-html-中的字符串中保留空格和换行符)
- [使用 hr 作为分隔符](#使用-hr-作为分隔符)
- [从图像中剔除白色背景](#从图像中剔除白色背景)
- [使用指针事件来控制鼠标事件](#使用指针事件来控制鼠标事件)
- [指示缺少 alt 属性的 img 元素](#指示缺少-alt-属性的-img-元素)
- [快速输入颜色变量](#快速输入颜色变量)
- [使用 currentColor 关键字重用当前颜色](#使用-currentcolor-关键字重用当前颜色)
- [给“默认”链接定义样式](#给默认链接定义样式)
- [用 rem 来调整全局大小；用 em 来调整局部大小](#用-rem-来调整全局大小用-em-来调整局部大小)
- [为 body 元素添加行高](#为-body-元素添加行高)
- [转义 CSS 类名](#转义-css-类名)
- [使用 SVG 图标](#使用-svg-图标)
- [在打印模式下显示链接](#在打印模式下显示链接)
- [隐藏 Microsoft Edge 的密码显示按钮](#隐藏-microsoft-edge-的密码显示按钮)
- [防止锚链接消失在粘性标题后面](#防止锚链接消失在粘性标题后面)
- [创建自定义表情符号光标](#创建自定义表情符号光标)
- [CSS 重置盒模型](#css-重置盒模型)
- [清除浮动](#清除浮动)
- [:focus 状态样式](#focus-状态样式)
- [:focus-within](#focus-within)
- [实现分割线](#实现分割线)
- [为破损的图片定义样式](#为破损的图片定义样式)
- [CSS `:empty`](#css-empty)
  - [显示空列表的占位符](#显示空列表的占位符)
  - [设置空链接的内容](#设置空链接的内容)
- [CSS :only-child](#css-only-child)
- [CSS :not()](#css-not)
- [逗号分隔列表](#逗号分隔列表)
- [移除最后一个导航项的边框](#移除最后一个导航项的边框)
- [隐藏没有静音、自动播放的影片](#隐藏没有静音自动播放的影片)
- [单独的项目列表](#单独的项目列表)
- [CSS 设置 ::placeholder 文本的样式](#css-设置-placeholder-文本的样式)
- [CSS :placeholder-shown](#css-placeholder-shown)
- [自定义列表](#自定义列表)
- [自定义文字选择](#自定义文字选择)
- [自定义 WebKit 滚动条](#自定义-webkit-滚动条)
- [首字大写](#首字大写)
- [只显示第一个字母](#只显示第一个字母)
- [使用 `:nth-child()` 创建具有交替背景颜色的列表](#使用-nth-child-创建具有交替背景颜色的列表)
- [使用负 `:nth-child` 和 `:nth-last-child` 来选择元素](#使用负-nth-child-和-nth-last-child-来选择元素)
- [:hover](#hover)
- [::marker](#marker)
- [使用 :invalid 和 :valid 校验表单元素](#使用-invalid-和-valid-校验表单元素)
- [使用 :checked 和 `:default` 赋予元素状态](#使用-checked-和-default-赋予元素状态)
- [将前导零附加到有序列表项](#将前导零附加到有序列表项)
- [使用特殊字符设置列表项的样式](#使用特殊字符设置列表项的样式)
- [使用 “形似猫头鹰” 选择器](#使用-形似猫头鹰-选择器)
- [将样式与 :is 伪类选择器组合](#将样式与-is-伪类选择器组合)
- [使用 :root 选择器灵活控制字体大小](#使用-root-选择器灵活控制字体大小)
- [利用属性选择器来选择空链接](#利用属性选择器来选择空链接)
- [利用 `+` 隐藏额外的换行符](#利用--隐藏额外的换行符)
- [在行内元素之间添加换行符](#在行内元素之间添加换行符)

## CSS3 中的 counter

使用 `counter` 属性可将任何元素转换为编号列表。类似于有序列表标签的工作方式 `<ol>`

- 定义并初始化计数器 `counter-reset: tidbit-counter 19;`
- 增量计数器 `counter-increment: <counter name> <integer>`
- 使用 `counter(<counter name>, <counter list style>)` 作为 `content` 的内容
- 查看 [counter list style](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style-type#Values) 样式的完整列表

```html
<div>
  <h2>HTML</h2>
  <h2>CSS</h2>
  <h2>JS</h2>
</div>
```

CSS 如下：

```css
div {
  counter-reset: tidbit-counter 19;
}

h2::before {
  counter-increment: tidbit-counter;
  content: counter(tidbit-counter, thai);
}
```

效果如下：

![counter](https://upload-images.jianshu.io/upload_images/18281896-814fd949fa889d66.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 使用 CSS white-space 修复文本重叠

有时 `nowrap` 会导致文本重叠

```css
.container {
  display: flex;
}

div {
  white-space: nowrap;
}
```

![nowrap](https://upload-images.jianshu.io/upload_images/18281896-00a64d79204be949.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

我们设置了 `nowrap` 并没有发送重叠的问题，但当我们给其添加 width 的时候，看看会发生什么情况

```css
div {
  width: 100px;
}
```

![nowrap](https://upload-images.jianshu.io/upload_images/18281896-0e59d3158e83aafa.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

发生这种情况是因为原本的 `div` 宽度的默认值为 `width: auto`，这意味着盒子会根据其内容展开。但是，当我们给其一个固定的宽度时，会限制它的增长。文本无处可去，流进了同级框中。

我们可以通过将设置 `white-space` 为 `normal` 轻松修复它

```css
div {
  white-space: normal;
}
```

![normal](https://upload-images.jianshu.io/upload_images/18281896-6ac0f59622699d87.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Flexbox 居中元素

使用 CSS Flexbox，能够水平和垂直居中放置某些东西非常简单。标准方法是使用 flex 属性。但是您也可以使用 `margin` 来做。

使用 flex 属性：

```css
.parent {
  display: flex;
  align-items: center;
  justify-content: center;
}
```

使用具有自动 `margin` 边距的 Flexbox：

```css
.parent {
  display: flex;
}

.child {
  margin: auto;
}
```

效果如下：

![flex 水平垂直居中](https://upload-images.jianshu.io/upload_images/18281896-6c6a463d57bcd501.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Gird 居中元素

```css
.parent {
  display: grid;
}

.child {
  /* place-items: center center; */
  justify-self: center;
  align-self: center;
}
```

`grid` 和 `margin`

```css
.parent {
  display: grid;
}

.child {
  margin: auto;
}
```

## 在 CSS 中更改光标颜色

使用 `caret-color` 更改光标（尖号）的颜色：

```css
input {
  /* default */
  caret-color: auto;
}

input {
  /* custom */
  caret-color: DeepPink;
}
```

![caret-color](https://upload-images.jianshu.io/upload_images/18281896-1d6c682dd8baf4bd.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 使非密码输入使用符号替代

这适用于文本输入（例如 `text`、`textarea` 等），但不能更改实际的密码输入。

`password` 默认样式

```css
input {
  -webkit-text-security: disc; /* default */ }
}
```

![disc](https://upload-images.jianshu.io/upload_images/18281896-ca89962fb2fe2043.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

```css
input {
  -webkit-text-security: none;
}
input {
  -webkit-text-security: circle;
}
input {
  -webkit-text-security: square;
}
```

![circle](https://upload-images.jianshu.io/upload_images/18281896-eb001906c79276a1.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![square](https://upload-images.jianshu.io/upload_images/18281896-f4c1672a26c46aae.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## CSS user-select 禁用文本选择

- 使用 `user-select: none` 使元素的内容不可选。
- 使用 `user-select: all` 用户只需点击一次选择文本

如果您试图创建一个简单的文本复制和粘贴体验，这将非常有用 👍

```css
/* 只需单击一次即可选择所有文本 */
p {
  user-select: all;
}

/* 禁用文本选择 */
p {
  user-select: none;
}
```

## 自定义 CSS 选择样式

CSS `::selection` 伪元素使您可以在文本突出显示时将样式应用于文本。

```css
p::selection {
  background: DeepPink;
  color: white;
}
```

对于 Firefox，您将需要使用 `::-moz-selection`

```css
p::-moz-selection {
  background: DeepPink;
  color: white;
}
```

## CSS 变量

原生 CSS 支持变量，而无需 sass 预处理器，也无需编译

你可以在全局范围的任何地方访问变量，而本地作用域将只在特定的选择器中

### 全局范围内定义

```css
/* 所有选择器中都可用 */
:root {
  --color-red: red;
}

.text {
  color: var(--color-red);
}

.text-1 {
  color: var(--color-red);
}
```

### 局部范围内定义

```css
/* 仅限于.local 类 */
.local {
  --color-blue: blue;
  color: var(--color); /* blue */
}

.text {
  color: var(--color-blue); /* 没有效果，找不到改变量 */
}
```

## text-rendering

CSS 关于文本渲染的 [`text-rendering`](https://developer.mozilla.org/en-US/docs/Web/CSS/text-rendering) 属性告诉渲染引擎工作时如何优化显示文本。 浏览器会在渲染速度、易读性（清晰度）和几何精度方面做一个权衡。

语法：

```css
text-rendering: optimizeLegibility | auto | optimizeSpeed | geometricPrecision;
```

- `auto`：浏览器依照某些根据去推测在绘制文本时，何时该优化速度，易读性或者几何精度。对于该值在不同浏览器中解释的差异，请看兼容性表。
- `optimizeSpeed`：浏览器在绘制文本时将着重考虑渲染速度，而不是易读性和几何精度。它会使字间距和连字无效。Gecko 默认开启该属性，Firefox 是默认 20px 以下开启该属性。
- `optimizeLegibility`：浏览器在绘制文本时将着重考虑易读性，而不是渲染速度和几何精度。它会使字间距和连字有效。**该属性值在移动设备上会造成比较明显的性能问题**
- `geometricPrecision`：浏览器在绘制文本时将着重考虑几何精度， 而不是渲染速度和易读性。字体的某些方面—比如字间距—不再线性缩放，所以该值可以使使用某些字体的文本看起来不错。

```css
body {
  text-rendering: optimizeLegibility;
}
```

## 类似原生的 IOS 滚动

- `-webkit-overflow-scrolling: touch` 当手指从触摸屏上移开，会保持一段时间的滚动
- `-webkit-overflow-scrolling: auto` 当手指从触摸屏上移开，滚动会立即停止

这些属性只能在 Safari iOS 中使用

```css
body {
  -webkit-overflow-scrolling: touch;
  overflow-y: auto;
}
```

- [Scroll Bouncing On Your Websites](https://www.smashingmagazine.com/2018/08/scroll-bouncing-websites/)
- [Momentum Scrolling on iOS Overflow Elements](https://css-tricks.com/snippets/css/momentum-scrolling-on-ios-overflow-elements/)

## 蚀刻文字

创建一种效果，使文本看上去被“蚀刻”或雕刻到背景中。

- 使用 `text-shadow` 创建一个白色的影子偏移 `0px` 水平和 `2px` 从原始位置垂直。
- 为了使效果起作用，背景必须比阴影更暗。
- 文字颜色应略微褪色，使其看起来像是从背景上雕刻/雕刻出来的。

```css
.etched-text {
  text-shadow: 0 2px white;
  font-size: 1.5rem;
  font-weight: bold;
  color: #b8bec5;
}
```

## 实现文本溢出省略效果

- 单行文本溢出

```css
.text-ellipsis {
  width: 250px;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}
```

- 多行文本溢出

```css
.text-ellipsis {
  width: 250px;
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
  overflow: hidden;
  text-overflow: ellipsis;
}
```

- 定位 + 渐变

```css
.truncate-text-multiline {
  position: relative;
  overflow: hidden;
  display: block;
  height: 109.2px;
  margin: 0 auto;
  font-size: 26px;
  line-height: 1.4;
  width: 400px;
  background: #f5f6f9;
  color: #333;
}

.truncate-text-multiline:after {
  content: '';
  position: absolute;
  bottom: 0;
  right: 0;
  width: 150px;
  height: 36.4px;
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #f5f6f9 50%);
}
```

![溢出省略](https://upload-images.jianshu.io/upload_images/18281896-0d99d4c3a992f4c0.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 渐变文字

- `background` 与 `linear-gradient` 值一起使用可为文本元素提供渐变背景。
- `webkit-text-fill-color: transparent` 用于透明颜色填充文本。
- `webkit-background-clip: text` 用于用文本剪切背景，用渐变背景作为颜色填充文本。

```css
.gradient-text {
  background: linear-gradient(120deg, #fccb90 0%, #d57eeb 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
```

![渐变文字](https://upload-images.jianshu.io/upload_images/18281896-a218fe9a96cddceb.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 文本描边效果

- `-webkit-text-stroke` 为文本字符指定了文本宽 `width` 和文本颜色 `color`
- `text-stroke-width`：设置或检索对象中的文字的描边厚度
- `text-stroke-color`：设置或检索对象中的文字的描边颜色

```css
.text {
  -webkit-text-stroke: 3px black;
}
```

效果如下：

![文本描边效果](https://upload-images.jianshu.io/upload_images/18281896-a41354ed2b62674a.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

[介绍文本笔画](https://www.webkit.org/blog/85/introducing-text-stroke/)

## 系统字体堆栈

使用本机的操作系统字体来接近本机应用程序的感觉。

- 使用 `font-family` 定义字体列表。
- 浏览器会查找每个连续的字体，如果可能的话，会选择第一个字体，如果找不到字体（在系统上或 CSS 中定义），则会退回到下一个字体。
- `-apple-system` 是 San Francisco,，在 iOS 和 macOS（而不是 Chrome）上使用。
- `BlinkMacSystemFont` 是 San Francisco，在 macOS Chrome 上使用。
- `'Segoe UI'` 在 Windows 10 上使用。
- `Roboto` 在 Android 上使用。
- `Oxygen-Sans` 在带有 KDE 的 Linux 上使用。
- `Ubuntu` 用于 Ubuntu （所有变体）。
- `Cantarell` 在带有 GNOME Shell 的 Linux 上使用。
- `'Helvetica Neue'` 并 `Helvetica`在 macOS 10.10 及更低版本上使用。
- `Arial` 是所有操作系统广泛支持的字体。
- 如果不支持其他字体，`sans-serif` 是后备无衬线字体。

```css
.system-font-stack {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    Oxygen-Sans, Ubuntu, Cantarell, 'Helvetica Neue', Helvetica, Arial,
    sans-serif;
}
```

## 叠纸效果

```css
.paper {
  background: #fff;
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.15), 0 10px 0 -5px #eee,
    0 10px 1px -4px rgba(0, 0, 0, 0.15), 0 20px 0 -10px #eee,
    0 20px 1px -9px rgba(0, 0, 0, 0.15);
  padding: 30px;
}
```

效果如下：

![叠纸效果](https://upload-images.jianshu.io/upload_images/18281896-d830c066a31b3e68.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 隐藏数字输入微调器

- `::-webkit-inner-spin-button` CSS 伪元素用于设置数字选择器 `<input>` 元素的微调器按钮内部的样式。
- `::-webkit outer spin button` 设置外部样式
- `-webkit-appearance`：改变按钮和其他控件的外观，使其类似于原生控件。
- `::-webkit-inner-spin-button`、`::-webkit outer spin button` 和 `-webkit-appearance` 都是不规范的属性，它们没有出现在 CSS 规范草案中。有些浏览器不支持或渲染效果不同。

这里我们使用 [`-webkit-appearance`](https://developer.mozilla.org/en-US/docs/Web/CSS/appearance)，语法如下：

```css
-webkit-appearance：none | button | button-bevel ....
```

从视觉上隐藏数字选择器 `<input>` 元素的微调器：

```css
input[type='number']::-webkit-inner-spin-button {
  -webkit-appearance: none;
  margin: 0;
}
```

正常情况下：

![数字选择器](https://upload-images.jianshu.io/upload_images/18281896-4bc12089376f68f3.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

隐藏后：

![数字选择器](https://upload-images.jianshu.io/upload_images/18281896-25e89463b9905bd8.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 发光的蓝色输入亮点

```css
input[type='text'],
textarea {
  padding: 3px 0px 3px 3px;
  margin: 5px 1px 3px 0px;
  border: 1px solid #dddddd;
  outline: none;
  transition: all 0.3s ease-in-out;
}

input[type='text']:focus,
textarea:focus {
  padding: 3px 0px 3px 3px;
  margin: 5px 1px 3px 0px;
  border: 1px solid rgba(81, 203, 238, 1);
  box-shadow: 0 0 5px rgba(81, 203, 238, 1);
}
```

![发光的输入框](https://upload-images.jianshu.io/upload_images/18281896-d1e390d36742ffe8.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 使用 fieldset 禁用表单

通过将控件或任何内容包裹在 `<fieldset>` 中并应用 `disabled` 属性来禁用整个表单或输入组

```html
<style>
  [disabled] {
    display: none;
  }
</style>

<form name="form">
  <label for="has-language">
    <input
      type="checkbox"
      id="has-language"
      name="has-language"
      onChange="document.forms.form.language.disabled = !this.checked"
    />
    Select language
  </label>
  <fieldset name="language" disabled>
    <legend>Language:</legend>
    <input type="text" name="HTML" placeholder="HTML" />
    <input type="text" name="CSS" placeholder="CSS" />
    <input type="text" name="JS" placeholder="JS" />
  </fieldset>
</form>
```

## 非表单 fieldset 外观

```html
<section class="fieldset">
  <h1>This is not a fieldset</h1>
  <p>Booyah!</p>
</section>
```

CSS 如下：

```css
.fieldset {
  position: relative;
  border: 1px solid #ddd;
  padding: 10px;
}

.fieldset h1 {
  position: absolute;
  top: 0;
  font-size: 18px;
  line-height: 1;
  margin: -9px 0 0;
  background: #fff;
  padding: 0 3px;
}
```

效果如下：

![fieldset](https://upload-images.jianshu.io/upload_images/18281896-b6f7ecd73b6b096d.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 将 WebKit 的文件上传输入按钮强制向右移动

```css
input[type='file'] {
  -webkit-appearance: none;
  -webkit-rtl-ordering: left;
  padding: 10px;
  border: 1px solid #3e68ff;
  border-radius: 8px;
  text-align: left;
}

input[type='file']::-webkit-file-upload-button {
  -webkit-appearance: none;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.25em 0.75em;
  margin: 0;
  float: right;
  border: none;
  background-color: transparent;
  cursor: pointer;
  min-width: 10ch;
  min-height: 44px;
  line-height: 1.1;
  background-color: #3e68ff;
  color: #fff;
  border-radius: 8px;
  box-shadow: 0 3px 5px rgba(0, 0, 0, 0.18);
}
```

![上传文件按钮右移](https://upload-images.jianshu.io/upload_images/18281896-3e7d94d8687c114f.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 简单而漂亮的 Blockquote 样式

```css
blockquote {
  background: #f9f9f9;
  border-left: 10px solid #ccc;
  margin: 1.5em 10px;
  padding: 1em 10px;
  quotes: '\201C''\201D''\2018''\2019';
}

blockquote:before {
  color: #ccc;
  content: open-quote;
  font-size: 4em;
  line-height: 0.1em;
  margin-right: 0.25em;
  vertical-align: -0.4em;
}

blockquote p {
  display: inline;
}
```

效果如下：

![简单而漂亮的 Blockquote 样式](https://upload-images.jianshu.io/upload_images/18281896-848e22c66dfb1ea0.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 使用纯 CSS 创建三角形

```css
.triangle {
  width: 0;
  height: 0;
  border-top: 20px solid #9c27b0;
  border-left: 20px solid transparent;
  border-right: 20px solid transparent;
}
```

效果如下：

![三角形](https://upload-images.jianshu.io/upload_images/18281896-1346666588eb3aca.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 制作一个列宽相等的表格

显式设置每个单元格的宽度是使所有列具有相同宽度的简单方法。例如，下面的 CSS 声明将包含四列的表拆分为宽度相同的部分：

```css
table td {
  width: 25%;
}
```

但是，如果表的列数是动态的，则该方法不起作用。幸运的是，我们可以使用 `table-layout` 属性来实现这一点。不管表有多少列，它们的宽度都是相同的。

```css
table {
  table-layout: fixed;
}
```

`table-layout: fixed` 可以让每个格子保持等宽：

```css
.calendar {
  table-layout: fixed;
}
```

无痛的 `table` 布局。

## 重置所有样式

仅使用一个属性将所有样式重置为默认值。

- 使用该`all`属性将所有样式（继承或不继承）重置为其默认值。
- **注意**：这不会影响 `direction`和`unicode-bidi`属性。

```css
.reset-all-styles {
  all: initial;
}
```

## 在 HTML 中的字符串中保留空格和换行符

我将通过表单中的 `<textarea>` 字段获得的工作描述渲染出来，并将其存储在数据库中。

现在，这个描述没有被解释为 HTML，当我把它添加到页面中时，浏览器没有考虑到空格和换行符。

我想要这个：

![保留空格和换行符](https://upload-images.jianshu.io/upload_images/18281896-0190648d25aa8efb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

但：

![未保留空格和换行符](https://upload-images.jianshu.io/upload_images/18281896-7788afeabc9ff598.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

我们可以添加以下 CSS 解决这个问题：

```css
.whitespace-pre-wrap {
  white-space: pre-wrap;
}
```

## 使用 hr 作为分隔符

我想在我的 HTML 页面上分离兄弟元素。

我的一个想法是将它们包装在 `section` 或 `div` 标签中，并在该元素的底部的顶部应用边距。

另一种方法是不触及整个 HTML 结构，而是放置一个标签作为分隔符。

所以，我使用了一个 `hr` 标签，它在语义上表示段落级标签之间的主题中断。

我以这种方式对其进行了样式设置，使其不可见但仍占用空间：

```css
hr {
  margin-top: 20px;
  border: none;
}
```

## 从图像中剔除白色背景

使用 `mix-blend-mode: multiply;`，从图像中剔除白色背景：

```css
img {
  mix-blend-mode: multiply;
}
```

效果如下：

![未使用 mix-blend-mode: multiply;](https://upload-images.jianshu.io/upload_images/18281896-a8898fe60dc62715.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![使用 mix-blend-mode: multiply;](https://upload-images.jianshu.io/upload_images/18281896-6df40560bc4a494a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 使用指针事件来控制鼠标事件

[`pointer-events`](https://developer.mozilla.org/en-US/docs/Web/CSS/pointer-events) 允许您指定鼠标如何与其触摸的元素进行交互。

要禁用按钮上的默认指针事件，例如：

```css
.button-disabled {
  opacity: 0.5;
  pointer-events: none;
}
```

## 指示缺少 alt 属性的 img 元素

以下 CSS 为任何缺少 `alt` 属性或 `alt` 属性为空的 `img` 提供红色轮廓：

```css
img:not([alt]),
img[alt=''] {
  outline: 8px solid red;
}
```

如果您使用的是 Visual Studio Code，则可以安装 [webhint 扩展](https://marketplace.visualstudio.com/items?itemName=webhint.vscode-webhint)。当您将鼠标悬停在元素上时，它将自动检测问题并显示详细信息。

![webhint image](https://upload-images.jianshu.io/upload_images/18281896-cbee5653f019dc2e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 快速输入颜色变量

我们通常为颜色声明变量，主要在文件顶部，如下所示：

```css
:root {
  --color-primary: #...;
}
```

然后，可以使用 `var` 函数重新使用这些颜色：

```css
.btn-primary {
  background-color: var(--color-primary);
}
```

如果您使用的是 VS Code，则不必完全键入 `var(...)`。相反，只需键入 `--`，VS Code 就会显示现有的颜色变量。

![Visual Studio Code 自动完成颜色变量](https://upload-images.jianshu.io/upload_images/18281896-e4d93450ea9bb2c6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 使用 currentColor 关键字重用当前颜色

我们可以一次性为 `color` 属性定义一个值，并将其与 `currentColor` 关键字一起重用，而不是在几个地方重复使用颜色。

```css
/* ❌ */
div {
  color: #d1d5db;
  background-image: linear-gradient(to bottom, #d1d5db, #fff);
}

/* ✅ */
div {
  color: #d1d5db;
  background-image: linear-gradient(to bottom, currentColor, #fff);
}
```

因为元素的 `color` 属性（如果未指定）是从其父元素继承的，所以我们可以在元素的子元素中使用 `currentColor` 关键字。

例如，假设我们希望链接的颜色与其容器（给定的 `div` 元素）相同：

```css
/* 不好的做法：在三个地方声明相同的颜色 */
div {
  color: #fff;
}

div a {
  border-bottom: 1px solid #fff;
  color: #fff;
  text-decoration: none;
}

/* 好的做法 */
div {
  color: #fff;
}

div a {
  border-bottom: 1px solid currentColor;
  color: currentColor;
  text-decoration: none;
}
```

我们经常在 camelCase 格式中使用 `currentColor` 关键字。但是，CSS 不区分大小写，这意味着`currentColor`、`CurrentColor` 甚至 `Currentcolor` 都是有效的关键字，并且与 `currentColor` 具有相同的效果。

## 给“默认”链接定义样式

给 “默认” 链接定义样式：

```css
a[href]:not([class]) {
  color: #008000;
  text-decoration: underline;
}
```

通过 CMS 系统插入的链接，通常没有 `class` 属性，以上样式可以识别它们，而且不会影响其它样式。

## 用 rem 来调整全局大小；用 em 来调整局部大小

在根元素设置基本字体大小后 (`html { font-size: 100%; }`), 使用 `em` 设置文本元素的字体大小:

```css
h2 {
  font-size: 2em;
}

p {
  font-size: 1em;
}
```

然后设置模块的字体大小为 `rem`:

```css
article {
  font-size: 1.25rem;
}

aside .module {
  font-size: 0.9rem;
}
```

现在，每个模块变得独立，更容易、灵活的样式便于维护。

## 为 body 元素添加行高

不必为每一个 `<p>`，`<h*>` 元素逐一添加 `line-height`，直接添加到 `body` 元素：

```css
body {
  line-height: 1.5;
}
```

文本元素可以很容易地继承 `body` 的样式。

## 转义 CSS 类名

CSS 类名不能包含 `:` 字符。例如，不可能在 CSS 中声明以下类：

```css
.lg:flex {
}
```

但是，我们可以使用 `\` 字符来更正它：

```css
.lg\:flex {
}
```

类名可以像往常一样在 HTML 中使用：

```html
<div class="lg:flex">...</div>
```

在一些 CSS 框架（如 [Tailwind](https://tailwindcss.com/)）中，经常使用 `\` 来转义 CSS 类名。

## 使用 SVG 图标

没有理由不使用 SVG 图标：

```css
.logo {
  background: url('logo.svg');
}
```

SVG 在所有分辨率下都可以良好缩放，并且支持所有 [IE9](https://caniuse.com/#search=svg) 以后的浏览器，现在使用它替换您的 .png，.jpg，或 .gif 文件吧。

> **注意**： 针对仅有图标的按钮，如果 SVG 没有加载成功的话，以下样式对无障碍有所帮助：

```css
.no-svg .icon-only::after {
  content: attr(aria-label);
}
```

## 在打印模式下显示链接

当用户打印网页时，他们将看不到实际的链接。如果一个链接同时显示文本和它的链接，它会更有用。

我们可以通过在 `:after` 元素中包含链接来实现：

```css
@media print {
  a::after {
    content: ' (' attr(href) ') ';
  }
}
```

在打印模式下，用户将看到包含在其内容之后的链接：

```html
<!-- 正常模式-->
<a href="https://getfrontend.tips">Front-End Tips</a>
<!-- 打印模式-->
<a href="https://getfrontend.tips">Front-End Tips (https://getfrontend.tips)</a>
```

## 隐藏 Microsoft Edge 的密码显示按钮

![image.png](https://upload-images.jianshu.io/upload_images/18281896-9c58577904f79002.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

如果您使用的是 Edge，需要隐藏 `input` 的 `password` 类型提供的**密码显示**按钮，可以使用下面的伪元素。

```css
::-ms-reveal {
  display: none;
}
```

> [新的 CSS 属性`input-security`正在使密码显示更容易](https://twitter.com/stefanjudis/status/1457281480556781568)。

## 防止锚链接消失在粘性标题后面

粘性标题是一种常见的布局，可以在许多网站上看到。问题是它不能很好地处理锚链接。

假设我们有一个包含不同锚链接的目录。每个锚都会将用户带到页面中的特定 `section`。

当用户单击定位点时，页面将滚动到目标 `section`。但该 `section` 的某些部分显示在标题下，这对用户来说不是一个好的体验。

为了防止这种情况发生，我们希望在目标的顶部添加一个边距，但它仅在滚动时有效。此时，`scroll-margin-top` 就派上了用场。

```css
header {
  height: 2rem;
}

section {
  scroll-margin-top: 2rem;
}
```

## 创建自定义表情符号光标

创建自定义光标有两种常用方法：

- 使用图像
- 创建 `canvas` 元素并生成 base64 图像

这两种方法最终都通过将图像的 URL 设置为 `cursor` 属性来更改光标：

```css
.custom-cursor {
  cursor: url(/path/to/image.png), auto;
}

/* 或者 */
.custom-cursor {
  cursor: url('data:image/png;base64,...'), auto;
}
```

要创建自定义表情符号光标，我们可以使用内联 SVG 元素，该元素在中心显示表情符号，如下所示：

```css
.custom-cursor {
  cursor: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewport="0 0 48 48" style="fill:black;font-size:24px"><text y="50%">🚀</text></svg>')
      16 0, auto;
}
```

> [查看效果](https://codepen.io/lio-zero/pen/GRvMEvY)

## CSS 重置盒模型

```css
*,
*::before,
*::after {
  box-sizing: border-box;
}
```

当与将所有元素边距减为零的重置规则或父规则一起使用时，这会将上边距应用于其他元素后面的所有元素。这是一种快速获得垂直节奏的方法。

```css
* + * {
  margin-top: 1.5rem;
}
```

如果你真的想更具选择性，那么我喜欢在以下特定情况下将其作为后代使用：

```css
article * + h2 {
  margin-top: 4rem;
}
```

这类似于堆栈的思想，但更针对标题元素，以便在内容节之间提供更多的喘息空间。

## 清除浮动

- 使用 `:after` 伪元素并应用 `content: ''` 以使其影响布局。
- 使用 `clear: both` 做出明确的元素都过去左右浮动。
- 将该元素设置为 `display: block` 块级元素才能正常运行

```css
.clearfix::after {
  content: '';
  display: block;
  clear: both;
}
```

> **注意**：仅在用于 `float` 构建布局时，此选项才有用。考虑使用更现代的方法，例如 `flexbox` 或 `grid` 布局

## :focus 状态样式

```css
.input {
  transition: 180ms box-shadow ease-in-out;
}
.input:focus {
  box-shadow: 0 0 0 3px hsla(245, 100%, calc(82%), 0.8);
  border-color: hsl(245, 100%, 42%);
  outline: 3px solid transparent;
}
```

![:focus](https://upload-images.jianshu.io/upload_images/18281896-3857ab24f2a8c899.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## :focus-within

创建带有视觉，不可编辑前缀的输入。

- 当用户与 `<input>` 字段交互时，使用 `:focus-within` 伪类选择器为父元素设置样式。

```html
<div class="input-box">
  <span class="prefix">+08</span>
  <input type="tel" placeholder="888 8888" />
</div>
```

css 如下

```css
.input-box {
  display: flex;
  align-items: center;
  max-width: 300px;
  background: #fff;
  border: 1px solid #a0a0a0;
  border-radius: 4px;
  padding-left: 0.5rem;
  overflow: hidden;
  font-family: sans-serif;
}

.input-box .prefix {
  font-weight: 300;
  font-size: 14px;
  color: #999;
}

.input-box input {
  flex-grow: 1;
  font-size: 14px;
  background: #fff;
  border: none;
  outline: none;
  padding: 0.5rem;
}

.input-box:focus-within {
  border-color: plum;
}
```

![:focus-within](https://upload-images.jianshu.io/upload_images/18281896-e56eebdb2db5ca70.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 实现分割线

实现分割线的方式有很多种，这里我们使用 `flex` 加伪元素（`::before` 和 `::after`）实现

```css
.divider {
  display: flex;
  align-items: center;
}

.divider::before,
.divider::after {
  content: '';
  flex: 1;
  height: 1px;
  background: #dcdfe6;
}

.divider::before {
  margin-right: 1rem;
}

.divider::after {
  margin-left: 1rem;
}
```

![分割线](https://upload-images.jianshu.io/upload_images/18281896-64451b14844cfa41.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

另一种使用 `grid`，左右两侧为水平线的标题可以构造为具有三列的网格：

```css
.heading {
  display: grid;
  grid-template-columns: 1fr auto 1fr;
  grid-gap: 1rem;
  text-align: center;
}
```

`1fr auto 1fr` 表示左侧和右侧列的宽度相同，它们将占用剩余的空间。

我们可以使用 `::before` 和 `::after` 伪元素分别表示标题的左侧和右侧：

```css
.heading::before,
.heading::after {
  align-self: center;
  border-top: 0.25rem double #e5e7eb;
  content: '';
}
```

> [查看效果](https://codepen.io/lio-zero/pen/qBXPjPV)

更多方法：[CSS 巧妙实现分隔线的几种方法](https://www.400zi.com/4258.html)

## 为破损的图片定义样式

只需要一点 CSS 就可以美化破损的图片：

```css
img {
  display: block;
  font-family: sans-serif;
  font-weight: 300;
  height: auto;
  line-height: 2;
  position: relative;
  text-align: center;
  width: 100%;
}
```

以添加伪元素的法则来显示用户信息和 URL 的引用：

```css
img::before {
  content: '很抱歉，下面的图像已损坏 :(';
  display: block;
  margin-bottom: 10px;
}

img::after {
  content: '(url: ' attr(src) ')';
  display: block;
  font-size: 12px;
}
```

了解更多关于这类样式的技巧，可以查阅 [Styling Broken Images](http://bitsofco.de/styling-broken-images/)。

## CSS `:empty`

通常，我们希望为包含内容的元素设置样式。当元素完全没有子元素或文本时，该怎么办？您可以使用 `:empty` 选择器：

```html
<p></p>
<!-- 注意空白区 -->

<p></p>
<!-- 中间什么都没有 -->
```

```css
p::before {
  font-family: 'FontAwesome';
  content: '\f240';
}

p:empty::before {
  content: '\f244';
}

p {
  color: silver;
}

p:empty {
  color: red;
}
```

### 显示空列表的占位符

通过使用 `:empty` 选择器，我们可以显示自定义占位符。

```css
ul:empty::after {
  content: 'Empty';
}
```

如果希望占位符更灵活，而不是在 CSS 中硬编码，则可以从属性中获取占位符，例如 `data-placeholder`：

```
ul:empty::after {
  content: attr(data-placeholder);
}
```

如果列表包含空格或空子节点，则 `:empty` 选择器无效。

### 设置空链接的内容

对于内容为空的链接，我们可以使用 `href` 属性替换内容：

```css
a[href^='http']:empty:before {
  content: attr(href);
}
```

## CSS :only-child

如果要设置没有兄弟元素的样式，请使用 `:only-child` 伪类选择器

```html
<ul>
  <li>child</li>
</ul>

<ul>
  <li>siblings</li>
  <li>siblings</li>
</ul>
```

```css
li:only-child {
  color: DeepPink;
}
```

## CSS :not()

不要使用两个不同的选择器来指定样式，然后使用另一个来否定使用它。`:not` 选择器可选择除与所传递参数匹配的元素之外的所有元素

```css
/* ❌ */
li {
  margin-left: 10px;
}

li:first-of-type {
  margin-left: 0;
}

/* ✅ 使用 :not() 要好很多 */
li:not(:first-of-type) {
  margin-left: 10px;
}
```

## 逗号分隔列表

使列表的每项都由逗号分隔：

```css
ul > li:not(:last-child)::after {
  content: ',';
}
```

因最后一项不加逗号，可以使用 `:not()` 伪类。

> **注意**： 这一技巧对于无障碍，特别是屏幕阅读器而言并不理想。而且复制粘贴并不会带走 CSS 生成的内容，需要注意。

## 移除最后一个导航项的边框

我们经常使用 `:last-child` 选择器取消应用最后一项的特定样式（例如 `border`）。创建每个项目都有底部边框的导航通常如下所示：

```css
li {
  border-bottom: 1px solid #e5e7eb;
}

/* 不向最后一项添加边框 */
li:last-child {
  border-bottom: none;
}
```

使用 `:not` 伪类，我们可以通过一个 CSS 声明使代码更短、更易于维护：

```css
/* 将边框添加到除最后一个项目外的所有项目 */
li:not(:last-child) {
  border-bottom: 1px solid #e5e7eb;
}
```

另一种方法是使用 `+` 选择器：

```css
li + li {
  border-top: 1px solid #e5e7eb;
}
```

## 隐藏没有静音、自动播放的影片

这是一个自定义用户样式表的不错的技巧。避免在加载页面时自动播放。如果没有静音，则不显示视频：

```css
video[autoplay]:not([muted]) {
  display: none;
}
```

## 单独的项目列表

`:after` 选择器的内容属性可用于分隔列表项：

```css
/* 内联项 */
span:not(:last-child):after {
  content: ' • ';
}

/* items 列表 */
li:not(:last-child):after {
  content: ',';
}
```

## CSS 设置 ::placeholder 文本的样式

使用 `::placeholder` 伪元素在 `<input>` 或 `<textarea>` 元素为占位符文本设置样式 。大多数现代浏览器都支持此功能，但对于较旧的浏览器，将需要供应商前缀。

```html
<input placeholder="CSS Placeholder" />
```

```css
::placeholder {
  color: pink;
}
```

![placeholder ](https://upload-images.jianshu.io/upload_images/18281896-eb0a27ff2f59f166.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## CSS :placeholder-shown

使用 `:placeholder-shown` 伪类为当前显示占位符文本的输入设置样式

```css
input:placeholder-shown {
  border-color: pink;
}
```

在逛到张鑫旭的博客时，看到一篇关于 [`:placeholder-shown`](https://www.zhangxinxu.com/wordpress/2018/12/css-placeholder-shown-material-design/) 的文章，里面示例的代码主要如下：

```css
/* 默认placeholder颜色透明不可见 */
.input-fill:placeholder-shown::placeholder {
  color: transparent;
}

.input-fill-x {
  position: relative;
}
.input-label {
  position: absolute;
  left: 16px;
  top: 14px;
  pointer-events: none;
}

.input-fill:not(:placeholder-shown) ~ .input-label,
.input-fill:focus ~ .input-label {
  transform: scale(0.75) translate(0, -32px);
}
```

![:placeholder-shown](https://upload-images.jianshu.io/upload_images/18281896-7705f8d2e9e5bce5.gif?imageMogr2/auto-orient/strip)

[`:placeholder-shown` 实现占位符过渡动画 demo](https://www.zhangxinxu.com/study/201812/placeholder-shown-label-transition-demo.php)

## 自定义列表

主要的几行代码如下：

```css
ul li::marker {
  content: attr(data-icon);
  font-size: 1.25em;
}

ol li::marker {
  content: counter(list-item);
  font-family: 'Indie Flower';
  font-size: 1.5em;
  color: purple;
}
```

上面例子中，`attr()` 用于抓取标签上的自定义属性 `data-*` 中的值赋予 content。详细例子请看：[CODEPEN](https://codepen.io/5t3ph/pen/KKgqeNB)

![1616732729(1).jpg](https://upload-images.jianshu.io/upload_images/18281896-849c1096ef2a2dcd.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 自定义文字选择

使用 `::selection` 伪选择器来选择其中的文本样式。

```css
::selection {
  background: aquamarine;
  color: black;
}

.custom-text-selection::selection {
  background: deeppink;
  color: white;
}
```

对于 Firefox，您将需要使用 `::-moz-selection`

```css
p::-moz-selection {
  background: deeppink;
  color: white;
}
```

## 自定义 WebKit 滚动条

为具有可滚动溢出的元素自定义滚动条样式。

- `::-webkit-scrollbar` 设置整个滚动条元素的样式。
- `::-webkit-scrollbar-track` 滚动条轨道（滚动条的背景）的样式。
- `::-webkit-scrollbar-thumb` 滚动条滑块（可拖动元素）的样式。
- `::-webkit-scrollbar-button` 设置滚动条上的按钮 (上下箭头)的样式。
- `::-webkit-scrollbar-track-piece` 设置滚动条没有滑块的轨道部分的样式。
- `::-webkit-scrollbar-corner` 设置当同时有垂直滚动条和水平滚动条时交汇的部分的样式。
- `::-webkit-resizer` 设置某些元素的 corner 部分的部分样式（如：textarea 的可拖动按钮）的样式。

```css
/* 为所以的滚动条设置相同的样式 */
::-webkit-scrollbar {
  width: 8px;
  background: transparent;
}

::-webkit-scrollbar-track {
  background: #e0e4f6;
  border-radius: 12px;
}

::-webkit-scrollbar-thumb {
  background: #666e8f;
  border-radius: 12px;
}
```

仅在单独地方设置滚动条样式：

```css
.box::-webkit-scrollbar {
  width: 8px;
  background: transparent;
}
.box::-webkit-scrollbar-track {
  background: #e0e4f6;
  border-radius: 12px;
}
.box::-webkit-scrollbar-thumb {
  background: #666e8f;
  border-radius: 12px;
}
```

相关资料：

- [Scrollbar Shenanigans](https://www.swyx.io/scrollbar-shenanigans/)
- [Strut Your Stuff With a Custom Scrollbar](https://css-tricks.com/strut-your-stuff-with-a-custom-scrollbar/)
- [scrollbar](https://css-tricks.com/almanac/properties/s/scrollbar/)
- [The story of the custom scrollbar using CSS](https://blog.greenroots.info/the-story-of-the-custom-scrollbar-using-css)

## 首字大写

- `::first-line` 伪元素选择器选择换行之前文本的首行。
- `::first-letter` 伪元素选择器应用于元素中文本的首字母。
- `:first-child` 伪类选择器仅选择第一段

```css
p::first-line {
  color: plum;
}
```

![first-line](https://upload-images.jianshu.io/upload_images/18281896-569c428b8b475b14.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

```css
p::first-letter {
  color: plum;
  font-size: 40px;
}
```

![first-letter](https://upload-images.jianshu.io/upload_images/18281896-f615e7c1fbd1c934.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

```csc
p:first-child {
  color: plum;
}
```

![first-child](https://upload-images.jianshu.io/upload_images/18281896-1ca352523054117d.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

使第一段的第一个字母大于文本的其余部分。

- 使用 `:first-child` 选择器仅选择第一段。
- 使用 `::first-letter` 伪元素为段落的第一个元素设置样式。

```css
p:first-child::first-letter {
  color: plum;
  float: left;
  margin: 0 8px 0 4px;
  font-size: 3rem;
  font-weight: bold;
  line-height: 1;
}
```

![首字大写](https://upload-images.jianshu.io/upload_images/18281896-715c53c472d5c380.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 只显示第一个字母

有些情况下，我们希望在生成的 HTML 中填充全文，但只显示第一个字母。其余的字符将在视觉上隐藏。例如，当我们必须支持更小的屏幕时，它非常有用。

这里的技巧是为元素设置零字体大小，而第一个字母的字体大小是正常的。

```css
.element {
  font-size: 0;
}

.element::first-letter {
  font-size: 1.5rem;
}
```

## 使用 `:nth-child()` 创建具有交替背景颜色的列表

使用 `:nth-child(odd)` 或 `:nth-child(even)` 伪类选择器将不同 `background-color` 的元素应用于根据其在同级组中的位置匹配的元素。

```css
li:nth-child(odd) {
  background-color: purple;
}
li:nth-child(even) {
  background: plum;
}
```

![1616744697(1).jpg](https://upload-images.jianshu.io/upload_images/18281896-a79b0cb4b8a7fcb8.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 使用负 `:nth-child` 和 `:nth-last-child` 来选择元素

使用负的 `nth-child` 可以选择 1 至 n 个元素。

在以下示例中，前三项将添加下划线。第二到第五项的范围为蓝色。

```css
li:nth-child(-n + 3) {
  text-decoration: underline;
}

li:nth-child(n + 2):nth-child(-n + 5) {
  color: #2563eb;
}
```

我们先隐藏所有的 `li` 标签，然后选择第 1 至第 3 个元素并显示出来

```css
li {
  display: none;
}

li:nth-child(-n + 3) {
  display: block;
}
```

选择除前 3 个之外的所有项目，并隐藏它们

```css
li:not(:nth-child(-n + 3)) {
  display: none;
}
```

同样地，`nth-last-child` 会选择最后几个子项。

```css
/* 在最后两项中添加 decorative */
li:nth-last-child(-n + 2) {
  text-decoration-line: line-through;
}
```

> [查看效果](https://codepen.io/lio-zero/pen/oNeqYzP)

## :hover

- 使用 `transition` 设置不透明度更改的动画。
- 使用 `:hover` 和 `:not` 伪类选择器将所有元素的不透明度更改为 0.5，但鼠标停留的元素除外。

```css
li {
  display: inline-block;
  padding: 0 16px;
  transition: opacity 0.3s;
}
.sibling-fade:hover li:not(:hover) {
  opacity: 0.5;
}
```

![sibling-fade](https://upload-images.jianshu.io/upload_images/18281896-1419b95aa0d1825b.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

`:hover` 可以配合动画和其他选择器做出很多效果，找时间在写一些例子，顺便加深印象

## ::marker

`::marker` 伪元素代表一个列表项的标记框 `<li>`。标记通常是一个项目符号或数字。

```css
ul li::marker {
  color: red;
  font-size: 1.5em;
}
```

![::marker](https://upload-images.jianshu.io/upload_images/18281896-fec616a19c4707a0.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 使用 :invalid 和 :valid 校验表单元素

- CSS 伪类 `:invalid` 表示任意内容未通过验证的 `<input>` 或其他 `<form>` 元素。
- CSS 伪类 `:valid` 表示内容验证正确的 `<input>` 或其他 `<form>` 元素。

```html
<form>
  <div>
    <label for="url_input">Enter a URL: </label>
    <input type="url" id="url_input" />
  </div>
</form>
```

```css
/* 当校验错误时 */
input:invalid {
  background-color: pink;
}
form:invalid {
  border: 2px solid pink;
  padding: 10px;
}

/* 当校验成功时 */
input:valid {
  background-color: #ddffdd;
}
form:valid {
  border: 2px solid #ddffdd;
  padding: 10px;
}
```

当校验错误时：

![1616748752(1).jpg](https://upload-images.jianshu.io/upload_images/18281896-208b947e9179e423.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

当校验成功时：

![1616748801(1).jpg](https://upload-images.jianshu.io/upload_images/18281896-021466bf1b81684c.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 使用 :checked 和 `:default` 赋予元素状态

`:checked` 伪类选择器表示任何处于选中状态的 `radio`，`checkbox` 或 `select` 元素中的 `option`。

```css
option:checked {
  color: coral;
}
```

![:checked](https://upload-images.jianshu.io/upload_images/18281896-dc60359daf4f3163.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

`:default` 伪类选择器只能作用在表单元素上，表示默认状态的表单元素。

`:default` 默认应用到有 checked 属性的的标签上。当你切换或选择其他选项时，该选择器不会跟随着应用到你选择的标签上。（它是固定的，不响应的）

示例（默认推荐）：

```css
input:default + label:after {
  content: ' (推荐)';
  color: coral;
}
```

![:default](https://upload-images.jianshu.io/upload_images/18281896-549649f4d87cafd1.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 将前导零附加到有序列表项

将 `list-style-type` 属性设置为以下值将为有序列表 ( `ol`) 的项追加零编号：

```css
ol {
  list-style-type: decimal-leading-zero;
}
```

然而，它只对指数小于 10 的项目有效。这意味着，如果我们的列表中有 100 多个项目，那么它们的前缀如下：

```txt
01. Item 02. Item ... 09. Item 10. Item ... 99. Item 100. Item ...
```

为了解决这个问题，我们可以使用 CSS 计数器。每项保存计数器的当前值，该值在下一项中递增 1：

```css
ol {
  counter-reset: items;
  list-style-type: none;
}

li {
  counter-increment: items;
}
```

要使用关联计数器值作为项的前缀，请使用 `::before` 伪元素。

```css
li:before {
  content: '00' counter(items) '. ';
}

li:nth-child(n + 10)::before {
  content: '0' counter(items) '. ';
}

li:nth-child(n + 100)::before {
  content: counter(items) '. ';
}
```

`:nth-child(n+10)` 选择器指示索引大于或等于 10 的项。它将覆盖应用于 `li::before` 元素的样式。以同样的方式，`:nth-child(n+100)` 覆盖了 `:nth-child(n+10)` 的样式。

## 使用特殊字符设置列表项的样式

我们通常使用圆形或方形来设置列表项的样式，如下所示：

```css
li {
  list-style-type: circle;
}
```

您知道列表样式类型属性也接受字符吗。这意味着我们可以使用表情符号或 Unicode 字符：

```css
li {
  list-style-type: '☀️';
}

/* 或 */
li {
  list-style-type: '\2600';
}
```

## 使用 “形似猫头鹰” 选择器

这个名字可能比较陌生，不过通用选择器（`*`）和相邻兄弟选择器（`+`）一起使用，效果非凡：

```css
* + * {
  margin-top: 1.5em;
}
```

在此示例中，文档流中的所有的相邻兄弟元素都将设置 `margin-top: 1.5em` 的样式。

更多 “形似猫头鹰” 的选择器，可参考 _A List Apart_ 上面 [Heydon Pickering 的文章](http://alistapart.com/article/axiomatic-css-and-lobotomized-owls)

## 将样式与 :is 伪类选择器组合

`:is` 伪类选择器为与参数中列出的选择器匹配的任何元素应用样式。

而不是编写单独的选择器：

```css
header a:hover,
nav a:hover,
footer a:hover {
  text-decoration: underline;
}
```

我们可以将它们合并为一个，如下所示：

```css
:is(header, nav, footer) a:hover {
  text-decoration: underline;
}
```

## 使用 :root 选择器灵活控制字体大小

在响应式布局中，字体大小应需要根据不同的视口进行调整。你可以计算字体大小根据视口高度和宽度，这时需要用到 `:root`：

```css
:root {
  font-size: calc(1vw + 1vh + 0.5vmin);
}
```

现在，您可以使用 **root em**

```css
body {
  font: 1rem/1.6 sans-serif;
}
```

## 利用属性选择器来选择空链接

当 `<a>` 元素没有文本内容，但有 `href` 属性的时候，显示它的 `href` 属性：

```css
a[href^='http']:empty::before {
  content: attr(href);
}
```

## 利用 `+` 隐藏额外的换行符

利用相邻兄弟选择器（`+`），在用作间距的换行符（`br`）上设置 `display: none`，有助于防止 CMS 用户使用额外的换行符。

```css
br + br {
  display: none;
}
```

## 在行内元素之间添加换行符

这是一个常见的场景，我们想把一个标题分成多行。例如，标题在大屏幕上连续显示。但在小屏幕上，它应该分成不同的部分。

在不使用 `br` 标签的情况下，我们可以从各种内联 `span` 元素构建标题。

```html
<h2>
  <span class="primary">Eet, sleep, code</span>
  <span>Travel around the world</span>
</h2>
```

通过使用 `::after` 伪元素，我们可以在第一个行内元素之后添加换行符：

```css
.primary::after {
  content: '\A';
  white-space: pre;
}
```

其中 `\A` 表示换行符。
