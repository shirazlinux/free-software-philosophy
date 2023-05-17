---
title: Managing copyright ownership
weight: 90
---

The nature of copyright ownership in free software bears clarifying. In the
absence of a Contributor License Agreement or similar document (a practice we
[strongly recommend against][0]), how do free software developers and publishers
manage the legal rights associated with the software's copyright?

[0]: /learn/participate/contribute/#regarding-contributor-license-agreements

## Who owns a free software project?

When you contribute to a free software project, if you do not assign your
copyright to someone else, you retain ownership over the intellectual property
rights associated with your contribution. Your changes are then *licensed* to
everyone else, including the other copyright holders, under the same terms as
the license the project was distributed under in the first place.

As such, in most cases, the copyright for any free software project is held in
aggregate by all of the people who have contributed intellectual property to it,
who license it to users, and each other, with a [free software license][1].

[1]: /learn/licenses/

## Establishing provenance

It may be desirable for some projects, particularly commercial projects, to
formally establish the following for each contribution:

1. The contributor owns the copyright for their contribution, or is authorized
   by the copyright holder to use it
2. The contributor agrees to license their copyright under the terms of the
   project license

If it is desirable for your project to formally establish provenance in this
manner, we recommend the use of the [Developer Certificate of Origin][2]. Most
projects facilitate this by asking authors to "sign-off" on their contributions.
The [Git][3] version control system provides a means of indicating that a given
contribution has been signed-off on with the "[git commit -s][4]" flag.

[2]: https://developercertificate.org/
[3]: https://git-scm.com/
[4]: https://git-scm.com/docs/git-commit#Documentation/git-commit.txt--s

## Changing a project's license

You may at some point wish to change your project's license.

[permissive license]: /learn/participate/choose-a-license/#permissive-licenses
[copyleft license]: /learn/participate/choose-a-license/#copyleft-licenses

If the project is licensed with a [permissive license], generally speaking it
is possible to sublicense the original project with a new license, and applying
the new license to future changes. You will still have to comply with the
original license terms, such as attribution, but future changes may be licensed
under different terms. In this sense, changing the license is similar to
starting a new project and incorporating the original codebase into it.

However, if the project is licensed with a [copyleft license], this is more
difficult -- often impossible. This is an intended trait of copyleft licenses:
it is necessary in order to prevent the project from being incorporated into
non-free software. You cannot generally sublicense a copyleft project in the
same way you can license a permissive project.

It is possible to change the license of a copyleft project, but you must either
<nobr>**(a)** secure the</nobr> permission of all copyright holders, or
<nobr>**(b)** rewrite their contributions</nobr>. This approach is also
appropriate if you want to change a permissive license without being subject to
its original terms (such as attribution), but this is usually not worth the
effort considering the relatively non-onerous terms of permissive licenses.

It is for this reason that holding the copyright in aggregate among the
contributors, rather than assigning copyright to a single entity, is recommended
for copyleft projects: it strengthens the long-term security of the project's
free software status by making it more difficult to change it to a non-free
license.
