# Go 语言编程之旅：一起用 Go 做项目

本书涵盖 Go 语言的各大经典实战，直接介绍 Go 语言的语法基础，内容将面向项目实践，同时会针对核心细节进行分析。而在实际项目迭代中，常常会出现或多或少的事故，因此本书也针对 Go 语言的大杀器（分析工具）以及常见问题进行了全面讲解。

本书适合已经大致学习了 Go 语言的基础语法后，想要跨越到下一个阶段的开发人员，可以填补该阶段的空白和进一步拓展你的思维方向。

![image](https://image.eddycjy.com/04737f7b3e5567224fd2bc93f352203d.jpeg)

- 作者：陈剑煜（煎鱼），GitHub：[@eddycjy](https://github.com/eddycjy)，微信公众号：脑子进煎鱼了。
- 作者：徐新华（polaris），GitHub：[@polaris](https://github.com/polaris1119)，微信公众号：Go语言中文网。

## 购买链接

- 京东：https://item.jd.com/12685249.html
- 当当：http://product.dangdang.com/28982027.html
- 天猫：https://detail.tmall.com/item.htm?id=622185710833

## 碰撞专区

本书是偏向项目实践类的书籍，因此或多或少你都会遇到一些问题或不解，在此我欢迎已购书的读者随时与我们进行沟通和交流，做到效益最大化。因此有专门的读者群和星球作为长期维护，而如果有遇到问题，也欢迎在下方的问题区进行反馈或修正。

### 问题

- [提交问题](https://github.com/go-programming-tour-book/book/issues/new)

### 交流

![image](https://image.eddycjy.com/5477850f13e9b404491f379102dafb60.jpg)

## 本书内容

本书针对常见的项目类型，主要细分为 5 + 1 板块，分别是命令行、HTTP、RPC、Websocket 应用、进程内缓存以及 Go 语言中的大杀器。

同时我们在项目开发、细节分析、运行时分析等方方面面都进行了较深入的介绍和说明，能够为 Go 语言开发者提供相对完整的项目实践经验，而如果深入阅读第六章的章节，更能够为未来各类问题出现时的问题排查提供一份强大的知识板块。

如下为本书的思维导图概览：

![image](https://image.eddycjy.com/e5eafb17140fdc06830b838eb7fb0468.png)

## 关于本书的想法

实际上写面向实践类的图书是一个比较大的考验，因为不管是章节篇幅、叙事顺序和结构以及代码的结构性，只要其中一点做的不好，就会影响读者阅读此书时的知识领域、感官，因此为了更贴合现实中的实践，针对本书我们划分为了如下三个方向：

![image](https://image.eddycjy.com/65e1e9cbfd14617fd054970e3d474e64.png)

笔者认为 “实践”，大体就是三个方向，分别是 “做、学、排”，做好你需要的项目，学习优秀的开源/私有项目，并据此不断精进你所负责的项目。而既然是企业项目，那么在长期的迭代中一定会遇到或大或小的事故，因此知道如何排查和分析问题就显得非常重要。

同时这里还有一个隐藏的方向，那就是归纳总结，你做好项目、学习了优秀项目，排查和分析问题后，都应当进行对所学知识的审读，将你的思维聚拢并归纳记录下来，这也是为什么我们会在章节中会有 “小结” 的原因。

## 如何阅读这本书

常规的列目录未免太无趣。我想不如说说从我个人的角度，所看到读者们在近 3 年来是如何阅读/实践我的实践系列文章的，其面向的读者群体是完全一致的。希望能够从另外一个角度告诉你，应当如何阅读这本书，尽可能的效益最大化。

首先，图书，买来要读，而与实战结合的图书，势必需要实践，实践最常见又分为脑内思考和上机实践：

![image](https://image.eddycjy.com/a6faa89061d62be755b715607e2563b8.jpg)

而在持续的交流中，可以发现至少会延伸出以下几类深入层次的不同：

![image](https://image.eddycjy.com/e3b17b0867e66bda4b5c6fb24ddcebc9.jpg)

- **第一层**：只阅读，留有印象，需要时再唤醒，也行。

- **第二层**：阅读并实践，实打实的完成项目实践，收获丰满。

- **第三层**：实践的过程中，**一定会遇到或大或小的问题**，有的人会放弃，这就是分叉点。但有的读者会持续排查，其提升了个人能力（排错能力很重要）。

- **第四层**：实践完毕后，有自己的想法，认为某某地方还可以这样，也可以再实现更多的功能，举一反三，进一步拓展，并对项目提 issues 或进行 pr。

- **第五层**：完成整体项目后，抽离业务代码，标准化框架，实现框架的应用脚手架，并有的读者会进一步开源。

- **第六层**：形成脚手架后，在自己业务组开始落地，实际在项目中使用，由业务学习转化为企业实践。

- **第七层**：在内部落地实践稳妥后，开始在其它业务组开始推广该框架脚手架，进一步标准化，拓展思路。

通过上图中 “七层金字塔” 的理解，我们不难发现其对于实践项目的理解和应用已经不再是单单这个项目，而是有了更深远的意义，抽象一下，对照着著名的 “学习效率金字塔” 来看：

![image](https://image.eddycjy.com/a35394d0ab562efaac8367c3eeff4b07.jpg)

在单纯的 “阅读” 时，其基本处于 “被动学习” 的阶段，而单进入阅读并实践时，已经转为了 “主动学习”，且绝大部分的读者做完实践后，表示 “嗯，实践完，挺好的，有所得”。

这时候就会进入到一个新的阶段（分叉点），绝大部分读者在做完后，会纠结 ”接下来要做什么“：

![image](https://image.eddycjy.com/16c678d883fe3b4e1db5fa99dfd0b302.jpg)

有部分读者会停滞，也有部分读者会转入 “转教别人/立即应用” 的阶段，也就是普遍的在企业内部进行标准化的使用，又或是开源项目，据此得到更一步的深入实践和提高，更大的吸收差距也在于此。

当然，这一切都要基于前面的 “1”，你得先买了书，读了书，接着就是你的选择和创建机遇的能力了，不同的路线效益自然不一样。

## 为什么要写这本书

在数年前，我司开始尝试进行技术栈的转型，当时我运气很好，恰好被抽调到了新业务的突破组，因此需要负责相关技术推进，但是当时网上并没有成体系成结构化的教材，因此我写了一些中文连载系列，希望借此将知识分享给广大的 Go 语言爱好者。

而回到 2020 年，我观察到这几年 Go 语言的火热程度不断上升，Go 语言相关的图书也越来越多，几乎方方面面的领域都已经涉及到了，但依然没有出现相对完整的项目实践类别的图书，因此我决定再次行动起来，希望将这一块的知识更体系更呈结构化的分享给大家。

## 社区支持

如果有任何疑问，欢迎通过各种方式联系到本书作者，我一定会回复你，并且我们还建立了官方网站 go-programming.cn 和相应的知识星球，我们会对本书进行长期维护，也希望这一个平台，能够给你带来更大的思维拓展和认识到更多的志同道合的朋友。

另外，我们只是喜欢分享的普通 Go 语言爱好者，技术水平有限，如果你发现任何疑似问题或错误，不要迟疑，马上联系我们，我们会进行处理。

## 版权声明

本图书所有文章采用 [知识署名-非商业性使用-禁止演绎 4.0 国际](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh) 进行许可。

## 致谢

感谢徐新华（polaris）和在 Go 语言社区中的爱好者们，如果没有你们的鼓励，这本书不可能出版。最后感谢为本书牺牲了大量业余时间进行 Review 的朋友们：

- [盛傲飞（aofei）](https://github.com/aofei)
- [石太彬（shitaibin）](https://github.com/shitaibin)
- [曾晓东（teroy）](https://github.com/teroy)
