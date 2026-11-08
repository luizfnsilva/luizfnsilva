# Luiz F. Nunes da Silva

Release engineering and reproducibility. When I find a release whose tag and code disagree in a
project I use, I report it with the commits that show it.

## Open source contributions

| project | what | status |
|---|---|---|
| [pypa/setuptools-scm#1568](https://github.com/pypa/setuptools-scm/issues/1568) | `v1.0` and `1.0` on different commits build the same version without a warning | wontfix; docs note asked for |
| [pypa/setuptools-scm#1569](https://github.com/pypa/setuptools-scm/pull/1569) | docs: two tags that give the same version | open |
| [ofek/hatch-vcs#115](https://github.com/ofek/hatch-vcs/pull/115) | docs: `tag-pattern` default linked to the current setuptools-scm docs | open |
| [mrabarnett/mrab-regex#624](https://github.com/mrabarnett/mrab-regex/pull/624) | CI: check that the tag matches the version before publishing | open |
| [smallvec/smallvec#852](https://github.com/smallvec/smallvec/issues/852) | tags `v1.16.0` and `v2.0.0-alpha.13` point before the version bump; crates.io records other commits | closed: old tags kept, future releases tagged on the published commit |
| [pytest-dev/pytest-timeout#217](https://github.com/pytest-dev/pytest-timeout/pull/217) | Release: check that the tag matches the version in setup.cfg (2.5.0 was tagged before the bump) | open |
