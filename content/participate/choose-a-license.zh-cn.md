---
title: 选择一份许可证
weight: 3
---

发布自由软件，重要的一步就是选择一份许可证。可供选择的许可证有很多，且每一份许可证各有不同的权衡，并且都会对你项目未来的发展产生不同的影响。[后续修改许可证]可能会很难，所以你最初就应该慎重考虑。

[后续修改许可证]: /learn/participate/copyright-ownership/#changing-a-projects-license

以下，我们推荐了几个广泛使用的许可证，以及选择它们的理由。

{{< tip >}}
选择好许可证之后，就要在分享软件的时候包含它。最简单的方式，就是把许可证的纯文本版本，复制到源代码仓库中的一个叫 “COPYING” 的文件里。情况更加复杂，则建议使用 [REUSE][0] 的方法。
[0]: https://reuse.software/
{{< /tip >}}

## Copyleft 许可证

Copyleft 许可证可以很有效地确保你的软件能保持自由。使用 copyleft，将要求任何改进了你软件的人，使用同样的 copyleft 许可证来发布其改进，这就保证了你也能将他们的改进并入你的版本。了解更多，参见[什么是 copyleft？](/learn/copyleft/)

{{< block "grid-2" >}}

{{< column "pros" >}}

### 优点

* 确保软件能保持自由
* 鼓励社区提交贡献
* 总体上促进了自由软件

{{< /column >}}

{{< column "cons" >}}

### 缺点

* 对商业的吸引力欠缺
* 复用时必须考虑许可证兼容性

{{< /column >}}

{{< /block >}}

### Copyleft 许可证推荐

| 许可证 | 用于... | Copyleft 方法 |
| --- | --- | --- |
| [Mozilla Public License 2.0] | 库（允许 <abbr title="指直接将库文件复制到另一个项目，而非单独链接它们">vendoring</abbr>） | 基于文件 |
| [GNU Lesser General Public License] | 库（不允许 vendoring） | 基于对象 |
| [GNU General Public License] | 可执行程序 | 基于可执行文件 |
| [GNU Affero General Public License] | 网络服务 | 基于网络 |

[Mozilla Public License 2.0]: https://www.mozilla.org/en-US/MPL/2.0/
[GNU Lesser General Public License]: https://www.gnu.org/licenses/lgpl-3.0.en.html
[GNU General Public License]: https://www.gnu.org/licenses/gpl-3.0.html
[GNU Affero General Public License]: https://www.gnu.org/licenses/agpl-3.0.html

## 宽松型许可证

宽松型许可证对软件接收者附加的义务相对较少。这些许可证允许软件被自由地复用，以及纳入其它任何软件项目之中，包括非自由软件。如果你的项目有商业使用的目标，或者想要被广泛采用，那么这些许可证就很有用。

{{< block "grid-2" >}}

{{< column "pros" >}}

### 优点

* 允许轻松复用
* 促进广泛使用
* 对商业用户有吸引力

{{< /column >}}

{{< column "cons" >}}

### 缺点

* 可并入非自由作品
* 阻碍社区贡献

{{< /column >}}

{{< /block >}}

### 宽松型许可证推荐

我们建议使用以下的宽松型许可证：

* [MIT license](https://mit-license.org/)
* [BSD 3-clause license](https://opensource.org/license/bsd-3-clause/)

## 推荐给企业的许可证

如果企业要发布自由软件，可取的选择是，使用一份宽松型许可证，其考虑了商标和专利权。要这样做的话，我们建议使用 [Apache 2.0 许可证]。

[Apache 2.0 许可证]: https://www.apache.org/licenses/LICENSE-2.0.html

## 公有领域

如果发布者想让自己的软件进入公有领域，那么要注意的是，简单的公有领域贡献不足以国际化使用。我们建议使用以下的许可证，它们提供了等同于公有领域的法定权利，并且与国际法相兼容：

* [Creative Commons 0](https://creativecommons.org/share-your-work/public-domain/cc0/)
* [Unlicense](https://unlicense.org/)

## 用于其它情况的许可证

我们单独写了一页，给非软件的资源（比如多媒体）推荐了一些许可证：

[Licensing non-software assets](/learn/participate/assets/)
