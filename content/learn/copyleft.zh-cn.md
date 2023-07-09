---
title: 什么是 copyleft?
weight: -8
---

**Copyleft** 是自由软件独特的授权工具。它设计的初衷，是为了促进自由软件的发展，防止自由软件被并入非自由作品之中。它工作的原理，就是在授予你*权利*，让你分享改进的同时，为你附加*义务*，要求你在某些条件下分享这些改进。当你在自己的作品中复用 copyleft 软件的时候，有一点很重要，那就是要理解这些义务。

{{< tip >}}
**术语说明**：将“copyleft”与“自由软件”并用，是很常见的误解：非 copyleft 软件可以是自由软件，而开源软件也可以是 copyleft 的。不过，比起认可开源运动的人，更加认可自由软件运动的人，往往会偏好 copyleft 许可证。
{{< /tip >}}

## Copyleft 光谱

不同的自由软件许可证，依据它们条款中 copyleft 的强度，都落在了一份从**宽松**到 **copyleft** 的光谱之间。宽松型许可证在允许复用方面十分慷慨，它的义务相对较少，也不繁杂，比如说只要求了简单的署名。相比之下，copyleft 许可证会附加这样的义务：要求你在同样的许可证条款下，分享你的改动和衍生作品。

<img src="/images/licensing-spectrum.svg" alt="各种项目及许可证排在一份光谱下" />
<small>
  各种软件许可证，以及使用了这些许可证的项目的例子，排在一份 copyleft 光谱之下。原图作者为 David A Wheeler，CC-BY-SA 3.0.
</small>

## 为何选用一份 copyleft 许可证？

使用了宽松许可证的自由软件，经常会被并入非自由作品之中。这种做法，常常是为了更大的利益，而把收到了非自由作品的用户的四大自由拒之门外。这么一来，这样的软件有了商机，而自由软件社区却得不到回报。

Copyleft 许可证解决了这么一些问题：

1. Copyleft 确保基于自由软件构建的软件，能够发展并惠及自由软件生态，这么一来，它就促进了自由软件及四大自由的增殖。
2. Copyleft 确保那些改进或复用自由软件的人，将自己的改进分享给社区，这么一来，所有用户都能从中受益。

Copyleft 软件，如同其它自由软件，也是可以出售的。但是，因为要求了商业改进也要保持自由，所有接收者也能得到四大自由。此外，如果 copyleft 软件的版权是[聚合而成][0]，那么想要改变许可证也很难，这也保证了软件在未来也是自由软件。

[0]: /learn/participate/copyright-ownership/

## Copyleft 之强弱

不同的 copyleft 许可证，其 copyleft 条款对软件复用的影响程度各不相同。例如，弱 copyleft 的 [Mozilla 公共许可证（Mozilla Public License）][MPL]是*基于文件*的，即 copyleft 条款涵盖的是单独的源代码文件，而不是整个项目：你可以把其中一个文件拿出来丢进其它任何项目，而不必对更大的那个项目进行再许可，只要你对那个特定的文件把改动再发布出来。

[MPL]: https://www.mozilla.org/en-US/MPL/2.0/

更为有力的例子是 [GNU 宽通用公共许可证（GNU Lesser General Public License）][LGPL]，它是专门用来处理软件的库的。这些库被编译成了一个聚合的软件制品，比如说共享对象或者静态归档，而 copyleft 条款适用于整个制品之中。然而，当它与第三方程序相链接时，copyleft 条款不会生效。一样强大的还有 [GNU 通用公共许可证（GNU General Public License）][GPL]，它把整个程序都视为 copyleft 适用的软件制品。

[LGPL]: https://www.gnu.org/licenses/lgpl-3.0.en.html
[GPL]: https://www.gnu.org/licenses/gpl-3.0.html


Copyleft 光谱的远端，有诸如 [GNU Affero 通用公共许可证（GNU Affero General Public License）][AGPL] 的许可证，它延伸了 <abbr title="GNU 通用公共许可证">GPL</abbr>，适用于基于网络使用的软件，比如说数据库。它把那些软件的用户也当成了软件的“接收者”，因此也有权得到源代码。

[AGPL]: https://www.gnu.org/licenses/agpl-3.0.html

## 如何复用 copyleft 作品

复用 copyleft 作品，最简单的方式，就是将它的许可证用于你自己的作品，并相应地分发你的作品。

如果你不想这样做，那你只能在它的许可证允许的条件下使用一份 copyleft 的作品，并且很可能仅限于使用弱 copyleft 的作品。比如说，如果你的软件依赖的库，使用了 <abbr title="GNU 宽通用公共许可证">LGPL</abbr>，那你可以对你自己的作品选用任何许可证，但是需要分享你对这个库本身做出的修改。如果软件使用了 GPL 或者 AGPL，那你就会受到更多约束。请仔细阅读许可证的条款，如果你束手无策，那就要咨询律师了。

了解详情，可以参考我们的[复用自由软件](/learn/participate/derived-works/)页面。

{{< tip >}}
[软件自由保护协会（Software Freedom Conservancy）][sfc]组织，除了一些其它的活动外，还会在 copyleft 执法方面提供法律救济。如果你在自己项目的 copyleft 执法方面想了解更多，可以参考他们的资源。

[sfc]: https://sfconservancy.org/
{{< /tip >}}
