---
title: 介绍HTML
date: 2018-01-28 22:07:53
tags:
---

### W3C简介

万维网联盟（World Wide Web Consortium，W3C），又称W3C理事会，是万维网的主要国际标准组织。
万维网联盟（W3C）由蒂姆·伯纳斯-李于1994年10月离开欧洲核子研究中心（CERN）后成立，在欧盟执委会和国防高等研究计划署（DARPA）的支持下成立于麻省理工学院MIT计算机科学与人工智能实验室（MIT／LCS），DARPA曾率先推出了互联网及其前身ARPANET。
该组织试图通过W3C制定的新标准来促进业界成员间的兼容性和协议。不兼容的HTML版本由不同的供应商提供，导致网页显示方式不一致。联盟试图让所有的供应商实施一套由联盟选择的核心原则和组件。

### MDN简介

MDN Web Docs（旧称Mozilla Developer Network、Mozilla Developer Center，简称MDN）是一个汇集众多Mozilla基金会产品和网络技术开发文档的免费网站。

### HTML简介

超文本标记语言（英语：HyperText Markup Language，简称：HTML）是一种用于创建网页的标准标记语言。HTML是一种基础技术，常与CSS、JavaScript一起被众多网站用于设计令人赏心悦目的网页、网页应用程序以及移动应用程序的用户界面。网页浏览器可以读取HTML文件，并将其渲染成可视化网页。HTML描述了一个网站的结构语义随着线索的呈现，使之成为一种标记语言而非编程语言。
HTML元素是构建网站的基石。HTML允许嵌入图像与对象，并且可以用于创建交互式表单，它被用来结构化信息——例如标题、段落和列表等等，也可用来在一定程度上描述文档的外观和语义。HTML的语言形式为尖括号包围的HTML元素（如<html>），浏览器使用HTML标签和脚本来诠释网页内容，但不会将它们显示在页面上。
HTML可以嵌入如JavaScript的脚本语言，它们会影响HTML网页的行为。网页浏览器也可以引用层叠样式表（CSS）来定义文本和其它元素的外观与布局。维护HTML和CSS标准的组织万维网联盟（W3C）鼓励人们使用CSS替代一些用于表现的HTML元素。

### HTML标签

| 标签                                       | 全称                        | 描述                                       |
| ---------------------------------------- | ------------------------- | ---------------------------------------- |
| < !–…– >                                 |                           | 定义注释。                                    |
| < !DOCTYPE >                             |                           | 定义文档类型。                                  |
| [< a >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/a) | Anchor                    | **HTML`<a>`元素**  (或锚元素) 可以创建一个到其他网页、文件、同一页面内的位置、电子邮件地址或任何其他URL的超链接。 |
| [< abbr >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/abbr) | Abbreviation              | **HTML`<abbr>`元素**代表缩写，并可选择提供一个完整的描述。    |
| [< acronym >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/acronym) | Acronym                   | **已废弃**。**HTML`<acronym>`元素**允许作者明确地声明一个字符序列，它们构成一个单词的首字母缩写或简略语。 |
| [< address >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/address) | Address                   | **HTML`<address>`元素**可以让作者为它最近的[`article`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/article)或者[`body`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/body)祖先元素提供联系信息。在后一种情况下，它应用于整个文档。 |
| [< applet >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/applet) | Applet                    | **已废弃**。**HTML`<applet>`元素**标志着包含了Java的applet。 |
| [< area >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/area) | Area                      | **HTML`<area>`元素**在图片上定义一个热点区域，可以关联一个超链接。`<area>`元素仅在`<map>`元素内部使用。 |
| [< article >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/article) | Article                   | **HTML`<article>`元素**表示文档、页面、应用或网站中的独立结构，其意在成为可独立分配的或可复用的结构，如在发布中，它可能是论坛帖子、杂志或新闻文章、博客、用户提交的评论、交互式组件，或者其他独立的内容项目。 |
| [< aside >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/aside) | Aside                     | **HTML`<article>`元素**表示一个和其余页面内容几乎无关的部分，被认为是独立于该内容的一部分并且可以被单独的拆分出来而不会使整体受影响。其通常表现为侧边栏或者嵌入内容。他们通常包含在工具条，例如来自词汇表的定义。也可能有其他类型的信息，例如相关的广告、笔者的传记、web 应用程序、个人资料信息，或在博客上的相关链接。 |
| [< audio >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/audio) | Audio                     | **HTML`<audio>`元素**用于在文档中表示音频内容。`<audio>` 元素可以包含多个音频资源， 这些音频资源可以使用 `src` 属性或者[`source`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/source) 元素来进行描述； 浏览器将会选择最合适的一个来使用。对于不支持`<audio>`元素的浏览器，`<audio>`元素也可以作为浏览器不识别的内容加入到文档中。 |
| [< b >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/b) | Blod                      | **HTML`<b>`元素**表示相对于普通文本字体上的区别，但不表示任何特殊的强调或者关联，通常以粗体显示。 |
| [< base >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/base) | Base                      | **HTML`<base>`元素**指定用于一个文档中包含的所有相对URL的基本URL。 |
| [< basefont >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/basefont) | Basefont                  | **已废弃**。**HTML`<basefont>`元素**用来设置文档的默认字体大小。使用[`font`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/font)可以相对于默认字体大小进行变化。 |
| [< bdi >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/bdi) |                           | **HTML`<bdi>`元素**（双向隔离元素）会隔离可能以不同方向进行格式化的外部文本。当不知道是从什么方向嵌入文本，如来自于数据库的文本（有起数据库的文本方向）的时候，该元素是十分有用的。 |
| [< bdo >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/bdo) | Bidirectional Override    | **HTML`<bdo>`元素**（*HTML双向覆盖元素*）用于覆盖当前文本的朝向，它使得字符按给定的方向排列。 |
| [< bgsound >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/bgsound) |                           | **非标准**。**HTML`<bgsound>`元素**是IE浏览器中设置网页背景音乐的元素。 |
| [< big >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/big) | Big                       | **已废弃**。**HTML`<big>`元素**使字体加大一号（例如从小号（small）到中号（medium），从大号（large）到加大（x-large）），最大不超过浏览器的最大字体。 |
| [< blink >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/blink) |                           | **已废弃**。**HTML`<blink>`元素**不是标准元素，它会使包含其中的文本闪烁。 |
| [< blockquote >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote) | Blockquote                | **HTML`<blockquote>`元素**（或者 HTML 块级引用元素）代表其中的文字是引用内容。通常在渲染时，这部分的内容会有一定的缩进（[注](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/blockquote#Notes) 中说明了如何更改）。若引文来源于网络，则可以将原内容的出处 URL 地址设置到 cite 特性上，若要以文本的形式告知读者引文的出处时，可以通过 [`cite`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/cite) 元素。 |
| [< body >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/body) | Body                      | **HTML 主体元素`<body>`**表示的是HTML文档的主体内容，任何一个HTML文档，只允许存在一个`<body>`元素。 |
| [< br >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/br) | Break                     | **HTML`<br>`元素**在文本中产生一个换行（回车键）。这对于写诗或写一个地址来说显得很有用。它可以将行明显地分开。 |
| [< button >](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/button) | Button                    | **HTML`<button>`元素**表示一个可点击的按钮。能够在表单，或者 HTML 文档的任一需要按钮的位置。默认情况下 HTML 按钮会呈现与用户主机相似的样式，基于 [user agent](https://developer.mozilla.org/en-US/docs/Glossary/user_agent)。 |
| [< canvas >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/canvas) |                           | **HTML`<canvas>`元素**可被被用来通过脚本（通常是JavaScript）绘制图形。比如，它可以被用来绘制图形，制作图片集合，甚至用来实现动画效果。你可以（也应该）在元素标签内写入可提供替代的的代码内容，这些内容将会在在旧的、不支持`<canvas>`元素的浏览器或是禁用了JavaScript的浏览器内渲染并展现。 |
| [< caption >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/caption) | Caption                   | **HTML`<caption>`元素**（or *HTML 表格标题元素*）展示一个表格的标题， 它常常作为 [`table`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/table)的第一个子元素出现，同时显示在表格内容的最前面，但是，它同样可以被CSS样式化，所以，它同样可以出现在任何一个一个相对于表格的做任意位置。 |
| [< center >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/center) | Center                    | **已废弃**。[块级元素](https://developer.mozilla.org/en-US/docs/HTML/Block-level_elements)，**HTML`<center>`元素**是个 可以包含段落，以及其它块级和内联元素。这个元素的整个内容在它的上级元素中水平居中(通常是 [`body`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/body))。 |
| [< cite >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/cite) | Cite                      | **HTML`<cite>`元素**表示一个作品的引用。它必须包含引用作品的符合简写格式的标题或者URL，它可能是一个根据添加引用元数据的约定的简写形式。 |
| [< code >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/code) | Code                      | **HTML`<code>`元素**呈现一段计算机代码。默认情况下，它以浏览器的默认等宽字体显示。 |
| [< col >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/col) | Column                    | **HTML`<col>`元素**定义表格中的列，并用于定义所有公共单元格上的公共语义。它通常位于元素[`<colgroup>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/colgroup)内。 |
| [< colgroup >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/colgroup) | Colgroup                  | **HTML`<colgroup>`元素**定义表中的一组列表。         |
| [< command >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/command) |                           | **已废弃**。**HTML`<command>`元素**表示一个用户可以调用的命令。 |
| [< content >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/content) |                           | **已废弃**。**HTML`<content>`元素**— [Web 组件](https://developer.mozilla.org/en-US/docs/Web/Web_Components) 的技术套件的废弃部分 — 用于 [Shadow DOM](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Shadow_DOM) 内部作为 [`insertion point`](https://developer.mozilla.org/zh-CN/docs/Glossary/insertion_point)，并且不可用于任何正常的 HTML，现在已被 [`slot`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/slot) 元素代替，它在 DOM 中创建一个位置，Shadow DOM 会插入这里。 |
| [< data >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/data) |                           | **HTML`<data>`元素**将一个指定内容和机器可读的翻译联系在一起。但如果内容是与 time 或者 date 相关的，一定要使用 [`time`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/time)。 |
| [< datalist >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist) |                           | **HTML`<datalist>`元素**包含了一组[`option`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/option)元素，这些元素表示其它表单控件可选值。 |
| [< dd >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dd) | Definition Description    | **HTML`<dd>`元素**（*HTML 描述元素*）用来指明一个描述列表（[`dl`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/dl)）元素中一个术语的描述。这个元素只能作为描述列表元素的子元素出现，并且必须跟着一个 [`dt`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/dt) 元素。 |
| [< del >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/del) | Delete                    | **HTML`<del>`元素**表示已经从文档中删除的文本范围。此元素通常是（但不必）呈现删除线的文本。 |
| [< details >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/details) |                           | **HTML`<details>`元素**被用作发现小部件，用户可以从其中检索附加信息。 |
| [< dfn >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dfn) | Defining Instance         | **HTML`<dfn>`元素**表示术语的一个定义。              |
| [< dialog >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dialog) |                           | **HTML`<dialog>`元素**表示一个对话框或其他交互式组件，例如一个检查员或窗口。 |
| [< dir >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dir) |                           | **已废弃**。**HTML`<dir>`元素**表示一个目录，也就是文件名称的集合。 |
| [< div >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div) | Division                  | **HTML`<div>`元素**（或 *HTML 文档分区元素*）一个通用型的流内容容器，它在语义上不代表任何特定类型的内容，它可以被用来对其它元素进行分组，一般用于样式化相关的需求（使用 **class** 或 **id** 特性) 或者对具有相同特性的一组元素进行分组 (比如 **lang**)，它应该在没有任何其它语义元素可用时才使用 (比如 [`article`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/article) 或 [`nav`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/nav)) 。 |
| [< dl >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dl) | Definition List           | **HTML`<dl>`元素**（或 *HTML* *描述列表元素*）是一个包含术语定义以及描述的列表，通常用于展示词汇表或者元数据 (键-值对列表)。 |
| [< dt >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dt) | Definition Term           | **HTML`<dt>`元素**（或 *HTML 术语定义元素*）用于在一个定义列表中声明一个术语。该元素仅能作为 [`dl`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/dl) 的子元素出现。通常在该元素后面会跟着 [`dd`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/dd) 元素， 然而，多个连续出现的 `<dt>` 元素都将由出现在它们后面的第一个 [`dd`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/dd) 元素定义。 |
| [< element >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/element) |                           | **已废弃**。**HTML`<element>`元素**定义在最新的 HTML DOM 元素中。 |
| [< em >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em) | Emphasized                | **HTML`<em>`元素**标记出需要用户着重阅读的内容， `<em>` 元素是可以嵌套的，嵌套层次越深，则其包含的内容被认定为越需要着重阅读。 |
| [< embed >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/embed) |                           | **HTML`<embed>`元素**将外部内容嵌入文档中的指定位置。此内容由外部应用程序或其他交互式内容源（如浏览器插件）提供。 |
| [< fieldset >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/fieldset) | Fieldset                  | **HTML`<fieldset>`元素**通常用来对表单中的控制元素进行分组(也包括 label 元素)。 |
| [< figcaption >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figcaption) |                           | **HTML`<figcaption>`元素**是与其相关联的图片的说明/标题，用于描述其父节点 [`figure`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/figure)元素里的其他数据。这意味着 `<figcaption>` 在[`figure`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/figure) 块里是第一个或最后一个。同时 HTML Figcaption 元素是可选的；如果没有该元素，这个父节点的图片只是会没有说明/标题。 |
| [< figure >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure) |                           | **HTML`<figure>`元素**代表一段独立的内容，经常与说明（caption） [`figcaption`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/figcaption) 配合使用，并且作为一个独立的引用单元。当它属于主体（main flow）时，它的位置独立于主体。这个标签经常是在主文中引用的图片，插图，表格，代码段等等，当这部分转移到附录中或者其他页面时不会影响到主体。 |
| [< font >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/font) | Font                      | **已废弃**。**HTML`<font>`元素**定义了该内容的字体大小、顏色与表现。 |
| [< footer >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer) |                           | **HTML`<footer>`元素**表示最近一个[章节内容](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Sections_and_Outlines_of_an_HTML5_document#Defining_Sections_in_HTML5)或者[根节点](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Sections_and_Outlines_of_an_HTML5_document#Sectioning_root)（sectioning root ）元素的页脚。一个页脚通常包含该章节作者、版权数据或者与文档相关的链接等信息。 |
| [< form >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form) | Form                      | **HTML`<form>`元素**表示了文档中的一个区域，这个区域包含有交互控制元件，用来向web服务器提交信息。 |
| [< frame >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/frame) | Frame                     | **已废弃**。**HTML`<frame>`元素**定义了一个特定区域，另一个 HTML 文档可以在里面展示。帧应该在 [`frameset`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/frameset) 中使用。 |
| [< frameset >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/frameset) | Frameset                  | **已废弃**。**HTML`<frameset>`元素**是一个用于包含 [`frame`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/frame) 的 HTML 元素。 |
| [< h1 > to < h6 >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements) | Header1 to Header6        | **标题(Heading)元素**拥有六个不同的级别，`<h1>` 是最高级的，而 `<h6> `则是最低的级别。 一个标题元素能简要描述该节的主题。标题信息可以由用户代理可以使用，例如，自动构造某个文档中的内容表（就像本文档右边浮动栏一样）。 |
| [< head >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head) | Head                      | **HTML`<head>`元素**规定文档相关的通用信息（元数据），包括文档的标题，文档的样式和脚本的链接（定义）等。 |
| [< header >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header) |                           | **HTML`<header>`元素**表示一组引导性的帮助，可能包含标题元素，也可以包含其他元素，像logo、分节头部、搜索表单等。 |
| [< hgroup >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/hgroup) |                           | **这是一个实验中的功能**， **注意: **本元素已经从HTML5（W3C）规范中删除，但是它仍旧在 WHATWG 的 HTML 版本里。大多数浏览器都部分地实现，所以它不太可能消失。 **HTML`<hgroup>`元素**代表一个段的标题。它规定了在文档轮廓里（[the outline of the document](https://developer.mozilla.org/en-US/docs/Sections_and_Outlines_of_an_HTML5_document) ）的单一标题是它所属的隐式或显式部分的标题。 |
| [< hr >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/hr) | Horizontal                | **HTML`<hr>`元素**表示段落级元素之间的主题转换（例如，一个故事中的场景的改变，或一个章节的主题的改变）。在HTML的早期版本中，它是一个水平线。现在它仍能在可视化浏览器中表现为水平线，但目前被定义为语义上的，而不是表现层面上。 |
| [< html >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/html) | Hypertext Markup Language | **HTML`<html>`元素**表示一个HTML文档的根（顶级元素），所以它也被称为*根元素*。其他所有元素必须是此元素的后代。 |
| [< i >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/i) | Italic                    | **HTML`<i>`元素**用于表现因某些原因需要区分普通文本的一系列文本。例如技术术语、外文短语或是小说中人物的思想活动等，它的内容通常以斜体显示。 |
| [< iframe >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe) | Inline Frame              | **HTML内联框架元素`<iframe>`**表示嵌套的浏览上下文，有效地将另一个HTML页面嵌入到当前页面中。在HTML 4.01中，文档可能包含头部和正文，或头部和框架集，但不能包含正文和框架集。但是，`<iframe>`可以在正常的文档主体中使用。每个浏览上下文都有自己的会话历史记录和活动文档。包含嵌入内容的浏览上下文称为父浏览上下文。顶级浏览上下文（没有父级）通常是浏览器窗口。 |
| [< image >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/image) |                           | **非标准**。**HTML`<image>`元素**曾经是一个试验性的元素，用来显示图片。它从未被实现过，请使用标准的 [`<img>`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/img)元素。 |
| [< img >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img) | Image                     | **HTML`<img>`元素**代表文档中的一个图像。             |
| [< input >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input) | Input                     | **HTML`<input>`元素**用于为基于Web的表单创建交互式控件，以便接受来自用户的数据。 |
| [< ins >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ins) | Inserted                  | **HTML`<ins>`元素**定义已经被插入文档中的文本。          |
| [< isindex >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/isindex) |                           | **已废弃**。**HTML`<isindex>`元素**作用是使浏览器显示一个对话框，提示用户输入单行文本。在W3C的规范中建议，`<isindex>`元素最好被放置在[`head`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/head) 标签块内，但是对于浏览器来说，`<isindex>`标签在页面任何位置都没有关系。 |
| [< kbd >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/kbd) | Keyboard                  | **HTML键盘输入元素`<kbd>`**用于表示用户输入，它将产生一个行内元素，以浏览器的默认monospace字体显示。 |
| [< keygen >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/keygen) |                           | **已废弃**。**HTML`<keygen>`元素**是为了方便生成密钥材料和提交作为 [HTML form](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Forms) 的一部分的公钥。这种机制被用于设计基于 Web 的证书管理系统。按照预想，`<keygen>` 元素将用于 HTML 表单与其他的所需信息一起构造一个证书请求，该处理的结果将是一个带有签名的证书。 |
| [< label >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label) | Label                     | **HTML`<label>`元素**表示用户界面中项目的标题。它通常关联一个控件，或者是将控件放置在label元素内，或者是用作其属性。这样的控制称作label元素的*labeled control* 。 |
| [< legend >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/legend) | Legend                    | **HTML的`<legend>`元素**（也称为HTML的域说明元素（or HMTL Legend Field Element））代表一个用于表示它的父元素[`fieldset`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/fieldset)的内容的标题。 |
| [< li >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li) | List                      | **HTML`<li>`元素**（或者 *HTML 列表条目元素*）用于表示列表里的条目。它必须被包含在一个父元素里：一个有顺序的列表（[`ol`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/ol)），一个无顺序的列表（[`ul`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/ul)），或者一个菜单 ([`menu`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/menu))。在菜单或者无顺序的列表里，列表条目通常用点排列显示。在有顺序的列表里，列表条目通常是在左边有按升序排列计数的显示，例如数字或者字母。 |
| [< link >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link) | Link                      | **HTML`<link>`元素**指定了外部资源与当前文档的关系。这个元素的使用方法包括为导航定义关系框架。这个元素经常用来链接css文件。 |
| [< listing >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/listing) |                           | **已废弃**。**HTML`<listing>`元素**渲染了开始和结束标签之间的文本，而不会解释 HTML，并使用等宽字体。HTML2 标准建议，当一行不超过 132 个字符时，不应该将其拆开。 |
| [< main >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/main) |                           | **HTML`<main>`元素**呈现了文档[`body`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/body)或应用的主体部分。主体部分由与文档直接相关，或者扩展于文档的中心主题、应用的主要功能部分的内容组成。这部分内容在文档中应当是独一无二的，不包含任何在一系列文档中重复的内容，比如侧边栏，导航栏链接，版权信息，网站logo，搜索框（除非搜索框作为文档的主要功能）。 |
| [< map >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/map) | Map                       | **HTML`<main>`元素**与 [`area`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/area) 元素一起使用来定义一个图像映射(一个可点击的链接区域)。 |
| [< mark >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/mark) |                           | **HTML`<mark>`元素**代表突出显示的文字，例如可以为了标记特定上下文中的文本而使用这个标签。举个例子，它可以用来显示搜索引擎搜索后关键词。 |
| [< marquee >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/marquee) |                           | **已废弃**。**HTML`<marquee>`元素**用来插入一段滚动的文字。你可以使用它的属性控制当文本到达容器边缘发生的事情。 |
| [< menu >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/menu) | Menu                      | **HTML`<menu>`元素**呈现了一组用户可执行或激活的命令。这既包含了可能出现在屏幕顶端的列表菜单，也包含了那些隐藏在按钮之下、当点击按钮后显示出来的文本菜单。 |
| [< menuitem >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/menuitem) |                           | **这是一个实验中的功能**。用户可以通过**HTML`<menuitem>`元素**生成一个弹出式菜单。这包括上下文菜单，以及按钮可能附带的菜单。 这个标签可以被显式定义，带有文本标签和可选图标来描述其外观，或者作为一个间接命令，其行为由一个单独的元素定义。命令还可以选择包含复选框或分组共享单选按钮。（`<input type="checkbox">` 和 `<input type="radio">`） |
| [< meta >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta) | Meta                      | **HTML`<meta>`元素**表示那些不能由其它HTML元相关元素（[`base`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/base), [`link`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/link), [`script`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/script), [`style`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/style) 或 [`title`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/title)）之一表示的任何元数据信息。 |
| [< meter >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meter) |                           | **HTML`<meter>`元素**用来显示已知范围的标量值或者分数值。    |
| [< multicol >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/multicol) |                           | **非标准**。**HTML`<multicol>`元素**是一个实验元素，旨在允许多列布局。它从来没有任何显着的牵引力，并没有在任何主流浏览器中实现。 |
| [< nav >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav) |                           | **HTML`<nav>`元素**描绘一个含有多个超链接的区域，这个区域包含转到其他页面，或者页面内部其他部分的链接列表。 |
| [< nextid >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nextid) |                           | **已废弃**。**`<nextid>`** is an obsolete HTML element that served to enable the NeXT web designing tool to generate automatic NAME labels for its anchors. It was generated by that web editing tool automatically and was not to be adjusted or entered by hand. This element has the distinction of being the first element to become one of the "Lost Tags" by being eliminated from the official public DTD's of the HTML versions. It is also probably one of the least understood of all of the early HTML elements. |
| [< nobr >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nobr) |                           | **非标准**。**HTML`<nobr>`元素**阻止文本自动拆分成新行，所以它展示为长的一行，可能还需要滚动。这个标签不是标准的 HTML，并且不应该使用。 |
| [< noembed >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/noembed) |                           | **非标准** ，**已废弃**。**HTML`<noembed>`元素**是个废除的和不标准的方式，用于向不支持 [`embed`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/embed) ，或者不支持作者希望的 [嵌入式内容](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Content_categories#Embedded_content) 的浏览器提供替代（或者“后备”）内容。这个元素在 HTML 4.01 起废除，以支持 [`object`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/object)。后备内容应该插在 [`object`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/object) 的开始和结束标签之间。 |
| [< noframes >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/noframes) | Noframes                  | **HTML`<noframes>`元素**用于支持不支持  [`frame`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/frame) 元素的浏览器，或者这样配置的浏览器。 |
| [< noscript >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/noscript) | Noscript                  | 如果页面上的脚本类型不受支持或者当前在浏览器中关闭了脚本，则在**HTML`<noscript>`元素**中定义脚本未被执行时的替代内容。 |
| [< object >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/object) | Object                    | **HTML`<object>`元素**（或者称作 *HTML 嵌入对象元素*）表示引入一个外部资源，这个资源可能是一张图片，一个嵌入的浏览上下文，亦或是一个插件所使用的资源。 |
| [< ol >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol) | Ordered List              | **HTML`<ol>`元素**表示多个有序列表项，通常渲染为有带编号的列表。  |
| [< optgroup >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/optgroup) | Option Group              | 在一个web表单中，**HTML`<optgroup>`元素**会创建包含在一个 [`select`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/select) 元素中的一组选项。 |
| [< option >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/option) | Option                    | 在web表单中,  **HTML`<option>`元素**用于定义在[`select`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/select),  [`optgroup`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/optgroup) 或[`datalist`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/datalist) 元素中包含的项。`<option>`可以在弹出窗口和 html 文档中的其他项目列表中表示菜单项。 |
| [< output >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/output) |                           | **HTML`<output>`元素**表示计算或用户操作的结果。        |
| [< p >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p) | Paragraph                 | **HTML`<p>`元素**（或者说 *HTML 段落元素*）表示文本的一个段落。该元素通常表现为一整块与相邻文本分离的文本，或以垂直的空白隔离或以首行缩进。另外，<p> 是[块级元素](https://developer.mozilla.org/en-US/docs/HTML/Block-level_elements)。 |
| [< param >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/param) | Param                     | **HTML`<param>`元素**（或 *HTML Parameter 元素*）定义了 [`object`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/object)的参数 |
| [< picture >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) |                           | **这是一个实验中的功能**。 **HTML`<picture>`元素**是一个容器，用来为其内部特定的 [`img`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/img) 元素提供多样的 [`source`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/source)元素。浏览器会根据当前页面（即图片所在的盒子的容器）的布局以及当前浏览的设备（比如普通的屏幕和高清屏幕）去从中选择最合适的资源。 |
| [< plaintext >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/plaintext) |                           | **已废弃**。**HTML 纯文本元素`<plaintext>`** 将起始标签后面的任何东西渲染为纯文本，不会解释为 HTML。它没有闭合标签，因为任何后面的东西都会看做纯文本。 |
| [< pre >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/pre) | Preformatted              | **HTML`<pre>`元素**表示预定义格式文本。在该元素中的文本通常按照原文件中的编排，以等宽字体的形式展现出来，文本中的空白符（比如空格和换行符）都会显示出来。（紧跟在`<pre>`开始标签后的换行符也会被省略） |
| [< progress >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/progress) |                           | **HTML`<progress>`元素**用来显示一项任务的完成进度。虽然规范中没有规定该元素具体如何显示，浏览器开发商可以自己决定，但通常情况下，该元素都显示为一个进度条形式。 |
| [< q >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q) | Quotation                 | **HTML引用标签`<q>`元素**表示一个封闭的并且是短的行内引用的文本。这个标签是用来引用短的文本，所以请不要引入换行符；对于长的文本的引用请使用 [`blockquote`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/blockquote) 替代。 |
| [< rp >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/rp) |                           | **HTML`<rp>`元素**用于为那些不能使用 [`ruby`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/ruby) 元素展示 ruby 注解的浏览器，提供随后的圆括号。 |
| [< rt >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/rt) |                           | **HTML`<rt>`元素**包含字符的发音，字符在 ruby 注解中出现，它用于描述东亚字符的发音。这个元素始终在 [`ruby`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/ruby) 元素中使用。 |
| [< rtc >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/rtc) |                           | **HTML`<rtc>`元素**包含文字的语义注解，它们在 [`rb`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/rb) 元素中展示。[`rb`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/rb) 元素可以拥有发音 ([`rt`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/rt)) 和语义([`rtc`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/rtc)) 注解。 |
| [< ruby >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ruby) |                           | **HTML`<ruby>`元素**被用来展示东亚文字注音或字符注释。      |
| [< s >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/s) |                           | **HTML`<s>`元素**使用删除线来渲染文本。使用 `<s>` 元素来表示不再相关，或者不再准确的事情。但是当表示文档编辑时，不提倡使用 `<s>` ；为此，提倡使用 [`del`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/del) 和 [`ins`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/ins) 元素。 |
| [< samp >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/samp) | Sample                    | **HTML`<samp>`元素**用于标识计算机程序输出，通常使用浏览器缺省的 monotype 字体（例如 Lucida Console）。 |
| [< script >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script) | Script                    | **HTML`<script>`元素**用于嵌入或引用可执行脚本。        |
| [< section >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section) |                           | **HTML`<section>`元素**表示文档中的一个区域（或节），比如，内容中的一个专题组，一般来说会有包含一个标题（heading）。一般通过是否包含一个标题 ([`h1`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/h1)-[`h6`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/h6)element) 作为子节点来辨识每一个`<section>`。 |
| [< select >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select) | Select                    | **HTML`<select>`元素**是一种表单控件，可创建选项菜单。菜单内的选项为`<option>` , 可以由 `<optgroup>` 元素分组。选项可以被用户预先选择。 |
| [< shadow >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Shadow) |                           | **已废弃**。 **HTML`<shadow>`元素 **— [Web 组件](https://developer.mozilla.org/en-US/docs/Web/Web_Components)技术套件的废弃部分 — 目的是用作 Shadow DOM [insertion point](https://developer.mozilla.org/zh-CN/docs/Glossary/insertion_point)。如果你在 shadow host 下面创建了多个 shadow root，你就可能已经使用了它。在正常的 HTML 没有任何用处。 |
| [< slot >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/slot) |                           | **这是一个实验中的功能**。 **HTML`<slot>`元素**是[web组件](https://developer.mozilla.org/zh-CN/docs/Web/Web_Components)技术的一部分，slot是web组件的一个占位符，可以用来插入自定义的标记文本。可以创建不同的DOM树并进行渲染。 |
| [< small >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/small) | Small                     | **HTML`<small>`元素**將使文本的字体变小一号。（例如从大变成中等，从中等变成小，从小变成超小）。在HTML5中，除了它的样式含义，这个元素被重新定义为表示边注释和附属细则，包括版权和法律文本。 |
| [< source >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/source) |                           | The **HTML`<source>`element** specifies multiple media resources for either the [`picture`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/picture), the [`audio`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/audio) or the [`video`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/video) element. It is an empty element. It is commonly used to serve the same media content in [multiple formats supported by different browsers](https://developer.mozilla.org/en-US/docs/Media_formats_supported_by_the_audio_and_video_elements). |
| [< spacer >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/spacer) |                           | **非标准**， **已废弃**。 **HTML`<spacer>`元素**是过时的 HTML 元素，它可以向页面插入间隔。它由 Netscape 设计，用于实现单像素布局图像的相同效果，Web 设计师用它来向页面添加空白，而不需要实际使用图片。 但是，`<spacer>` 不再受任何主流浏览器支持，并且相同效果可以简单由 CSS 实现。 |
| [< span >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span) | Span                      | **HTML`<span>`**元素是短语内容的通用行内容器，并没有任何特殊语义。可以使用它来编组元素以达到某种样式意图（通过使用类或者Id属性），或者这些元素有着共同的属性，比如**lang**。应该在没有其他合适的语义元素时才使用它。`<span>` 与 [`div`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/div) 元素很相似，但 [`div`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/div) 是一个 [块元素](https://developer.mozilla.org/en-US/docs/HTML/Block-level_elements) 而 `<span>` 则是 [行内元素 ](https://developer.mozilla.org/en-US/docs/HTML/Inline_elements)。 |
| [< strike >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strike) |                           | **已废弃**。**HTML`<strike>`元素**（或者 HTML 删除线元素）在文本上放置删除线。 |
| [< strong >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong) | Strong                    | **HTML`<strong>`元素**表示文本十分重要，一般用粗体显示。    |
| [< style >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/style) | Style                     | **HTML`<style>`元素**包含了文档的样式化信息或者文档的一部分。指定的样式化星系包含的该元素内，通常是[CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)的格式。 |
| [< sub >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/sub) | Subscript                 | **HTML`<sub>`元素**定义了一个文本区域，出于排版的原因，与主要的文本相比，应该展示得更低并且更小。 |
| [< summary >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/summary) |                           | **HTML`<summary>`元素**用作一个[`details`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/details)元素的一个内容的摘要，标题或图例。 |
| [< sup >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/sup) | Superscript               | **HTML`<sup>`元素**定义了一个文本区域，出于排版的原因，与主要的文本相比，应该展示得更高并且更小。 |
| [< table >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table) | Table                     | **HTML`<table>`元素**表示表格数据 — 即通过二维数据表表示的信息。 |
| [< tbody >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tbody) | Table Body                | **HTML`<tbody>`元素**在一个`<table>`元素中可以出现一个或者更多。 |
| [< td >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/td) | Table Data Cell           | The *Table cell* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) element (`<td>`) defines a cell of a table that contains data. It participates in the *table model*. |
| [< template >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template) |                           | **HTML`<template>`元素**是一种用于保存客户端内容的机制，该内容在页面加载时不被渲染，但可以在运行时使用JavaScript进行实例化。 |
| [< textarea >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea) | Textarea                  | **HTML`<textarea>`元素**表示一个多行纯文本编辑控件。     |
| [< tfoot >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tfoot) | Table Foot                | The **HTML`<tfoot>`element** defines a set of rows summarizing the columns of the table. |
| [< th >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/th) | Table Head Cell           | **HTML`<th>`元素**定义表格内的表头单元格。             |
| [< thead >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/thead) | Table Head                | **HTML`<thead>`元素**定义了一组定义表格的列头的行。       |
| [< time >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/time) |                           | **HTML`<time>`元素**用来表示24小时制时间或者[公历日期](http://en.wikipedia.org/wiki/Gregorian_calendar)，若表示日期则也可包含时间和时区。 |
| [< title >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title) | Title                     | **HTML`<title>`元素**定义文档的标题，显示在浏览器的标题栏或标签页上。它只可以包含文本，若是包含有标签，则包含的任何标签都不会被解释。 |
| [< tr >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tr) | Table Row                 | **HTML`<tr>`元素**定义表格中的行。                 |
| [< track >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/track) |                           | **HTML`<track>`元素**被当作媒体元素—[`audio`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/audio) 和 [`video`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/video)的子元素来使用。它允许指定计时字幕（或者基于事件的数据），例如自动处理字幕。 |
| [< tt >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tt) | Teletype                  | **已废弃**。**HTML电报文本元素`<tt>`**产生一个内联元素，使用浏览器内置的 monotype 字体展示。这个元素用于给文本排版，使其等宽展示，就像电报那样。使用 [`code`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/code) 元素来展示等宽文本可能更加普遍。 |
| [< u >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/u) | Underline                 | **HTML`<u>`元素**使文本在其内容的基线下的一行呈现下划线。在HTML5中, 此元素表示具有未标注的文本跨度，显示渲染，非文本注释，例如将文本标记为中文文本中的专有名称（一个正确的中文标记）, 或 将文本标记为拼写错误。 |
| [< ul >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul) | Unordered List            | **HTML`<ul>`元素**（或 *HTML 无序列表元素*）代表多项的无序列表，即无数值排序项的集合，且它们在列表中的顺序是没有意义的。通常情况下，无序列表项的头部可以是几种形式，如一个点，一个圆形或方形。头部的风格并不是在页面的HTML描述定义，但在其相关的CSS 可以用 [`list-style-type`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/list-style-type) 属性。 |
| [< var >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/var) | Variable                  | **HTML`<var>`元素**表示变量的名称，或者由用户提供的值。      |
| [< video >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video) |                           | **HTML`<video>`元素**用于在HTML或者XHTML文档中嵌入视频内容。 |
| [< wbr >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/wbr) |                           | **HTML`<wbr>`元素 **— 一个文本中的位置，其中浏览器可以选择来换行，虽然它的换行规则可能不会在这里换行。 |
| [< xmp >](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/xmp) |                           | **已废弃**。 **HTML`<xmp>`元素**之间的内容不会被当作文档内容解析，而会被用等宽字体直接呈现。HTML2规范建议，本标签中的内容应该具有足够容纳每行80个字母的宽度。 |

### 什么是空元素

一个**空元素（empty element）**可能是 HTML，SVG，或者 MathML 里的一个不可能存在子节点（例如内嵌的元素或者元素内的文本）的[element](https://developer.mozilla.org/en-US/docs/Glossary/element)。

[HTML](http://www.w3.org/html/wg/drafts/html/CR/)，[SVG](http://www.w3.org/TR/SVG2/) 和 [MathML](http://www.w3.org/Math/draft-spec/) 的规范都详细定义了每个元素能包含的具体内容（define very precisely what each element can contain）。许多组合是没有任何语义含义的，比如一个 [`audio`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/audio) 元素嵌套在一个 [`hr`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/hr) 元素里。

在 HTML 中，通常在一个空元素上使用一个闭标签是无效的。例如， `<input type="text"></input>` 的闭标签是无效的 HTML。

在 HTML 中有以下这些空元素：

- [`area`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/area)
- [`base`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/base)
- [`br`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/br)
- [`col`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/col)
- [`colgroup`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/col)when the `span` is present
- [`command`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/command)
- [`embed`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/embed)
- [`hr`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/hr)
- [`img`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/img)
- [`input`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/input)
- [`keygen`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/keygen)
- [`link`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/link)
- [`meta`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/meta)
- [`param`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/param)
- [`source`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/source)
- [`track`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/track)
- [`wbr`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/wbr)

### 什么是可替换标签

CSS 里，**可替换元素（replaced element）**的展现不是由CSS来控制的。这些元素是一类外观渲染独立于CSS的外部对象。 典型的可替换元素有 [`img`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/img)、 [`object`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/object)、 [`video`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/video)和表单元素，如[`textarea`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/textarea)、 [`input`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/input) 。 某些元素只在一些特殊情况下表现为可替换元素，例如 [`audio`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/audio) 和 [`canvas`](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Element/canvas) 。 通过 CSS [`content`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/content) 属性来插入的对象被称作**匿名可替换元素（***anonymous replaced elements***）**。

CSS在某些情况下会对可替换元素做特殊处理，比如计算外边距和一些auto值。

需要注意的是，一部分（并非全部）可替换元素，本身具有尺寸和基线（baseline），会被像[`vertical-align`](https://developer.mozilla.org/zh-CN/docs/Web/CSS/vertical-align)之类的一些 CSS 属性用到。

