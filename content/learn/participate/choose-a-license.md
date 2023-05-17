---
title: Choosing a license
weight: 3
---

Choosing a license is an important part of publishing your free software
projects. There are many to choose from, and each has different trade-offs and
implications for your project's future. It can be difficult to change the
license later, so you should consider it carefully at the start.

Here are a few widely used free software licenses we recommend, and why you
might choose them.

{{< tip >}}
Once you pick a license, include it when sharing your software. The easiest
way to do this is to copy the plain-text version into a file called "COPYING" in
your source code repository. For more complex scenarios, we recommend the
[REUSE][0] approach.

[0]: https://reuse.software/
{{< /tip >}}

## Copyleft licenses

Copyleft licenses are useful for ensuring that your software remains free. The
use of copyleft requires anyone who makes improvements to your software to
publish them under the same copyleft license, which ensures that you can
incorporate their improvements back into your version. For more details, see
[What is copyleft?](/learn/copyleft/)

{{< block "grid-2" >}}

{{< column "pros" >}}

### Advantages

* Ensures your software remains free
* Encourages community contributions
* Promotes free software generally

{{< /column >}}

{{< column "cons" >}}

### Disadvantages

* Less attractive to businesses
* Must consider license compatibility for reuse

{{< /column >}}

{{< /block >}}

### Recommended copyleft licenses

| License | Use it for... | Copyleft approach |
| --- | --- | --- |
| [Mozilla Public License 2.0] | Libraries (allows <abbr title="The practice of copying library files directly into another project instead of linking them separately">vendoring</abbr>) | File-based |
| [GNU Lesser General Public License] | Libraries (disallows vendoring) | Object-based |
| [GNU General Public License] | Executable programs | Executable-based |
| [GNU Affero General Public License] | Networked services | Network-based |

[Mozilla Public License 2.0]: https://www.mozilla.org/en-US/MPL/2.0/
[GNU Lesser General Public License]: https://www.gnu.org/licenses/lgpl-3.0.en.html
[GNU General Public License]: https://www.gnu.org/licenses/gpl-3.0.html
[GNU Affero General Public License]: https://www.gnu.org/licenses/agpl-3.0.html

## Permissive licenses

Permissive licenses impose relatively few obligations on the receipient of your
software. These licenses permit the software to be freely re-used and integrated
into any other software project, including non-free software. It can be useful
for projects which target commercial use or widespread adoption.

{{< block "grid-2" >}}

{{< column "pros" >}}

### Advantages

* Permits easy re-use
* Encourages widespread adoption
* Attractive to business users

{{< /column >}}

{{< column "cons" >}}

### Disadvantages

* Can be incorporated into non-free works
* Discourages community contributions

{{< /column >}}

{{< /block >}}

### Recommended permissive licenses

We recommend the following permissive licenses:

* [MIT license](https://mit-license.org/)
* [BSD 3-clause license](https://opensource.org/license/bsd-3-clause/)

## Recommended for businesses

For businesses publishing free software, it may be desirable to use a
permissive-style license which includes considerations for trademark and patent
rights. For this purpose we recommend the [Apache 2.0 license].

[Apache 2.0 license]: https://www.apache.org/licenses/LICENSE-2.0.html

## Public domain

Publishers who wish to enter their software into the public domain should note
that a simple public domain dedication is not sufficient for international use.
We recommend the following licenses, which provide public-domain-equivalent
legal rights in a manner compatible with international laws:

* [Creative Commons 0](https://creativecommons.org/share-your-work/public-domain/cc0/)
* [Unlicense](https://unlicense.org/)

## Licenses for other situations

We have a separate page recommending licenses for non-software assets, such as
multimedia:

[Licensing non-software assets](/learn/participate/assets/)
