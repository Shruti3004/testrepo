# FOSSology UI

[![GPL-2.0](https://img.shields.io/github/license/fossology/fossology)](LICENSE)
[![Travis-CI Build Status](https://travis-ci.org/fossology/fossology.svg?branch=master)](https://travis-ci.org/fossology/fossology)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/2395/badge)](https://bestpractices.coreinfrastructure.org/projects/2395)
[![Coverage Status](https://coveralls.io/repos/github/fossology/fossology/badge.svg?branch=master)](https://coveralls.io/github/fossology/fossology?branch=master)
[![Slack Channel](https://img.shields.io/badge/slack-fossology-blue.svg?longCache=true&logo=slack)](https://join.slack.com/t/fossology/shared_invite/enQtNzI0OTEzMTk0MjYzLTYyZWQxNDc0N2JiZGU2YmI3YmI1NjE4NDVjOGYxMTVjNGY3Y2MzZmM1OGZmMWI5NTRjMzJlNjExZGU2N2I5NGY)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/fossology/fossology)](https://github.com/fossology/fossology/releases/latest)
[![YouTube Channel](https://img.shields.io/badge/youtube-FOSSology-red.svg?&logo=youtube&link=https://www.youtube.com/channel/UCZGPJnQZVnEPQWxOuNamLpw)](https://www.youtube.com/channel/UCZGPJnQZVnEPQWxOuNamLpw)

## About

FOSSology is an open source license compliance software system and toolkit. As a toolkit, you can run license, copyright and export control scans from the command line. As a system, a database and web UI are provided to give you a compliance workflow. In one click you can generate an SPDX file or a ReadMe with all the copyrights notices from your software. FOSSology deduplication means that you can scan an entire distro, rescan a new version, and only the changed files will get rescanned. This is a big time saver for large projects.

[Check out Who Uses FOSSology!](https://www.fossology.org)

FOSSology does not give legal advice.
https://fossology.org/

## Overview

The UI Migration project is an effort focused on generating the new component-based architecture with the integration of the APIs. To make the project more **efficient** and **easily accessible**, an entire code base shift from Symfony-Twig to React.js is proposed. React.js features an incrementally adaptable architecture that focuses on declarative rendering and component composition. React.js component system will enable us to organize the current working APIs appropriately.

## Objectives

- Working on good interactive design, with a modern look.
- Integrating the APIs to the new component-based UI structure.
- Seamless routing and page transitions.
- Giving the power of the node engine to our UI. Making all NPM accessible.
- Writing detailed ​ documentation of the project, to make the
  codebase simpler for other contributors.


## Requirements
NodeJS and NPM<br>
[https://nodejs.org/en/download/](https://nodejs.org/en/download/)


## Installation

In the project directory, you can run:

#### `yarn`
#### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

#### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Support

Mailing lists, FAQs, Release Notes, and other useful info is available
by clicking the documentation tab on the project website. We encourage
all users to join the mailing list and participate in discussions.
There is also a #fossology IRC channel on the freenode IRC network if
you'd like to talk to other FOSSology users and developers.
See [Contact Us](https://www.fossology.org/about/contact/)

## Contributing

We really like contributions in several forms, see [CONTRIBUTING.md](CONTRIBUTING.md)

## Licensing

The original FOSSology source code and associated documentation
including these web pages are Copyright (C) 2007-2012 HP Development
Company, L.P. In the past years, other contributors added source code
and documentation to the project, see the NOTICES file or the referring
files for more information.

Any modifications or additions to source code or documentation
contributed to the FOSSology project are Copyright (C) the contributor,
and should be noted as such in the comments section of the modified file(s).

FOSSology is licensed under [GPL-2.0](https://tldrlegal.com/license/gnu-general-public-license-v2)

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation; version 2 of the License

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License along
    with this program; if not, write to the Free Software Foundation, Inc.,
    51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.

Exception:

All of the FOSSology source code is licensed under the terms of the GNU
General Public License version 2, with the following exceptions:

libfossdb and libfossrepo libraries are licensed under the terms of
the GNU Lesser General Public License version 2.1, [LGPL-2.1](https://tldrlegal.com/license/gnu-lesser-general-public-license-v2.1-(lgpl-2.1)).

    This library is free software; you can redistribute it and/or
    modify it under the terms of the GNU Lesser General Public
    License as published by the Free Software Foundation; either
    version 2.1 of the License.

    This library is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
    Lesser General Public License for more details.

    You should have received a copy of the GNU Lesser General Public
    License along with this library; if not, write to the Free Software
    Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA
    02110-1301  USA

Please see the LICENSE file included with this software for the full texts of
these licenses.
