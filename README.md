# Potato-CV

**注**: 本简历模版参考了[3]的基本元素，但是笔者在实际应聘过程中，发现[3]的排版过于花哨，简单的经历很容易写超出一页，然而实际应届生应聘中简历要求不要超出一页，因此在借用基本元素的前提下，简化了成了本简历模版。（笔者大概是在一年前用[3]的模版的，大家可以翻commit历史的话，会发现当时[3]的作者给出的demo也是两页纸的，这个对于大部分应届生来说是不现实的）。特此声明，谢谢。

土豆简历-尝试简化了一些现成的基于LaTex的简历，制作了这个简洁的，适合于程序员的简历模版，效果如下图所示，基本要素包括了程序员就业面试必要的：

- GitHub
- Blog
- 邮箱和电话等联系方式
- 教育背景，GPA，均分等
- 学术工作
- 项目实习经验
- 获奖情况
- 专业技能以及证书

![tudou][tudou]

# To run this CV

为了能够对这个LaTex CV进行编译，笔者推荐大家下载TexStudio[1]作为编辑器，TexLive[2]作为编译器对整个Latex文档进行编译，直接用TexStudio打开根目录下的`awesome-cv-cn.tex`修改成自己的文本之后，就可以编译并且得到最终的pdf文档。

在开始编译之前，建议设置TexStudio的默认编译器为`xelatex`，具体操作：

options->configure TexStudio->Build->Default Compiler



# 更新日志

**2020.10.15**: 

1. 添加了`\moreme`选项，其可以展示在线简历，比如领英或者`github page`个人页面等，方便展示更为完善的项目和科研经历。
2. 完善了行间距。



# Reference

[1]. http://texstudio.sourceforge.net/

[2]. http://tug.org/texlive/

[3]. https://github.com/huajh/awesome-latex-cv



[tudou]: ./imgs/tudou.png

