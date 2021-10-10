# GMCM_LaTeX
华为杯数学建模LaTeX模版（重整版）



感谢两位前辈，分别是https://github.com/zhanwen/MathModel

和https://mp.weixin.qq.com/s/i1Bk1wvn9mPXPnEpdockPQ提供的LaTeX模版。



本弟弟🧍‍♂️重新整理了一下。

分成

1. 附录代码部分
2. 页面设置部分
3. 图表部分（按照章节顺序重新编码）
4. 封面 摘要 目录部分
5. 字体设置部分

主要改动在字体设置部分。

```latex
\setmainfont{Times New Roman}
\setmonofont{Courier New}
\setsansfont{Arial}

\setCJKmainfont[AutoFakeBold = {2.15},ItalicFont={KaiTi}]{SimSun.ttf}
\setCJKfamilyfont{zhkai}[AutoFakeBold=2.15]{KaiTi.ttf}
\setCJKsansfont[AutoFakeBold=2.15]{SimHei.ttf}
\setCJKfamilyfont{zhsong}[AutoFakeBold=2.15]{SimSun.ttf}
\setCJKfamilyfont{zhhei}[AutoFakeBold=2.15]{SimHei.ttf}
\setCJKfamilyfont{zhli}{LiSu.ttf}
\newcommand*{\lishu}{\CJKfamily{zhli}}
```

凭着经验和不断地调试，这是比较美观的字体设置。并且这种方法是跨平台的，无论你在哪一个设备上都会渲染出一样的效果。





### 解释一下

Overleaf 的中文字体，主要是 Fandol 和思源。

因此模版里的隶书（摘要），宋体（正文），黑体（标题）都没有。

同理，Mac也没有。



因此。

本项目上传了这三个字体。



如何使用？

对于overleaf，直接把字体和样式（cls文件）放到项目文件里，然后，将字体那块部分添加后缀.ttf即可。

> 参考
> Overleaf中怎么使用自己的中文字体? - 耀出千份光的回答 - 知乎 https://www.zhihu.com/question/294518505/answer/2105363555



对于本地运行（mac）也可以按照方法一，或者直接安装即可。











