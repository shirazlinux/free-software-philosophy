---
title: Free software licenses
weight: -9
---

The [four freedoms](/learn/four-freedoms/) are generally guaranteed through the
use of a **free software license**. There are many different kinds of licenses
with many different trade-offs to suit each software project's unique situation.

## How a free software license works

A free software license grants the necessary rights, perhaps subject to
some caveats (such as attribution requirements), to establish the four freedoms
for recipients of the software. Any software license can be a free software
license if it upholds the four freedoms, but in practice most projects pick from
one of a few licenses established for general use.

Comments on specific general-purpose software licenses and how to choose between
them for your own projects are addressed in
[choosing a license](/learn/participate/choose-a-license/).

Generally speaking you will encounter a free software license in the "LICENSE"
or "COPYING" file in the software source code. Other projects, particularly
those which pull together source code from many sources, have more intricate
ways of explaining their licensing situation. A common approach to managing this
is the [REUSE specification][0].

[0]: https://reuse.software/

If you want to know more about how free software licenses work in detail, read
on. Otherwise:

{{< button "/learn/participate" "Next: Getting started" "next-button" >}}

## Common traits of free software licenses

To understand your obligations under any particular license, you will have to
read it (and perhaps consult a lawyer, especially if you represent a business).
However, most free software licenses have some traits in common with others, and
you get get a simple understanding of them by learning about a few essential
traits. Here are some common features of free software licenses:

### Attribution

Attribution clauses require you to **attribute** the authors when distributing
or reusing software based on a license with such a clause. This generally
involves reproducing the license in full, or sometimes a simple copyright
notice, when you distribute the software, modifications to it, or new software
which incorporates some or all of the software.

Here's an example from the [MIT license]:

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

[MIT license]: https://mit-license.org

### Disclaimer of warranty

Free software is often provided as a gift. In exchange for this gift, you often
are asked to agree to accept the software as-is, without any particular
expectations of support or warranty from the publisher. This **disclaimer of
warranty** is used to disclaim liability for free software, so the recipient is
responsible for what they do with it.

Here's an example from the [MIT license]:

> THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.

### Use of trademarks and patents

Software licenses generally deal with copyright-related rights, but commercial
software publishers often hold other kinds of intellectual property, namely
trademarks and patents. Free software licenses often incorporate clauses which
address the relationship between the software's copyright grant and other <abbr
title="Intellectual Property">IP</abbr>, for example agreeing that use of the
software does not infringe on the copyright holder's patents, or forbidding the
use of the copyright holder's trademarks.

Here's an example from the [Apache 2.0 license]:

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

[Apache 2.0 license]: https://www.apache.org/licenses/LICENSE-2.0.html

### Copyleft

Some licenses don't just *permit* you to share your improvements, but *require*
you to share your improvements. Such licenses are **copyleft** licenses, and if
you make changes to them you are required to share those changes with others
under the same free-software terms. Copyleft is a tool to protect free software
from being incorporated into non-free works.

Here's an example from the [Mozilla Public License 2.0]:

> All distribution of Covered Software in Source Code Form, including any
> Modifications that You create or to which You contribute, must be under the
> terms of this License. You must inform recipients that the Source Code Form of
> the Covered Software is governed by the terms of this License, and how they
> can obtain a copy of this License. You may not attempt to alter or restrict
> the recipients’ rights in the Source Code Form.

[Mozilla Public License 2.0]: https://www.mozilla.org/en-US/MPL/2.0/

{{< tip >}}
Copyleft is covered in detail in [What is Copyleft?](/learn/copyleft)
{{< /tip >}}

### License compatibility & sublicensing

The ability to combine many works together is an essential trait of the free
software ecosystem, but the use of many different copyright licenses can make
this work more difficult. This is where **sublicensing** and **license
compatibility** comes in: many free software licenses make provisions wherein
they can be extended by the terms of additional licenses. This allows you to
combine software with two or more compatible licenses to produce new software
subject to the license terms of both.

Not all licenses have terms which are compatible with one another; in particular
copyleft licenses tend to be less compatible with others. Software with
incompatible licenses cannot be combined into one work.
