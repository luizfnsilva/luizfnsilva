# Luiz F. Nunes da Silva

Release engineering and reproducibility. When I find a release whose tag and code disagree in a
project I use, I report it with the commits that show it.

## Open source contributions

| project | what | status |
|---|---|---|
| [ossf/wg-supply-chain-integrity#97](https://github.com/ossf/wg-supply-chain-integrity/issues/97) | feedback request: where a tag/declared-version consistency check belongs among supply-chain controls | open |
| [Comfy-Org/ComfyUI#17616](https://github.com/Comfy-Org/ComfyUI/issues/17616) | the `v0.14.2` Windows portable package declares `0.14.1` (checked inside the published archive); `v0.18.3` and `v0.20.2` the same | open |
| [smallvec/smallvec#852](https://github.com/smallvec/smallvec/issues/852) | tags `v1.16.0` and `v2.0.0-alpha.13` point before the version bump; crates.io records other commits | closed: old tags kept, future releases tagged on the published commit |
| [pytest-dev/pytest-timeout#217](https://github.com/pytest-dev/pytest-timeout/pull/217) | release workflow: check that the tag matches the version in `setup.cfg` (2.5.0 was tagged before the bump) | open, in discussion |
| [pypa/setuptools-scm#1569](https://github.com/pypa/setuptools-scm/pull/1569) | docs: two tags that give the same version | merged |
| [pypa/setuptools-scm#1568](https://github.com/pypa/setuptools-scm/issues/1568) | `v1.0` and `1.0` on different commits build the same version without a warning | wontfix; docs note added (#1569, merged) |
| [mrabarnett/mrab-regex#624](https://github.com/mrabarnett/mrab-regex/pull/624) | CI: check that the tag matches the version before publishing | open |
| [ofek/hatch-vcs#115](https://github.com/ofek/hatch-vcs/pull/115) | docs: `tag-pattern` default linked to the current setuptools-scm docs | open |
| [tyki6/MyJWT#154](https://github.com/tyki6/MyJWT/issues/154) | tag `2.1.0` declares version `2.0.0` in `pyproject.toml` | open |
| [dfurtado/dataclass-csv#77](https://github.com/dfurtado/dataclass-csv/issues/77) | tag `1.4.1` points to a commit that declares `1.4.0` | open |
| [fillipe-gsm/python-tsp#73](https://github.com/fillipe-gsm/python-tsp/issues/73) | tag `v0.5.0` points to a commit that declares `0.4.2` | open |
| [strawberry-graphql/strawberry#4808](https://github.com/strawberry-graphql/strawberry/discussions/4808) | discussion: a read-only tag/version check in the release workflow | open |
| [strawberry-graphql/strawberry-django#993](https://github.com/strawberry-graphql/strawberry-django/issues/993) | question: a read-only tag/version check in the release workflow | open |
| [usecross/cross-web#22](https://github.com/usecross/cross-web/issues/22) | question: a read-only tag/version check in the release workflow | open |
