# ImgGenCN
游戏王卡图生成器，由 https://github.com/moecube/ImgGen 修改而来，对简体中文显示样式作了修改。

YGOPro卡图生成工具
------------------------------------------------
**使用：**
执行目录内放入cards.cdb，并建立pico文件夹放入要制的图。

**样式字体：**

方正隶变_GBK 
MatrixBoldSmallCaps 
文泉驿点阵正黑 
ZhunYuan


**生成卡图：**
在执行目录创建pico目录，放入对应密码的中间图规格的jpg图片，运行ImgGen.exe，即可在picn目录内生成卡图。

普通中间图尺寸：256x256
灵摆中间图尺寸：292x217

**参数：**

自定义数据库
```
ImgGen.exe ..\expansions\pre-release.cdb
```

**配置：** `app.config`

XyzString
自定义Xyz的翻译，默认为超量

FontName
卡图名字字体，默认为方正隶变_GBK

NumFontName
攻守字体：MatrixBoldSmallCaps

TxtFontName
描述字体：文泉驿点阵正黑

LinkFontName
连接字体：ZhunYuan

ZeroStarCards
红龙等没有星星的怪兽卡，用逗号分开

GenerateLarge
生成大图，默认为True

GenerateSmall
生成小图，默认为False

GenerateThumb
生成缩略图，默认为False
