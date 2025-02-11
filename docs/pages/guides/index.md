---
layout: page
title: Topical Guides
permalink: /guides/
nav_order: 3
has_children: true
---

The pages here are intended for developers who are making or maintaining a
package and want to follow modern best practices in Python.

New developers are encouraged to read the following pages. Veteran developers
should still check out the [tutorials][], as it has a guide on
recommendations for your `CONTRIBUTING.md`, and at least glance through other
sections.

Following that, there are recommendations for [style][], intended to promote
good practices and to ensure continuity across the packages. There is a
[dedicated page for static type checking with MyPy][mypy]. There is then a guide on
[simple packaging][] or [compiled / complex packaging][packaging], which should help
in ensuring a consistent developer and user experience when working with distribution.

A section on CI follows, with a [general setup guide][gha_basic], and then two
choices for using CI to distribute your package, on for [pure
Python][gha_pure], and one for [compiled extensions][gha_wheels]. You can read
about setting up good tests on the [pytest page][pytest].

Once you have completed the guidelines, there is a [cookiecutter][] project,
[scientific-python/cookie][], that implements these guidelines and lets you setup a
new package from a template in less than 60 seconds!

You can also evaluate your repository against the guidelines by using
[scientific-python-repo-review][]!

[tutorials]: {{ site.baseurl }}{% link pages/tutorials/index.md %}
[style]: {{ site.baseurl }}{% link pages/guides/style.md %}
[mypy]: {{ site.baseurl }}{% link pages/guides/mypy.md %}
[simple packaging]: {{ site.baseurl }}{% link pages/guides/pep621.md %}
[packaging]: {{ site.baseurl }}{% link pages/guides/packaging.md %}
[gha_basic]: {{ site.baseurl }}{% link pages/guides/gha_basic.md %}
[gha_pure]: {{ site.baseurl }}{% link pages/guides/gha_pure.md %}
[gha_wheels]: {{ site.baseurl }}{% link pages/guides/gha_wheels.md %}
[pytest]: {{ site.baseurl }}{% link pages/guides/pytest.md %}
[scientific-python-repo-review]: {{ site.baseurl }}{% link pages/guides/repo_review.md %}

[cookiecutter]: https://cookiecutter.readthedocs.io
[scientific-python/cookie]: https://github.com/scientific-python/cookie
