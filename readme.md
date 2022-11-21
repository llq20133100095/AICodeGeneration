在之前我写过自动生成代码的工具Copilot，它是由Github根据大量的仓库代码进行预训练生成的。如果感兴趣可以具体看回我之前写过的文章。里面由包括安装、使用方法等。

由于Copilot已经需要收费，**因此为了找到更加合理（~~免费好用~~）的生成代码工具，帮助我把重复枯燥的代码进行补全。**最近又使用了几个类似的工具，下面是我根据这些工具的一些使用体验。

（PS：更多详细的内容，可以查看这个github网页：）
# 1.可使用的AI生成代码工具

---

| **Name** | **收费情况** | **Tags** | **官方网站** |
| --- | --- | --- | --- |
| Copilot | 收费 | 主要是由Github和OpenAI联合开发的模型框架 | [https://github.com/features/copilot/](https://github.com/features/copilot/) |
| Tabnine | 两渠道：免费 + 收费 | - | [https://www.tabnine.com/](https://www.tabnine.com/) |
| Mutable AI | 免费 | - | [https://mutable.ai/](https://mutable.ai/) |
| cheat.sh | 免费 | - | [https://github.com/chubin/cheat.sh#visual-studio-code](https://github.com/chubin/cheat.sh#visual-studio-code) |
| CodeGeeX | 免费 | 清华大学知识工程实验室开源 | [https://models.aminer.cn/codegeex/](https://models.aminer.cn/codegeex/) |
| CodeWhisperer  | 需要加入waitlist | Amazon发布的对标Copilot竞品 | [https://aws.amazon.com/cn/codewhisperer/](https://aws.amazon.com/cn/codewhisperer/) |
| PanGu-Coder | 还没有内测 | 华为诺亚方舟实验室研发 | - |


# 2.使用教程

---

## 2.1 Copilot
[Copilot安装教程](https://mp.weixin.qq.com/s/_NWWvBDL8f23ymZ0w9Aj8Q)

1. **安装：**在vscode软件中，找到github copilot进行安装即可

![](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668831856316-c657926d-a394-4a06-b6d4-e470d7fe0eca.png#averageHue=%23303b45&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=343&id=ud65e760b&margin=%5Bobject%20Object%5D&originHeight=481&originWidth=631&originalType=url&ratio=1&rotation=0&showTitle=false&status=done&style=none&taskId=u8af70de4-d504-4dbd-a506-5c24f95c5f0&title=&width=450)

2. **使用方法**
> **自动生成**

在python代码自动生成中，只需要输入"**函数名称**" + "**英文描述**"，copilot就可以根据对应的英文描述，给出代码建议：
![](https://cdn.nlark.com/yuque/0/2022/gif/29330410/1668831955232-cc076d44-1815-452c-b945-fabb4cf29148.gif#averageHue=%232f3840&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=372&id=uc0050744&margin=%5Bobject%20Object%5D&originHeight=644&originWidth=1079&originalType=url&ratio=1&rotation=0&showTitle=false&status=done&style=none&taskId=u443fccdb-d175-4a8a-aa58-a4d317e7455&title=&width=623)
如果对上面的代码不满意，copilet还可以利用快捷键进行替换：
![](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668831983883-5a8b78c9-df6d-4fa0-9f2c-67734cc2a0ae.png#averageHue=%23e4c396&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&id=ua6e43b5b&margin=%5Bobject%20Object%5D&originHeight=86&originWidth=508&originalType=url&ratio=1&rotation=0&showTitle=false&status=done&style=none&taskId=ud0705314-7042-479b-acc6-11ac11c053a&title=)
> **得到更详细的意见**

可以通过快捷键 **Ctrl+Enter **来得到copilot的更多详细的辅助编程信息：

![](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668831983949-af66ecdb-81e6-402f-8957-0560ab70064a.png#averageHue=%23202020&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&id=uc3772bce&margin=%5Bobject%20Object%5D&originHeight=464&originWidth=896&originalType=url&ratio=1&rotation=0&showTitle=false&status=done&style=none&taskId=u5b772a43-c4d5-4068-912c-250ed9c49cc&title=)

## 2.2 Tabnine

1. **安装：**在vscode软件中，找到Tabnine进行安装即可

![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668832904366-26ab0d42-1f17-48b2-82ca-5c90ab66187b.png#averageHue=%23282727&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=370&id=uaabbf4d2&margin=%5Bobject%20Object%5D&name=image.png&originHeight=555&originWidth=1201&originalType=binary&ratio=1&rotation=0&showTitle=false&size=93545&status=done&style=none&taskId=u3abe90bd-2867-4318-82e9-f2dc402e476&title=&width=800.6666666666666)

2. **使用方法**

tabnine分为免费版本和收费版本

其中免费版本只能够帮你补全你想要的代码：
![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668838293165-0c2c5ecc-a100-4fe8-bc98-2b3ba3088748.png#averageHue=%23363735&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=92&id=uf7d6e2ac&margin=%5Bobject%20Object%5D&name=image.png&originHeight=138&originWidth=865&originalType=binary&ratio=1&rotation=0&showTitle=false&size=49800&status=done&style=none&taskId=u9b707551-5b16-4a9b-93d9-a977e97578e&title=&width=576.6666666666666)

而付费版本则可以生成更多行代码，且理解你的上下文需求
![动画3.gif](https://cdn.nlark.com/yuque/0/2022/gif/29330410/1669039514259-ec7155b9-2628-4483-8db8-bf1280151d80.gif#averageHue=%232c292f&clientId=u0395f74f-2f1a-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=576&id=ude773d3d&margin=%5Bobject%20Object%5D&name=%E5%8A%A8%E7%94%BB3.gif&originHeight=720&originWidth=1280&originalType=binary&ratio=1&rotation=0&showTitle=false&size=2163331&status=done&style=none&taskId=u043c9043-6f98-42c4-b1af-160a848becb&title=&width=1024)

## 2.3 Mutable AI

1. **安装：**在vscode软件中，找到Mutable AI进行安装

![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668849612299-8a67b1bd-3b37-4811-aaba-bac53d5654d4.png#averageHue=%231f1d1c&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=460&id=ubedb4a9b&margin=%5Bobject%20Object%5D&name=image.png&originHeight=690&originWidth=1228&originalType=binary&ratio=1&rotation=0&showTitle=false&size=158462&status=done&style=none&taskId=ud8f9f665-e4d2-40e0-b51b-4d64139e0d7&title=&width=818.6666666666666)

然后它会提示你，需要在官方网站上获取API key，登录后就可以获取：
![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668850281836-48f4657c-2b9f-4586-9eed-362f8a7c8101.png#averageHue=%23094b70&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=299&id=u78e386f1&margin=%5Bobject%20Object%5D&name=image.png&originHeight=449&originWidth=746&originalType=binary&ratio=1&rotation=0&showTitle=false&size=77214&status=done&style=none&taskId=u24a797df-06c5-4fb3-aa9c-1f84519fbca&title=&width=497.3333333333333)

然后回到vscode上，输入key就可以了

2. **使用方法**
> **给定coding指导**

选择MutableAI：Give a coding instruction
![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668869533242-2eecd117-d308-4f1e-b8b1-7a4def58c13b.png#averageHue=%2307272e&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=660&id=u7ffc6df0&margin=%5Bobject%20Object%5D&name=image.png&originHeight=990&originWidth=1879&originalType=binary&ratio=1&rotation=0&showTitle=false&size=723091&status=done&style=none&taskId=u0bb76c1e-4c1f-4d1d-918e-9984bf1b1e5&title=&width=1252.6666666666667)
输入需要指导的内容：
![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668869620368-81f46f25-05cb-48ca-980e-317db180a7c7.png#averageHue=%2301252e&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=651&id=u88952e0a&margin=%5Bobject%20Object%5D&name=image.png&originHeight=977&originWidth=1881&originalType=binary&ratio=1&rotation=0&showTitle=false&size=146142&status=done&style=none&taskId=ua6992700-6718-4b73-8ee7-674be0f40ec&title=&width=1254)
该插件会生成相应的代码进行参考：
![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668869662363-c5e8aafa-29bd-4768-81df-a5e2c8458c73.png#averageHue=%23123335&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=649&id=u8107ed18&margin=%5Bobject%20Object%5D&name=image.png&originHeight=974&originWidth=1886&originalType=binary&ratio=1&rotation=0&showTitle=false&size=1451724&status=done&style=none&taskId=u5d636fa1-0b5f-4e6c-a147-c4fbd800f20&title=&width=1257.3333333333333)

>  代码补全和生成

![mutableal[00_00_03--00_00_13].gif](https://cdn.nlark.com/yuque/0/2022/gif/29330410/1668869973415-ade3e72e-dc43-4110-9f89-8a59c6d37bbd.gif#averageHue=%2317404e&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=drop&height=281&id=ue6d15837&margin=%5Bobject%20Object%5D&name=mutableal%5B00_00_03--00_00_13%5D.gif&originHeight=210&originWidth=400&originalType=binary&ratio=1&rotation=0&showTitle=false&size=251526&status=done&style=none&taskId=ub2a7971e-f93a-4305-a1c8-1a5d3e091f0&title=&width=534.9923706054688)
> 代码文档生成

![mutableal[00_00_27--00_00_40].gif](https://cdn.nlark.com/yuque/0/2022/gif/29330410/1668869977334-a4198760-59cc-4ebe-b273-0b805a585d87.gif#averageHue=%23a9a7a3&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=drop&height=280&id=ue6aac4a1&margin=%5Bobject%20Object%5D&name=mutableal%5B00_00_27--00_00_40%5D.gif&originHeight=210&originWidth=400&originalType=binary&ratio=1&rotation=0&showTitle=false&size=600712&status=done&style=none&taskId=u9212fa07-73eb-44ef-a5b6-55232dade48&title=&width=533.998046875)

## 2.3 Cheat.sh

1. **安装：**在vscode软件中，找到进行安装Snippet

![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668871178667-7652e875-fe51-4c62-a9b5-2868c9486dcf.png#averageHue=%23212020&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=351&id=u400d7285&margin=%5Bobject%20Object%5D&name=image.png&originHeight=526&originWidth=1337&originalType=binary&ratio=1&rotation=0&showTitle=false&size=62040&status=done&style=none&taskId=u8d97bcf7-252f-471a-aa33-bf1f11d5803&title=&width=891.3333333333334)

2. **使用方法：**

打开命令行，找到snippet输入即可：
![](https://camo.githubusercontent.com/cfaacc425313b23ea65ae974e99b63973d12f887d3f126bd6f2a273c54381de6/68747470733a2f2f63686561742e73682f66696c65732f7673636f64652d736e69707065742d64656d6f2e676966#crop=0&crop=0&crop=1&crop=1&from=url&id=SXWtM&margin=%5Bobject%20Object%5D&originHeight=402&originWidth=583&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)


## 2.4 CodeGeeX

1. **安装：**在vscode软件中，找到进行安装CodeGeeX

![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668871412713-2ff2f8dc-fd89-4ebf-9e32-ad576d8ceace.png#averageHue=%231f1e1e&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=343&id=qZJ5p&margin=%5Bobject%20Object%5D&name=image.png&originHeight=514&originWidth=1257&originalType=binary&ratio=1&rotation=0&showTitle=false&size=77550&status=done&style=none&taskId=u2b26f316-fec6-45ae-a487-1ed391307d8&title=&width=838)

2. **使用方法：**
> **隐匿模式**

在该模式中，CodeGeeX将在您停止输入时，从光标处开始生成（右下角CodeGeeX图标转圈表示正在生成）。生成完毕之后会以灰色显示，按Tab即可插入生成结果。 
[![](https://camo.githubusercontent.com/60d629f1d76409397444632ae9563b81f535c21668ef15dafa95dcce52aece09/68747470733a2f2f6c66732e616d696e65722e636e2f6d6973632f77616e677368616e2f707265747261696e2f636f6465676565782f627562626c655f736f72745f676f2e676966#crop=0&crop=0&crop=1&crop=1&from=url&id=CjOzv&margin=%5Bobject%20Object%5D&originHeight=1484&originWidth=1888&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)](https://camo.githubusercontent.com/60d629f1d76409397444632ae9563b81f535c21668ef15dafa95dcce52aece09/68747470733a2f2f6c66732e616d696e65722e636e2f6d6973632f77616e677368616e2f707265747261696e2f636f6465676565782f627562626c655f736f72745f676f2e676966)

> **交互模式**

在该模式中，按Ctrl+Enter激活交互模式，CodeGeeX将生成X个候选，并显示在右侧窗口中。

> **翻译模式**

在当前的语言的文本编辑器中输入或者粘贴其他语言的代码，您用鼠标选择这些代码，然后按下Ctrl+Alt+T激活翻译模式，您根据提示选择该代码的语言，然后CodeGeeX会帮您把该代码翻译成匹配您当前编辑器语言的代码。点击翻译结果上方的use code即可插入。您还可以在设置中选择您希望插入的时候如何处理被翻译的代码，您可以选择注释它们或者覆盖它们。
![](https://camo.githubusercontent.com/e6e4e432576f3d89b30374dfc5055637136138ce35790842037dd71d454120e1/68747470733a2f2f6c66732e616d696e65722e636e2f6d6973632f77616e677368616e2f707265747261696e2f636f6465676565782f7472616e736c6174696f6e5f6370705f746f5f707974686f6e2e676966#crop=0&crop=0&crop=1&crop=1&from=url&id=HJIQV&margin=%5Bobject%20Object%5D&originHeight=1484&originWidth=1888&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)

> **提示模式（实验功能）**

在该模式中，您可以在输入中添加额外的提示来实现一些有趣的功能，包括并不限于代码解释、概括、以特定风格生成等。该模式的原理是利用了CodeGeeX强大的少样本生成能力。当您在输入中提供一些例子时，CodeGeeX会模仿这些例子并实现相应的功能。**比如，您可以自定义模板中提供一段逐行解释代码的例子。选择您想要解释的代码，按Alt/Option+t触发提示模式，选择您写好的模板（如explanation），CodeGeeX就会解释您输入的代码。**
[![](https://camo.githubusercontent.com/71e90fb2d8740d8a4c0ae37d47749dfd1112bc2bbf51bea2c792c01b0c27739a/68747470733a2f2f6c66732e616d696e65722e636e2f6d6973632f77616e677368616e2f707265747261696e2f636f6465676565782f6578706c616e6174696f6e5f707974686f6e2e676966#crop=0&crop=0&crop=1&crop=1&from=url&id=cFjRg&margin=%5Bobject%20Object%5D&originHeight=1484&originWidth=1888&originalType=binary&ratio=1&rotation=0&showTitle=false&status=done&style=none&title=)](https://camo.githubusercontent.com/71e90fb2d8740d8a4c0ae37d47749dfd1112bc2bbf51bea2c792c01b0c27739a/68747470733a2f2f6c66732e616d696e65722e636e2f6d6973632f77616e677368616e2f707265747261696e2f636f6465676565782f6578706c616e6174696f6e5f707974686f6e2e676966)

## 2.5 CodeWhisperer

1. **安装：**

目前还没有放出面向大众的版本，但是可以去到官网加入waitlist进行内测。
![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668914181734-5cc8f7df-dad3-45a3-a797-b6bf404a5d4e.png#averageHue=%2381c9d7&clientId=uae15ba49-5f8a-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=297&id=u42f00a93&margin=%5Bobject%20Object%5D&name=image.png&originHeight=446&originWidth=616&originalType=binary&ratio=1&rotation=0&showTitle=false&size=79070&status=done&style=none&taskId=ue0849e65-2d67-4d4d-8fff-daa5f9f4375&title=&width=410.6666666666667)

2. **使用方法：**
> **制订现成的代码**

![](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668914284975-a99a624c-fc60-4a11-b186-4a05262196ce.png#averageHue=%2392865c&clientId=uae15ba49-5f8a-4&crop=0&crop=0&crop=1&crop=1&from=paste&id=uf2e43744&margin=%5Bobject%20Object%5D&originHeight=744&originWidth=1428&originalType=url&ratio=1&rotation=0&showTitle=false&status=done&style=none&taskId=u2f8b12c5-ea3e-41e9-b967-ccaf0cd1b3c&title=)

> **检测代码中的漏洞，并给出参考意见**

![](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668914330723-2035c087-084c-4173-ae5a-50dd98cfd362.png#averageHue=%23416341&clientId=uae15ba49-5f8a-4&crop=0&crop=0&crop=1&crop=1&from=paste&id=uc5176ca4&margin=%5Bobject%20Object%5D&originHeight=704&originWidth=1430&originalType=url&ratio=1&rotation=0&showTitle=false&status=done&style=none&taskId=udd68b439-f77e-4e7c-bf6e-45071f3a9c2&title=)


# 3.网友评价

---

**Copilot：**
有网友开始在CF平台发声，呼吁不让把共享代码作为数据进行机器学习：
![](https://cdn.nlark.com/yuque/0/2022/png/29330410/1669038808572-1be64657-d4c1-49e8-8705-2ee7df68f558.png#averageHue=%23f9f8f6&clientId=ua7759e54-17b9-4&crop=0&crop=0&crop=1&crop=1&from=paste&id=u16de698d&margin=%5Bobject%20Object%5D&originHeight=248&originWidth=877&originalType=url&ratio=1&rotation=0&showTitle=false&status=done&style=none&taskId=u72c7e336-f8fb-49e5-8599-0d7eafa622c&title=)
侵害到程序员在GitHub开源共享的精神：
![](https://cdn.nlark.com/yuque/0/2022/png/29330410/1669038819499-eaf9eefd-af2d-44c6-89fc-57f74b1ca86a.png#averageHue=%230b0d0b&clientId=ua7759e54-17b9-4&crop=0&crop=0&crop=1&crop=1&from=paste&id=u0aa776c2&margin=%5Bobject%20Object%5D&originHeight=567&originWidth=793&originalType=url&ratio=1&rotation=0&showTitle=false&status=done&style=none&taskId=u5c70bd21-47ca-406c-b3c8-55473691b23&title=)

**Tabnine**:

![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668837010530-077b16d4-81bf-4030-b492-0640a3236d0b.png#averageHue=%23fefefe&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=203&id=u9da95c66&margin=%5Bobject%20Object%5D&name=image.png&originHeight=200&originWidth=409&originalType=binary&ratio=1&rotation=0&showTitle=false&size=36632&status=done&style=none&taskId=u361e4e0e-89e9-4309-8d86-b60f9cc6ced&title=&width=414.6625061035156)
![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668836995266-476f76a8-fa63-4847-912d-ff45b7dc8e6c.png#averageHue=%23fdfdfc&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=201&id=u3dee1ec6&margin=%5Bobject%20Object%5D&name=image.png&originHeight=201&originWidth=412&originalType=binary&ratio=1&rotation=0&showTitle=false&size=29417&status=done&style=none&taskId=u19ffc983-0df0-4299-8ca5-9c3a062fc11&title=&width=411.6625061035156)
![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668837042149-a2a3d0ee-00f1-4c8d-97a5-81e591a01fa5.png#averageHue=%23fefefe&clientId=u53e2cc64-c498-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=200&id=ud9a80ba4&margin=%5Bobject%20Object%5D&name=image.png&originHeight=200&originWidth=408&originalType=binary&ratio=1&rotation=0&showTitle=false&size=39151&status=done&style=none&taskId=u4e6cd800-bf1d-4db7-a579-f1a7c60d1d8&title=&width=407)

**Mutable AI:**

- 补全代码的参数

![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668935741433-e9b383c5-e32f-4d50-a8b3-2c7aeed0e722.png#averageHue=%23fefefe&clientId=uae15ba49-5f8a-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=206&id=u88c098f6&margin=%5Bobject%20Object%5D&name=image.png&originHeight=309&originWidth=877&originalType=binary&ratio=1&rotation=0&showTitle=false&size=63347&status=done&style=none&taskId=u7e413509-6c23-4f10-977b-1102b3d94f1&title=&width=584.6666666666666)

**Cheat.sh：**
![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1669039011463-ad90d429-6acb-4d20-ba8b-8de6661de077.png#averageHue=%23fdfbfb&clientId=ua7759e54-17b9-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=447&id=u04d01f87&margin=%5Bobject%20Object%5D&name=image.png&originHeight=559&originWidth=737&originalType=binary&ratio=1&rotation=0&showTitle=false&size=120166&status=done&style=none&taskId=u85728ccb-4741-4522-9625-b5c7c8acfa9&title=&width=589.6)
# 4.综合打分
| **Name** | **优点** | **缺点** | **综合打分（最高5星）** |
| --- | --- | --- | --- |
| Copilot | 
- 学生和对github仓库有贡献的开发者，可以免费使用
- 有一定的中文识别能力
- 代码生成功能较完整
- 基于大量的github仓库训练，可以大佬们优秀的代码写法
 | 
- 收费
- 用的是Github仓库的代码进行训练，违法开源免费的标准，面临集体起诉
 | ⭐⭐⭐⭐⭐ |
| Tabnine | 
- 免费版本可以有一定的代码提示功能
- 有较长的代码生成效果
 | 
- 免费版功能较少
- 专业版需要收费
 | ⭐⭐⭐⭐⭐ |
| Mutable AI | 
- 免费
- 可以制定代码文档生成
 | - | ⭐⭐⭐⭐⭐ |
| cheat.sh | 
- 免费
- 支持多种不同的语言
 | - | ⭐⭐⭐ |
| CodeGeeX | 
- 免费
- 支持自定义代码模板
- 支持自己训练模型
 | - | ⭐⭐⭐⭐ |
| CodeWhisperer  | 
- 检测代码中的漏洞，并给出参考意见
 | 
- 需要加入waitlist
 | ⭐⭐⭐ |
| PanGu-Coder | 
- 支持更加复杂的数学计算函数等功能
- 支持中文识别
 | 
- 还没有开始内测，普通开发者不能够使用
 | ⭐⭐⭐⭐ |


# 5.新闻资料（持续更新）

---

## 5.1 Copilot


[试用GitHub Copilot一周后，我给出了3点不建议你使用它的理由](https://zhuanlan.zhihu.com/p/390993810)
## 5.2 tabnine



## 5.3 Mutable AI



## 5.4 CodeGeeX


## 5.5 CodeWhisperer



## 5.6 PanGu-Coder


# 6. 群聊

---

**微信群：可以加入群中进行软件交流**
![image.png](https://cdn.nlark.com/yuque/0/2022/png/29330410/1668915455024-4548ff35-322b-4be5-b743-40e1e636b08c.png#averageHue=%23bcbcbc&clientId=uae15ba49-5f8a-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=704&id=u97c68353&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1319&originWidth=1000&originalType=binary&ratio=1&rotation=0&showTitle=false&size=177197&status=done&style=none&taskId=u6fe32b2e-9d91-4ac3-b4c5-902018e2df0&title=&width=533.6666870117188)

也可以添加我的微信号**llqvigorous**拉你入群
