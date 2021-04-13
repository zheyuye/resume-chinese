# resume-chinese
中文LaTeX简历模板

主要参考：

- [billryan/resume](https://github.com/billryan/resume)
- [WonderCV 学生求职模板](https://www.wondercv.com/zh-CN/resume_templates)
- [Htallone/myCV](https://github.com/Htallone/myCV)
- [hijiangtao/resume](https://github.com/hijiangtao/resume)

LaTex语法内容以及框架基本上参照[Htallone/myCV](https://github.com/Htallone/myCV), 宏主要参照[hijiangtao/resume](https://github.com/hijiangtao/resume), 集各家之所长后做了些小修改, 方便直接从overleaf编译. 

### 使用步骤

1. Download ZIP
2. Overleaf -> New Project -> Upload Project
3. Do your own editing
4. 选择complier为`XeLaTeX`

或者

0. 直接使用[Overleaf模板](https://www.overleaf.com/latex/templates/resume-chinese/vbrmnfrgbscv), 开始你的编辑



P.S. Overleaf Link还未能及时更新

###  宏(newcommand)

- `\name`: 姓名
- `\contactInfo`{邮箱}{手机号}{个人主页}`: 个人信息三元组
- `\basicContactInfo`{邮箱}{手机号}: 个人信息两元组, 没有个人主页的可以用这个
- `\logosection{fontawesome command}{小节}`: 用于分节, 如教育背景, 实习项目经历等
- `\dateRange{起始日期}{终止日期}`: 时间区间, 其中使用了特殊对齐策略, 便于在`终止日期`处填写**至今**
- `\datedline{内容}{日期}`: 第二项自动右对齐, 广泛使用于简历中, 嵌套`\dateRange`使用效果更佳
- `\biInfo{}{}`: 两元组信息填充, 以`\quad`分割
- `tripleInfo{}{}{}`: 三元组信息填充, 以`\quad`分割
- `\itemize`: 清单列表，简历中应用最广
- `\enumerate`: 枚举列表，数字标号


### 效果示例

**纯享版:**

![resume](https://zheyuye-image-1257819557.cos.ap-shanghai.myqcloud.com/img/resume.png)


**照片版:**

页眉个人照片+学校logo:

![head](https://zheyuye-image-1257819557.cos.ap-shanghai.myqcloud.com/img/image-20210408152658206.png)

页脚个人信息:

![footer](https://zheyuye-image-1257819557.cos.ap-shanghai.myqcloud.com/img/image-20210408152718217.png)
