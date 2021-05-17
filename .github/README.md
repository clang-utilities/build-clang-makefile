# Build C-Lang Makefile
[heading__top]:
  #build-clang-makefile
  "&#x2B06; Copies and customizes Makefile script to target path"


Copies and customizes Makefile script to target path


## [![Byte size of Build Clang Makefile][badge__main__build_clang_makefile__source_code]][build_clang_makefile__main__source_code] [![Open Issues][badge__issues__build_clang_makefile]][issues__build_clang_makefile] [![Open Pull Requests][badge__pull_requests__build_clang_makefile]][pull_requests__build_clang_makefile] [![Latest commits][badge__commits__build_clang_makefile__main]][commits__build_clang_makefile__main]


---


- [:arrow_up: Top of Document][heading__top]

- [:building_construction: Requirements][heading__requirements]

- [:zap: Quick Start][heading__quick_start]

- [&#x1F9F0; Usage][heading__usage]

- [&#x1F5D2; Notes][heading__notes]

- [:chart_with_upwards_trend: Contributing][heading__contributing]

  - [:trident: Forking][heading__forking]
  - [:currency_exchange: Sponsor][heading__sponsor]


- [:card_index: Attribution][heading__attribution]

- [:balance_scale: Licensing][heading__license]


---



## Requirements
[heading__requirements]:
  #requirements
  "&#x1F3D7; Prerequisites and/or dependencies that this project needs to function properly"




______


## Quick Start
[heading__quick_start]:
  #quick-start
  "&#9889; Perhaps as easy as one, 2.0,..."


Clone this project...


```Bash
mkdir -vp ~/git/hub/clang-utilities

cd ~/git/hub/clang-utilities

git clone --recurse-submodules git@github.com:clang-utilities/build-clang-makefile.git
```


Install via `make`...


```Bash
cd ~/git/hub/clang-utilities/build-clang-makefile

make install
```


Updates or upgrades are also facilitated via `make` commands...


```Bash
cd ~/git/hub/clang-utilities/build-clang-makefile

make upgrade
```


______


## Usage
[heading__usage]:
  #usage
  "&#x1F9F0; How to utilize this repository"


After installation make a directory for C-Lang new plugin project...


```Bash
mkdir -p ~/git/hub/clang-utilities/project-name
```


Run `build-clang-makefile` script for new project...


```Bash
build-clang-makefile --path ~/git/hub/clang-utilities/project-name\
                     --author "S0AndS0"\
                     --version "0.0.1"
```


Documentation is available via `--help` command-line option...


```Bash
build-clang-makefile --help
```


... or `man` may be used too...


```Bash
man build-clang-makefile
```


______


## Notes
[heading__notes]:
  #notes
  "&#x1F5D2; Additional things to keep in mind when developing"


This repository may not be feature complete and/or fully functional, Pull Requests that add features or fix bugs are certainly welcomed.



______


## Contributing
[heading__contributing]:
  #contributing
  "&#x1F4C8; Options for contributing to build-clang-makefile and clang-utilities"


Options for contributing to build-clang-makefile and clang-utilities


---


### Forking
[heading__forking]:
  #forking
  "&#x1F531; Tips for forking build-clang-makefile"


Start making a [Fork][build_clang_makefile__fork_it] of this repository to an account that you have write permissions for.


- Add remote for fork URL. The URL syntax is _`git@github.com:<NAME>/<REPO>.git`_...


```Bash
cd ~/git/hub/clang-utilities/build-clang-makefile

git remote add fork git@github.com:<NAME>/build-clang-makefile.git
```


- Commit your changes and push to your fork, eg. to fix an issue...


```Bash
cd ~/git/hub/clang-utilities/build-clang-makefile


git commit -F- <<'EOF'
:bug: Fixes #42 Issue


**Edits**


- `<SCRIPT-NAME>` script, fixes some bug reported in issue
EOF


git push fork main
```


> Note, the `-u` option may be used to set `fork` as the default remote, eg. _`git push -u fork main`_ however, this will also default the `fork` remote for pulling from too! Meaning that pulling updates from `origin` must be done explicitly, eg. _`git pull origin main`_


- Then on GitHub submit a Pull Request through the Web-UI, the URL syntax is _`https://github.com/<NAME>/<REPO>/pull/new/<BRANCH>`_


> Note; to decrease the chances of your Pull Request needing modifications before being accepted, please check the [dot-github](https://github.com/clang-utilities/.github) repository for detailed contributing guidelines.


---


### Sponsor
  [heading__sponsor]:
  #sponsor
  "&#x1F4B1; Methods for financially supporting clang-utilities that maintains build-clang-makefile"


Thanks for even considering it!


Via Liberapay you may <sub>[![sponsor__shields_io__liberapay]][sponsor__link__liberapay]</sub> on a repeating basis.


Regardless of if you're able to financially support projects such as build-clang-makefile that clang-utilities maintains, please consider sharing projects that are useful with others, because one of the goals of maintaining Open Source repositories is to provide value to the community.


______


## Attribution
[heading__attribution]:
  #attribution
  "&#x1F4C7; Resources that where helpful in building this project so far."


- [GitHub -- `github-utilities/make-readme`](https://github.com/github-utilities/make-readme)


______


## License
[heading__license]:
  #license
  "&#x2696; Legal side of Open Source"


```
Copies and customizes Makefile script to target path
Copyright (C) 2021 S0AndS0

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, version 3 of the License.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```


For further details review full length version of [AGPL-3.0][branch__current__license] License.



[branch__current__license]:
  /LICENSE
  "&#x2696; Full length version of AGPL-3.0 License"


[badge__commits__build_clang_makefile__main]:
  https://img.shields.io/github/last-commit/clang-utilities/build-clang-makefile/main.svg

[commits__build_clang_makefile__main]:
  https://github.com/clang-utilities/build-clang-makefile/commits/main
  "&#x1F4DD; History of changes on this branch"


[build_clang_makefile__community]:
  https://github.com/clang-utilities/build-clang-makefile/community
  "&#x1F331; Dedicated to functioning code"

[build_clang_makefile__gh_pages]:
  https://github.com/clang-utilities/build-clang-makefile/tree/
  "Source code examples hosted thanks to GitHub Pages!"

[badge__gh_pages__build_clang_makefile]:
  https://img.shields.io/website/https/clang-utilities.github.io/build-clang-makefile/index.html.svg?down_color=darkorange&down_message=Offline&label=Demo&logo=Demo%20Site&up_color=success&up_message=Online

[gh_pages__build_clang_makefile]:
  https://clang-utilities.github.io/build-clang-makefile/index.html
  "&#x1F52C; Check the example collection tests"

[issues__build_clang_makefile]:
  https://github.com/clang-utilities/build-clang-makefile/issues
  "&#x2622; Search for and _bump_ existing issues or open new issues for project maintainer to address."

[build_clang_makefile__fork_it]:
  https://github.com/clang-utilities/build-clang-makefile/
  "&#x1F531; Fork it!"

[pull_requests__build_clang_makefile]:
  https://github.com/clang-utilities/build-clang-makefile/pulls
  "&#x1F3D7; Pull Request friendly, though please check the Community guidelines"

[build_clang_makefile__main__source_code]:
  https://github.com/clang-utilities/build-clang-makefile/
  "&#x2328; Project source!"

[badge__issues__build_clang_makefile]:
  https://img.shields.io/github/issues/clang-utilities/build-clang-makefile.svg

[badge__pull_requests__build_clang_makefile]:
  https://img.shields.io/github/issues-pr/clang-utilities/build-clang-makefile.svg

[badge__main__build_clang_makefile__source_code]:
  https://img.shields.io/github/repo-size/clang-utilities/build-clang-makefile


[sponsor__shields_io__liberapay]:
  https://img.shields.io/static/v1?logo=liberapay&label=Sponsor&message=clang-utilities

[sponsor__link__liberapay]:
  https://liberapay.com/clang-utilities
  "&#x1F4B1; Sponsor developments and projects that clang-utilities maintains via Liberapay"

