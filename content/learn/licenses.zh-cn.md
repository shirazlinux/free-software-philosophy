---
title: 自由软件许可证
weight: -9
---

[四大自由](/learn/four-freedoms/)一般是通过一份**自由软件许可证**来授予的。许可证有许多不同的类型，每一个都做出了不同的权衡，从而适应每个软件项目独特的情况。

## 自由软件许可证是如何运作的

自由软件许可证会授予必要的权利，从而为软件的接收者提供四大自由，这种授权可能会有一些条件（例如署名）。任何软件许可证，只要能维持这四大自由，都能成为自由软件许可证。但实际上，有许多流行的许可证是为一般用途而编写的，大多数项目都会从这些许可证中选择一份使用。你可以在[选择一份许可证](/learn/participate/choose-a-license/)部分，了解这些通用的软件许可证，以及如何从中选择一份用于你自己的项目。

你常常可以在软件源代码中的“LICENSE”或者“COPYING”文件中，发现一份自由软件许可证。其它的项目，尤其是那些混合了众多来源的软件的项目，它们会用更加复杂的方式来解释自己的许可情况。用 [REUSE 标准][0]进行管理，是一种常用的方法。

[0]: https://reuse.software/

如果你想详细了解自由软件许可证是如何运作的，请往下读。否则的话：

{{< button "/learn/participate" "下一篇：参与其中" "next-button" >}}

## 自由软件许可证的常见特征

要理解你在特定许可证下的义务，那你就要去读它（可能还要咨询律师，尤其是你代表了企业时）。但是，大多数许可证都有一些共同特征，你可以通过了解一些基础特征，来简单理解这些许可证。以下是一些自由软件许可证的常见特点：

### 署名

署名条款，当你要分发或者复用的软件，它的许可证有这样的条款时，那么这个条款就会要求你为其作者**署名**。这样的要求，通常需要在你分发该软件、其修改部分或者并入了原软件之部分或全部的新软件时，完整复制许可证，或者有时候只需要复制一份简单的版权声明。

以下是一个例子，来自 [MIT license]（MIT 许可证）：

> Permission is hereby granted, free of charge, to any person obtaining a copy of
> this software and associated documentation files (the “Software”), to deal in
> the Software without restriction, including without limitation the rights to
> use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
> the Software, and to permit persons to whom the Software is furnished to do so,
> subject to the following conditions:
> 
> <strong style="color: var(--theme)">The above copyright notice and this permission
> notice shall be included in all copies or substantial portions of the
> Software.</strong>

*译者注：为便于理解，译者为本文的每段许可证选文附上了对应的译文，以供读者参考。这些译文不能代替原许可证使用，译者亦不对中文翻译文本的使用承担任何责任。本文中的所有许可证译文，均以 CC0 发布至公有领域。*

> 特此，为任何获得此软件及其相关文档文件的部分（下称“本软件”）的人，免费授予不受限制地处置本软件的权利，包括但不限于对本软件的使用、修改、合并、发布、分发、分授权和/或售卖其副本的权利，以及向被供以本软件的人授予上述权利的权利，前提是满足以下条件：
>
> <strong style="color: var(--theme)">上述版权声明及本许可证声明应被包含于本软件的所有部分或主要部分之中。</strong>

[MIT license]: https://mit-license.org

### 拒供担保

自由软件常常是作为一份礼物来提供的。为了换取这份礼物，你常常需要同意按原样接受这份软件，而不能期待能从发布者那里得到任何支持或者担保。这个**拒供担保**的声明，用于表示不会提供自由软件的担保，所以接收者要对自己所做的一切负责。

以下是一个例子，来自 [MIT license]（MIT 许可证）：

> THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.

> 本软件“照原样”发布，不附带任何形式的显示或隐式的担保，包括但不限于有经济价值、适合特定用途、无侵权行为的担保。在任何情况下，作者或版权持有人都不对任何索赔、损害或其他责任负责，无论其来自合同的起诉、侵权行为或其他来源，还是产生于、源于或有关于本软件或对其进行的其他处置。

### Copyleft

有一些许可证，不光*允许*你分享改进，还会*要求*你在分享派生自原软件或者将原软件一部分并入其中的软件的时候，对你的改进使用同样的许可证。这就是 **copyleft** 许可证：防止自由软件被并入非自由作品的工具。

以下是一个例子，来自 [Mozilla Public License 2.0]（Mozilla 公共许可证 2.0）：

> All distribution of Covered Software in Source Code Form, including any
> Modifications that You create or to which You contribute, must be under the
> terms of this License. You must inform recipients that the Source Code Form of
> the Covered Software is governed by the terms of this License, and how they
> can obtain a copy of this License. You may not attempt to alter or restrict
> the recipients’ rights in the Source Code Form.

> 涵盖软件的所有源代码形式的分发，包括你所做出或贡献的任何更改，必须以本许可证的条款发布。你必须告知接收者，涵盖软件的源代码形式受本许可证管辖，以及他们可以通过何种方式获取本许可证。你不得试图改变或限制接收者于源代码形式的权利。

[Mozilla Public License 2.0]: https://www.mozilla.org/en-US/MPL/2.0/

{{< tip >}}
[什么是 Copyleft？](/learn/copyleft)部分详细讲解了 copyleft。
{{< /tip >}}

### 许可证兼容性及分许可

将许多作品组合在一起的能力，是自由软件生态系统的一个重要特征。但由于使用了许多不同的版权许可证，实现这一点会更加困难。这时，就有了**分许可（sublicensing）**和**许可证兼容性（license compatibility）**：许多自由软件许可证都有设有条款，允许其被其它许可证的条款扩展。这样你就能组合有着两个或两个以上相互兼容的许可证的软件，并产生新的符合这些许可证条款的软件。

并非所有许可证都有兼容另一个许可证的条款；特别地，copyleft 许可证与其它许可证的兼容性往往更加低。软件如果使用了不兼容的许可证，那就不能合并成一份作品。

{{< tip >}}
你可以在[复用自由软件](/learn/participate/derived-works/)部分详细了解许可证兼容性。
{{< /tip >}}

### 商标和专利使用

软件许可证一般会处理与版权相关的权利，但商业软件的发布者常常持有其它类型的知识产权，例如商标权和专利权。有些自由软件许可证包含了一些条款，专门处理软件的版权授权与其它知识产权之间的关系，例如同意对本软件的使用不会侵犯版权持有人的专利权，或者禁止使用版权持有人的商标。

以下是一个例子，来自 [Apache 2.0 license]（Apache 2.0 许可证）:

> 3. **Grant of Patent License.** Subject to the terms and conditions of this
>    License, each Contributor hereby grants to You a perpetual, worldwide,
>    non-exclusive, no-charge, royalty-free, irrevocable (except as stated in
>    this section) patent license to make, have made, use, offer to sell, sell,
>    import, and otherwise transfer the Work, where such license applies only to
>    those patent claims licensable by such Contributor that are necessarily
>    infringed by their Contribution(s) alone or by combination of their
>    Contribution(s) with the Work to which such Contribution(s) was submitted.
>    If You institute patent litigation against any entity (including a
>    cross-claim or counterclaim in a lawsuit) alleging that the Work or a
>    Contribution incorporated within the Work constitutes direct or
>    contributory patent infringement, then any patent licenses granted to You
>    under this License for that Work shall terminate as of the date such
>    litigation is filed.

> 3. **专利许可的授予** 受限于本许可证的条款和条件，每个贡献者特此授予您永久的、全球性的、非排他性的、免交易费的、免许可费的、不可撤销的（按本节规定的除外）专利许可，以制造、委托制造、使用、许诺销售、销售、进口及以其他方式转移本作品，该许可仅及于贡献者有权许可且由其贡献本身或由其贡献与其提交时所针对的本作品形成的组合所必然侵犯的专利权利要求。如果您对任何实体提起专利诉讼（包括在法律诉讼中的交叉诉讼主张或反诉主张），主张本作品或纳入本作品的贡献构成专利的直接侵权或帮助侵权，则在本许可证下授予您的任何专利许可自该诉讼提起之日起终止。

[Apache 2.0 license]: https://www.apache.org/licenses/LICENSE-2.0.html
