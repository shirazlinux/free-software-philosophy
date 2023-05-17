---
title: Re-using free software
weight: 90
---

One of the great advantages of free software is its potential for re-use. You
can incorporate code from other free software projects into new projects, saving
time and allowing you to build on the shoulders of giants. Of course, you have
to respect the original project's work, and that means complying with their free
software license terms.

{{< tip "warning" >}}
Always read the license carefully when incorporating someone else's work into
your own software.
{{< /tip >}}

## Incorporating permissive software into new works

The main appeal of permissive software licenses is the ability to incorporate it
into anything with relatively little obligation towards the copyright holders.
Most permissive licenses require only that you include the license text, or even
just a copyright statement, in your product. For free software projects which
incorporate permissively licensed code into their work, meeting these
obligations is is usually as straightforward as including an additional license
with your source code.

When incorporating permissively licensed free software into non-free works, you
must distribute the free software license and/or copyright attribution with your
software. Many commercial users of permissively licensed free software include a
menu somewhere in their product which enumerates the applicable software
licenses, or include a printed version with the product. You will need to come
up with a similar approach.

## Incorporating copyleft software into new works

{{< tip "warning" >}}
Copyleft software **cannot** be incorporated into non-free software.
{{< /tip >}}

Most free software can be incorporated into copyleft software, and vice versa,
if the licenses are **compatible**. As a general rule, most popular permissive
licenses -- but not all -- are compatible with most popular copyleft licenses.
*Some* copyleft licenses are compatible with other copyleft licenses (for
instance, the Mozilla Public License 2.0 is compatible with the GNU family of
licenses), but many are not. Any two projects which use the *same* copyleft
license are compatible with each other and may share code freely.

{{< tip >}}
GNU maintains a list of licenses which are compatible and incompatible with the
GPL family of copyleft licenses [here][0].

[0]: https://www.gnu.org/licenses/license-list.html
{{< /tip >}}

Incorporating permissive code into a copyleft project is straightforward if the
licenses are compatible: see the previous section.

{{< tip "warning" >}}
The inverse, incorporating copyleft software into a permissively licensed
software project, is less straightforward. In this case, the combined work
becomes subject to the terms of the copyleft license. Managing a mix of
permissive and copyleft licenses in a single work is possible, but has important
and meaningful implications for your project. This is strongly advised against
for non-experts: don't mix copyleft code into a permissive project unless you
are prepared for the project to [switch to a copyleft
license](/learn/participate/copyright-ownership/#changing-a-projects-license).
{{< /tip >}}

## Managing many licenses and copyrights in one project

Larger and more complex projects may incorporate software from many different
sources with many different licenses and copyright holders. If this describes
your project, we recommend that you consider applying the
[REUSE](https://reuse.software/) specification to your work.
