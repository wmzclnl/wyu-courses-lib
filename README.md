# 五邑大学课程资料整理分享库

[![Requirements Status](https://requires.io/github/OpenWyu/wyu-courses-lib/requirements.svg?branch=master)](https://requires.io/github/OpenWyu/wyu-courses-lib/requirements/?branch=master)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/OpenWyu/wyu-courses-lib/Deploy-mkdocs-gh-pages)](https://github.com/OpenWyu/wyu-courses-lib/actions)

[![GitHub repo size](https://img.shields.io/github/repo-size/OpenWyu/wyu-courses-lib)](https://github.com/OpenWyu/wyu-courses-lib)
[![GitHub issues](https://img.shields.io/github/issues/OpenWyu/wyu-courses-lib)](https://github.com/OpenWyu/wyu-courses-lib/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/OpenWyu/wyu-courses-lib)](https://github.com/OpenWyu/wyu-courses-lib/pulls)

[![五邑大学](https://raw.fastgit.org/LengSword/MyPicturesRepo/main/images/wuyi_university.png)](http://www.wyu.edu.cn)

## 前言

**(以下内容部分引用自[QSCTech/zju-icicles](https://github.com/QSCTech/zju-icicles))**

来到一所大学，从第一次接触许多课，直到一门一门完成，这个过程中我们时常收集起许多资料和情报。

有些是需要在网上搜索的电子书，每次见到一门新课程，Google 一下教材名称，有的可以立即找到，有的却是要花费许多眼力；有些是历年试卷或者 A4 纸，前人精心收集制作，抱着能对他人有用的想法公开，却需要在各个群或者 CC98 中摸索以至于从学长手中代代相传；有些是上完一门课才恍然领悟的技巧，原来这门课重点如此，当初本可以更轻松地完成得更好……

我也曾很努力地收集各种课程资料，但到最后，某些重要信息的得到却往往依然是纯属偶然。这种状态时常令我感到后怕与不安。我也曾在课程结束后终于有了些许方法与总结，但这些想法无处诉说，最终只能把花费时间与精力才换来的经验耗散在了漫漫的遗忘之中。

我为这一年一年，这么多人孤军奋战的重复劳动感到不平。

我希望能够将这些隐晦的、不确定的、口口相传的资料和经验，变为公开的、易于获取的和大家能够共同完善、积累的共享资料。

我希望只要是前人走过的弯路，后人就不必再走。这是我的信念，也是我建立这个项目的原因。

## 分享库相关链接

> 为了使分享/下载更为方便,现在所有资源的链接均指向 **FastGit** 镜像加速站
>
> 如果是国内用户,则建议使用以下的 **FastGit** 镜像加速站

- GitHub
    - [资源仓库](https://github.com/OpenWyu/wyu-courses-lib)
    - [在线文档](https://openwyu.github.io/wyu-courses-lib/)
- FastGit
    - [资源仓库](https://hub.fastgit.org/OpenWyu/wyu-courses-lib)

## 贡献

**欢迎贡献!**

**贡献前请一定先仔细阅读[贡献步骤](#贡献步骤)及[贡献规范](#贡献规范)！**

### 贡献步骤

- 一般方法(**推荐做法**)
    1. `Fork` 本项目
    2. 在自己 `Fork` 的项目里, 使用 **GitHub** 网页端点击 **Upload File** 上传文件
    3. 修改完成后,检查一下是否符合 **贡献规范**
    4. 推送到 **GitHub** 上
    5. 向本项目提出 `Pull Request`
    6. 项目负责人进行审核后通过,你所做的更改就合并到本项目了!

- 懒人方法
    - 可以将资料通过各网盘链接形式 **直接附加在 Issue 中**,由维护者进行添加

- 完整方法(**可获取到所有资料, 但拉取耗时会较长**)
    1. `Fork` 本项目
    2. 对自己 `Fork` 的项目进行 `Clone`
    3. 在本地修改完成后,检查一下是否符合 **贡献规范**
    4. 推送到 **GitHub** 上
    5. 向本项目提出 `Pull Request`
    6. 项目负责人进行审核后通过,你所做的更改就合并到本项目了!

**Note: 同时请留意一下项目的文件组织**

### 贡献规范

- 文件夹命名格式(请参考已有示例的格式)
    - **原创或转载** 的笔记放入`笔记`子文件夹
    - 历年考试的试卷放入`试卷`子文件夹
    - 课程设计/实验报告(模板,示例等资料)放入`课程设计`子文件夹
    - 老师布置的习题/作业(以及参考答案)放入`习题`子文件夹
    - 老师发的复习资料放入`复习资料`子文件夹.可进一步细分如下:
        - 课件相关等资料放入`课件`文件夹
    - 网上找的资料放入`网络资源`子文件夹

- 命名问题
    - 文件夹名不应包含小写的圆括号`()`,方括号`[]`,请使用大写括号代替,否则会使文件目录的超链接出错
    - 文件名中最好不要有空格,如果有空格,建议将空格用`-`替换

- 其他建议
    - 同一分类里的文件过多(超过3~5个以上)建议 **压缩打包** 为`rar`或`zip`格式
    - 历年考试的试卷 **最好含有答案,并标明清楚**,否则复习价值较低,建议删减
    - 无用的复习资料请自行判定并做出删减,除非对复习很有用,否则请 **尽量精简**
    - **说明文档** 和 **笔记** 统一使用`markdown`标记语言书写,同时编码统一为`UTF-8`

### 贡献注意

- 不要修改`docs`目录下的文件,该文件夹的文件均由脚本自动生成
- 使用`markdown`的时候,注意该文档系统的`markdown`渲染器对 **无序列表** 的缩进空格为`4`个
- 对于教师的名字为了避免不必要的纠纷,请使用 **姓名拼音首字母缩写**,但为了确定是哪个教师最好加上 **所教班级** 等等信息

## 许可

由贡献者编写部分的许可如下：

[CC-BY-NC-SA：署名-非商业性使用-相同方式共享](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)

其他部分的版权归属于其各自的作者。
