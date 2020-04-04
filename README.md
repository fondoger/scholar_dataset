# CNKI中文论文Meta信息数据集

- 216万中文论文Meta信息数据集: 包含标题、摘要、关键字、被引用数、作者、发表时间、
机构、期刊等信息, 可以参见样例。
- 83万项知网学者公开信息数据集: 包含姓名、从事领域、研究方向、被引用数、G影响指数和H影响指数等信息，可以参见样例。
- 8万项百度百科学者词条数据集: 包含结构化存储的百度百科词条上的文本内容, 可以参见样例。
- 1.4万项知网与百科精确匹配数据集: 针对知网学者和百科学者取交集，并合并双方字段得到的数据集。

数据来源：迫于毕设，想获取中文论文数据集，但网上找寻了一遍
没找到。所以只能自食其力，通过爬虫爬了。爬虫运行了几天几夜，
中途一遍遍处理各种异常case，又担心被封，不敢爬太快，所幸
最终还是爬完了。

**数据集下载**

> 在正式下载前，你可以先看看本Github仓库提供的小样本数据，了解数据格式及内容。

下载地址: https://pan.baidu.com/s/1AwJzfW1Nx-xJkEesIWNUaQ
提取码: 6fb6

**数据样例**

```json
{
    "UrlInfo": null,
    "FileName" : "SYXB201202002",
    "Title" : "常规与非常规油气聚集类型、特征、机理及展望——以中国致密油和致密气为例",
    "Author" : "邹才能;朱如凯;吴松涛;杨智;陶士振;袁选俊;侯连华;杨华;徐春春;李登华;白斌;王岚;",
    "PublishName" : "石油学报",
    "PublishPYName" : "SYXB",
    "Year" : "2012",
    "Period" : "2012年02期",
    "DBName" : "CJFD2012",
    "Type" : "CJFD",
    "Summary" : "油气勘探开发领域从常规油气向非常规油气跨越,是石油工业发展的必然趋势,二者在油气类型、地质特征及聚集机理等方面明显不同。常规油气研究的灵魂是成藏,目标是回答圈闭是否有油气;非常规油气研究的灵魂是储层,目标是回答储集有多少油气。非常规油气主要表现在连续分布、无自然工业产量。目前,常规油气面临非常规的问题,非常规需要发展成新的\"常规\"。伴随技术的进步,非常规可向常规转化。常规油气聚集包括构造油气藏、岩性-地层油气藏,油气以孤立的单体式或较大范围的集群式展布,圈闭界限明显,储集体发育毫米级—微米级孔喉系统,浮力成藏。",
    "Content" : "",
    "Url" : "//wap.cnki.net/touch/web/Journal/Article/SYXB201202002.html",
    "CoverUrl" : "",
    "DbUrl" : "",
    "PublishUrl" : "",
    "SYS_VSM" : "常规油气:3848,非常规油气:3194,页岩系统油气:2976,致密砂岩:2787,圈闭:2594,孔喉:2579,纳米油气:2540,油气聚集:2108,致密砂岩气:2095,储集体:2056,",
    "Keyword" : "常规油气;;非常规油气;;页岩系统油气;;纳米油气;;致密油;;致密气;;页岩气;;页岩油;;连续型油气聚集",
    "ZjCode" : "B;~#@A@#~;",
    "ZtCode" : "A011;B019;",
    "DownloadUrl" : "",
    "Page" : "5-19",
    "PageCount" : "15",
    "Size" : "1318K",
    "ZtChildCode" : "A011_B5;B019_12;",
    "DownloadFlag" : "pdf",
    "DownloadCount" : "18051",
    "QuoteFrequency" : "1168",
    "PublicationTime" : "2012-03-15",
    "Tutor" : "",
    "Catalog" : "",
    "Range" : "",
    "RangeCount" : "",
    "ArticleMark" : "",
    "QKMark" : "",
    "AuthorInstitution" : "中国石油勘探开发研究院;提高石油采收率国家重点实验室;中国石油长庆油田公司;中国石油西南油气田公司;",
    "AuthorInstitutionCode" : "0164466;1000851;0890009;",
    "AuthorCode" : "10603962;10585879;26036574;23387641;10723444;11076337;10677382;20292499;21108635;10725009;21679029;11134166;",
    "FileType" : "EPUBXML;",
    "DiscNo" : "",
    "ErrorCode" : "E0000",
    "ErrorMessage" : "",
    "Priority" : "",
    "UnitCode" : "",
    "CoreCode" : "Y",
    "SCICode" : "",
    "EICode" : "Y",
    "CSSCICode" : "",
    "NetMark" : "",
    "PriorityFileName" : "",
    "Status" : "",
    "StatusContent" : "",
    "AssignType" : "CJFD",
    "ArticleSource" : "石油学报",
    "KeywordCN" : "常规油气;;非常规油气;;页岩系统油气;;纳米油气;;致密油;;致密气;;页岩气;;页岩油;;连续型油气聚集",
    "KeywordJB" : "常规油气;致密砂岩;页岩气;页岩系统油气;油气聚集;致密气;致密油;孔喉;储集体;储层孔;"
}
```

**Copyright**: 仅供学术研究.
