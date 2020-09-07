### [Documentation on GitHub Pages](https://rapydo.github.io/docs)

### A brief summary of all RAPyDO repositories:

| Project | Version | Quality | Tests | Coverage |
| --- | --- | --- | --- | --- |
| [controller](https://github.com/rapydo/do) | [![PyPI version](https://badge.fury.io/py/rapydo-controller.svg)](https://badge.fury.io/py/rapydo-controller) | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/0668957ee3a04608887b2e9a7fdea198)](https://www.codacy.com/gh/rapydo/do?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=rapydo/do&amp;utm_campaign=Badge_Grade) | [![Build Status](https://travis-ci.com/rapydo/do.svg?branch=0.8)](https://travis-ci.com/rapydo/do) | [![codecov](https://codecov.io/gh/rapydo/do/branch/0.8/graph/badge.svg)](https://codecov.io/gh/rapydo/do) |
| [http-api](https://github.com/rapydo/http-api) | [![PyPI version](https://badge.fury.io/py/rapydo-http.svg)](https://badge.fury.io/py/rapydo-http) | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/7fb33f343d824eaeb323672545ad9cca)](https://www.codacy.com/gh/rapydo/http-api?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=rapydo/http-api&amp;utm_campaign=Badge_Grade) | [![Build Status](https://travis-ci.com/rapydo/http-api.svg?branch=0.8)](https://travis-ci.com/rapydo/http-api) | [![codecov](https://codecov.io/gh/rapydo/http-api/branch/0.8/graph/badge.svg)](https://codecov.io/gh/rapydo/http-api) |
| [angular](https://github.com/rapydo/rapydo-angular) | [![GitHub version](https://img.shields.io/github/tag/rapydo/rapydo-angular.svg)](https://github.com/rapydo/rapydo-angular/releases) | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/1e839e6b61d4465088989d068c0fcafe)](https://www.codacy.com/gh/rapydo/rapydo-angular?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=rapydo/rapydo-angular&amp;utm_campaign=Badge_Grade) | [![Build Status](https://travis-ci.com/rapydo/rapydo-angular.svg?branch=0.8)](https://travis-ci.com/rapydo/rapydo-angular) | [![codecov](https://codecov.io/gh/rapydo/rapydo-angular/branch/0.8/graph/badge.svg)](https://codecov.io/gh/rapydo/rapydo-angular) |
| [build templates](https://github.com/rapydo/build-templates) | [![GitHub version](https://img.shields.io/github/tag/rapydo/build-templates.svg)](https://github.com/rapydo/build-templates/releases) | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/985f3eb2469f4e3dbb84edf64d354c47)](https://www.codacy.com/gh/rapydo/build-templates?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=rapydo/build-templates&amp;utm_campaign=Badge_Grade) | [![Build Status](https://travis-ci.com/rapydo/build-templates.svg?branch=0.8)](https://travis-ci.com/rapydo/build-templates) |  |


[![PyPI](https://img.shields.io/pypi/l/rapydo-controller.svg)](https://github.com/rapydo/core/blob/master/LICENSE)


## Versions

| Version | Release date | Status | Major changes |
| --- | --- | --- | --- |
| **0.8** | *Nov 2020* | *Under development* | Controller package renamed (rapydo-controller -> rapydo); Dropped support for _METHOD dictionaries; Ajv frontend validation |
| **0.7.6** | 04 Sep 2020 | **Supported** | @decorators.endpoint; Angular10; Cypress 5; Webargs 6; Profile edit; |
| **0.7.5** | 17 Aug 2020 | **Supported** | Stats endpoint; Ubuntu 20.04; Dropped irods; Dropped py35; Typer; rapydo backup; |
| **0.7.4** | 09 Jul 2020 | **Supported** | Gunicorn; Flask-Apispec; Dropped AngularJS; Cypress; |
| 0.7.3 | 16 May 2020 | Discontinued | Dropped rapydo-confs repo; Unwrapped responses; Angular 9; rapydo create; |
| 0.7.2 | 21 Mar 2020 | Discontinued | Dropped py34; |
| **0.7.1** | 19 Jan 2020 | **Supported** | Dropped utils repo|
| 0.7.0 | 25 Nov 2019 | Discontinued | Angular CLI; Dropped swagger yamls |
| **0.6.7** | 23 Sep 2019 | **Partially supported** | Angular 8; Celery-beat |
| 0.6.6 | 28 Jun 2019 | Discontinued | |
| 0.6.5 | 19 Apr 2019 | Discontinued | Angular 7; rapydo install auto;|
| 0.6.4 | 11 Feb 2019 | Discontinued | |
| 0.6.3 | 06 Dec 2018 | Discontinued | |
| 0.6.2 | 30 Jul 2018 | Discontinued | Angular 5; |
| 0.6.1 | 26 Apr 2018 | Discontinued | |
| 0.6.0 | 17 Jan 2018 | Discontinued | |
| 0.5.7 | 03 Nov 2017 | Discontinued | |
| 0.5.6 | 24 Oct 2017 | Discontinued | |
| 0.5.5 | 25 Sep 2017 | Discontinued | |
| 0.5.4 | 12 Sep 2017 | Discontinued | |
| 0.5.3 | 1 Aug 2017 | Discontinued | |
| 0.5.2 | 28 Jul 2017 | Discontinued | |
| 0.5.1 | 18 Jul 2017 | Discontinued | |
| 0.5.0 | 14 Jul 2017 | Discontinued | |

| Version | Controller | HTTP-API | Build templates | Rapydo-Angular |
| --- | --- | --- | --- | --- |
| 0.8 | [![Build Status](https://travis-ci.com/rapydo/do.svg?branch=0.8)](https://travis-ci.com/rapydo/do/branches) | [![Build Status](https://travis-ci.com/rapydo/http-api.svg?branch=0.8)](https://travis-ci.com/rapydo/http-api/branches) | [![Build Status](https://travis-ci.com/rapydo/build-templates.svg?branch=0.8)](https://travis-ci.com/rapydo/build-templates/branches) | [![Build Status](https://travis-ci.com/rapydo/rapydo-angular.svg?branch=0.8)](https://travis-ci.com/rapydo/rapydo-angular/branches) |
| 0.7.6 | [![Build Status](https://travis-ci.com/rapydo/do.svg?branch=0.7.6)](https://travis-ci.com/rapydo/do/branches) | [![Build Status](https://travis-ci.com/rapydo/http-api.svg?branch=0.7.6)](https://travis-ci.com/rapydo/http-api/branches) | [![Build Status](https://travis-ci.com/rapydo/build-templates.svg?branch=0.7.6)](https://travis-ci.com/rapydo/build-templates/branches) | [![Build Status](https://travis-ci.com/rapydo/rapydo-angular.svg?branch=0.7.6)](https://travis-ci.com/rapydo/rapydo-angular/branches) |
| 0.7.5 | [![Build Status](https://travis-ci.com/rapydo/do.svg?branch=0.7.5)](https://travis-ci.com/rapydo/do/branches) | [![Build Status](https://travis-ci.com/rapydo/http-api.svg?branch=0.7.5)](https://travis-ci.com/rapydo/http-api/branches) | [![Build Status](https://travis-ci.com/rapydo/build-templates.svg?branch=0.7.5)](https://travis-ci.com/rapydo/build-templates/branches) | [![Build Status](https://travis-ci.com/rapydo/rapydo-angular.svg?branch=0.7.5)](https://travis-ci.com/rapydo/rapydo-angular/branches) |
| 0.7.4 | [![Build Status](https://travis-ci.com/rapydo/do.svg?branch=0.7.4)](https://travis-ci.com/rapydo/do/branches) | [![Build Status](https://travis-ci.com/rapydo/http-api.svg?branch=0.7.4)](https://travis-ci.com/rapydo/http-api/branches) | [![Build Status](https://travis-ci.com/rapydo/build-templates.svg?branch=0.7.4)](https://travis-ci.com/rapydo/build-templates/branches) | [![Build Status](https://travis-ci.com/rapydo/rapydo-angular.svg?branch=0.7.4)](https://travis-ci.com/rapydo/rapydo-angular/branches) |
| 0.7.1 | [![Build Status](https://travis-ci.com/rapydo/do.svg?branch=0.7.1)](https://travis-ci.com/rapydo/do/branches) | [![Build Status](https://travis-ci.com/rapydo/http-api.svg?branch=0.7.1)](https://travis-ci.com/rapydo/http-api/branches) | [![Build Status](https://travis-ci.com/rapydo/build-templates.svg?branch=0.7.1)](https://travis-ci.com/rapydo/build-templates/branches) | [![Build Status](https://travis-ci.com/rapydo/rapydo-angular.svg?branch=0.7.1)](https://travis-ci.com/rapydo/rapydo-angular/branches) |
| 0.6.7 | [![Build Status](https://travis-ci.com/rapydo/do.svg?branch=0.6.7)](https://travis-ci.com/rapydo/do/branches) | [![Build Status](https://travis-ci.com/rapydo/http-api.svg?branch=0.6.7)](https://travis-ci.com/rapydo/http-api/branches) | [![Build Status](https://travis-ci.com/rapydo/build-templates.svg?branch=0.6.7)](https://travis-ci.com/rapydo/build-templates/branches) | [![Build Status](https://travis-ci.com/rapydo/rapydo-angular.svg?branch=0.6.7)](https://travis-ci.com/rapydo/rapydo-angular/branches) |
