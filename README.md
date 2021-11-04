# PaperWritingTips

Note（结合以往经验整理，仅供参考）：

关于科技英语写作习惯：

1. 不要使用didn't这样的缩写形式 任何时候都不要用撇号缩写。对于所有格，完全不要用，非要表达类似意思，用of短语。对于引号，要尽力避免。
2. 使用缩写（如模型名、定义等），需在使用的最初始位置定义。
3. 模型名字大小写保持一致，如BERT，ELECTRA，避免Bert，Electra，electra混合使用。
4. 例句、例子考虑用斜体
5. \begin{enumerate}\item改成正常段落可以使页面更紧凑（然后在每段前手工加打黑点$\bullet$），浪费过多空间有被怀疑灌水之嫌
6.  脚注的写法：一般情况下，脚注可以写在“脚注相关的地方后第一个非左标点符号（如左引号、左括号）”后面。\footnote命令和它前面的标点符号之间没有空格。
7. A和an的区别在于发音：**an** LSTM cell, **an** F/H/L/M/N/S/X, **a** U.

关于图片：

1. 图片内部的字体应统一且跟正文文字大小一致。
2. 整张图片两侧尽量不要有空白，保持紧凑。
3. 同类型模块颜色尽可能保持一个色系，每类单元用同一个颜色填充或作为边框。
4. 同样色系，如果某个模块颜色更深更亮 ，代表这个模块更为重要。如果不是想表达更为重要，更为核心，请在各个模块之间保持均衡颜色分配，比如灰度值尽量一致。
5. 不得使用过多的颜色种类，颜色最好不要高于六种。
6. 图片使用矢量图。
7. figure本意是提供比文字更直观、更明了简洁的表达的，应尽可能动用合理的绘画元素，而不是大量用文字标记。figure元素、规范用最小集合、最统一、一致的设置完成，一般不会难看。
8. 细节到线型、配色：第一，保持统一（低描述复杂性），第二，用一个意思、类别的图形元素该用近似、一样的线形、配色（认知直观性）。
9. 箭头方向尽量保持通向，避免出现来回折转。

关于引用：

1. 引用在文字外（parent），使用\cite。引用在文字内（within text），ACL/NAACL/EMNLP模板使用\citet{...}；COLING模板使用\newcite{...}；AAAI/IJCAI模板使用\citeauthor{...} \shortcite{...}；IEEE模版：\citeauthor{...}~(\citeyear{...})

   效果：(Zhang et al. 2020)  vs. Zhang et al. (2020)

2. bib管理注意保持会议/期刊名称全程和缩写一致性，检查年份、卷号、页码等，不要完全依赖scholar提供的信息（可能存在缺失或格式混乱）。

3. 章节、表格、图片使用\label{...}定义后，可通过\ref{...}自动引用跳转。

关于公式：

​	1. 公式为句子的一部分。因此可在公式内部（尤其是多行）加入逗号和句号。对于公式后面的文字，若与公式组成完成的句子，则首字母不需要大写，并紧接在公式后面；若另起新的句子或段落，则在公式结束符\end{equation}后换行，并句子首字母大写，开启新的句子。

投稿前注意事项：

1. 检查匿名性
2. 检查是否超页（最后时刻慎重勿随意改图表大小）
3. 检查标题和摘要与投稿系统填写框内的信息是否对应。

附录处理：

1. 注意匿名性，尤其是code里面一些hard coded模型或数据路径等需要处理掉。

其他阅读材料：

[如何优雅地（用TeX）写AI论文](https://zhuanlan.zhihu.com/p/103519006?utm_source=wechat_session&utm_medium=social&utm_oi=37609443164160&utm_content=sec)

[浅谈学术论文rebuttal](https://zhuanlan.zhihu.com/p/104298923)

[如何ensemble多个神经网络？](https://www.zhihu.com/question/60753512)

[NLP领域，你推荐哪些综述性的文章？](https://www.zhihu.com/question/355125622/answer/890666561?utm_source=wechat_session&utm_medium=social&utm_oi=37609443164160&utm_content=sec)

