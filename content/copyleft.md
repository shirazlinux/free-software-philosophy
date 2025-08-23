---
title: What is copyleft?
weight: -8
---

**Copyleft** is a licensing tool unique to free software. It is designed to
encourage the proliferation of free software and protect free software from
being incorporated into non-free works. This works by giving you not only the
*right* to share your improvements, but the *obligation* to share your
improvements under the same conditions when the software is distributed. It is
very important to understand these obligations when re-using copyleft software
in your own work.

{{< tip >}}
**Terminology note**:
Conflating "copyleft" and "free software" is a common misconception:
non-copyleft software can be Free Software, and Open Source software can be
copyleft. However, those who identify more closely with the Free Software
movement tend to favor copyleft licenses more than those who identify with the
Open Source movement.
{{< /tip >}}

## The copyleft spectrum

Different free software licenses exist along a spectrum from **permissive** to
**copyleft**, based on the degree to which they emphasize copyleft in their
license terms. Permissive licenses tend to allow generous reuse with relatively
few and non-onerous obligations, such as simple attribution requirements. In
contrast, copyleft licenses impose the obligation to share your changes and
derived works under the same license terms.

<img src="/images/licensing-spectrum.svg" alt="various projects and licenses organized along a spectrum" />
<small>
  Various software licenses and examples of projects which use them, organized
  on the copyleft spectrum. Original graphic by David A Wheeler, <a href="https://creativecommons.org/licenses/by-sa/3.0/">CC BY-SA 3.0</a>.
</small>

## Why choose a copyleft license?

It is common for permissively-licensed free software to be incorporated into
non-free works. This is often done in the name of greater profits by denying the
four freedoms to users who receive the non-free work, making profitable use
of the software without giving anything back to the free software community.

Copyleft licenses address some of these problems:

1. Copyleft promotes the proliferation of free software and the four freedoms by
   ensuring that work built on top of free software grows and benefits the free
   software ecosystem.
2. Copyleft ensures that those who improve or re-use free software share their
   changes with their users, so that the community can benefit from their
   improvements.

Copyleft software can be sold, like all other free software, but requiring that
commercial improvements remain free ensures the four freedoms are upheld by all
participants. Furthermore, it is difficult to change the license of copyleft
software if the copyright is held [in&nbsp;aggregate][0], which serves as a
strong promise for the future of the software as free software.

[0]: /learn/participate/copyright-ownership/

## Weak and strong copyleft

Copyleft licenses differ in how strongly their copyleft clauses affect re-use of
the software. For example, the weak copyleft [Mozilla Public License][MPL] is
*file-based*, such that the copyleft clause covers individual source code files,
and not the project as a whole: you can drop one of these files into any project
without having to relicense the larger project, so long as you distribute any
changes to those specific files under the same license terms.

[MPL]: https://www.mozilla.org/en-US/MPL/2.0/

A somewhat stronger copyleft example is the [GNU Lesser General Public License][LGPL],
which deals specifically with software libraries. These libraries are compiled
into an aggregate software artifact, such as a shared object or static archive,
and the copyleft terms applies to this entire artifact. However, when this is
linked with a third-party program, the copyleft clause is not invoked. Stronger
still is the [GNU General Public License][GPL], which treats the completed
program as the software artifact to which the copyleft clause applies.

[LGPL]: https://www.gnu.org/licenses/lgpl-3.0.en.html
[GPL]: https://www.gnu.org/licenses/gpl-3.0.html

On the far end of the copyleft spectrum are licenses like the [GNU Affero
General Public License][AGPL], which extends the <abbr title="GNU General Public
License">GPL</abbr> to apply to software used over a network, such as databases,
and considers end users of that software "recipients" of the software, who are
thus entitled to receive the source code.

[AGPL]: https://www.gnu.org/licenses/agpl-3.0.html

## How to re-use copyleft works

The simplest way to re-use copyleft works is to apply its license to your own
work and distribute it accordingly.

If you do not want to do this, you can only use a copyleft work under the
conditions permitted by its license, which will likely limit you to the use of
weak copyleft works. For example, if your software depends on a library which
uses the <abbr title="GNU Lesser General Public License">LGPL</abbr>, you may
use any license for your own work but need to share changes you make to the
library itself when you distribute the software to third parties. If the
software uses the GPL or AGPL, you will be more
constrained in your approach. Read the license terms carefully and consult a
lawyer if you are unsure how to proceed.

For more details, consult our page on [re-using free software](/learn/participate/derived-works/).

{{< tip >}}
The [Software Freedom Conservancy][sfc] is an organization which, among other
activities, pursues legal remedies for copyleft enforcement. To learn more about
copyleft enforcement for your own projects, consult their resources.

[sfc]: https://sfconservancy.org/
{{< /tip >}}
