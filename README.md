### [Documentation on GitHub Pages](https://rapydo.github.io/docs)

### A brief summary of all RAPyDO repositories:

| Project | Version | Quality | Tests | Coverage | Security |
| --- | --- | --- | --- | --- | --- |
| [controller](https://github.com/rapydo/do) | [![PyPI version](https://badge.fury.io/py/rapydo.svg)](https://badge.fury.io/py/rapydo) | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/0668957ee3a04608887b2e9a7fdea198)](https://www.codacy.com/gh/rapydo/do?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=rapydo/do&amp;utm_campaign=Badge_Grade) | [![Test](https://github.com/rapydo/do/workflows/Test/badge.svg)](https://github.com/rapydo/do/actions?query=workflow%3ATest) | [![codecov](https://codecov.io/gh/rapydo/do/branch/2.0/graph/badge.svg)](https://codecov.io/gh/rapydo/do) | [![CodeQL](https://github.com/rapydo/do/workflows/CodeQL/badge.svg)](https://github.com/rapydo/do/actions?query=workflow%3ACodeQL) |
| [http-api](https://github.com/rapydo/http-api) | [![PyPI version](https://badge.fury.io/py/rapydo-http.svg)](https://badge.fury.io/py/rapydo-http) | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/7fb33f343d824eaeb323672545ad9cca)](https://www.codacy.com/gh/rapydo/http-api?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=rapydo/http-api&amp;utm_campaign=Badge_Grade) | [![Test](https://github.com/rapydo/http-api/workflows/Test/badge.svg)](https://github.com/rapydo/http-api/actions?query=workflow%3ATest) | [![codecov](https://codecov.io/gh/rapydo/http-api/branch/2.0/graph/badge.svg)](https://codecov.io/gh/rapydo/http-api) | [![CodeQL](https://github.com/rapydo/http-api/workflows/CodeQL/badge.svg)](https://github.com/rapydo/http-api/actions?query=workflow%3ACodeQL) |
| [angular](https://github.com/rapydo/rapydo-angular) | [![GitHub version](https://img.shields.io/github/tag/rapydo/rapydo-angular.svg)](https://github.com/rapydo/rapydo-angular/releases) | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/1e839e6b61d4465088989d068c0fcafe)](https://www.codacy.com/gh/rapydo/rapydo-angular?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=rapydo/rapydo-angular&amp;utm_campaign=Badge_Grade) | [![Test](https://github.com/rapydo/rapydo-angular/workflows/Test/badge.svg)](https://github.com/rapydo/rapydo-angular/actions?query=workflow%3ATest) | [![codecov](https://codecov.io/gh/rapydo/rapydo-angular/branch/2.0/graph/badge.svg)](https://codecov.io/gh/rapydo/rapydo-angular) | [![CodeQL](https://github.com/rapydo/rapydo-angular/workflows/CodeQL/badge.svg)](https://github.com/rapydo/rapydo-angular/actions?query=workflow%3ACodeQL) |
| [build templates](https://github.com/rapydo/build-templates) | [![GitHub version](https://img.shields.io/github/tag/rapydo/build-templates.svg)](https://github.com/rapydo/build-templates/releases) | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/985f3eb2469f4e3dbb84edf64d354c47)](https://www.codacy.com/gh/rapydo/build-templates?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=rapydo/build-templates&amp;utm_campaign=Badge_Grade) | [![Build](https://github.com/rapydo/build-templates/workflows/Build/badge.svg)](https://github.com/rapydo/build-templates/actions?query=workflow%3A%22Build%22) |  | [![CodeQL](https://github.com/rapydo/build-templates/workflows/CodeQL/badge.svg)](https://github.com/rapydo/build-templates/actions?query=workflow%3ACodeQL) |


[![PyPI](https://img.shields.io/pypi/l/rapydo-controller.svg)](https://github.com/rapydo/core/blob/master/LICENSE)


## Versions

| Version | Release date | Status | Major changes |
| --- | --- | --- | --- |
| **2.0** | *Jul 2021* | *Under development* | Docker 20.10+; Dropped py3.6; |
| **1.2** | **22 May 2021** | **Supported** | SCSS; Support for NoAuth deployments; Enabled Docker BuildKit; |
| **1.1** | **24 Apr 2021** | **Supported** | Deprecated endpoints multiple mapping; Autocomplete fields; Upload and download improvements; SEO improvements; |
| **1.0** | **20 Feb 2021** | **Supported** | Python3.9 backend; Celery 5; Angular 11; Ajv 7 with standalone compilation (production-ready); Angular SSR; Two Factor Authentication; |
| 0.9 | 13 Dec 2020 | Discontinued | Groups management; PostgreSQL 13; Started Python Typing; Gzip compressed responses; Endpoints caching; |
| 0.8 | 24 Oct 2020 | Discontinued | Controller package renamed (rapydo-controller -> rapydo); Dropped support for _METHOD dictionaries; Ajv frontend validation (dev mode); Neo4j 4; |
| 0.7.6 | 04 Sep 2020 | Discontinued | @decorators.endpoint; Angular10; Cypress 5; Webargs 6; Profile edit; |
| 0.7.5 | 17 Aug 2020 | Discontinued | Stats endpoint; Ubuntu 20.04; Dropped irods; Dropped py35; Typer; rapydo backup; |
| 0.7.4 | 09 Jul 2020 | Discontinued | Gunicorn; Flask-Apispec; Dropped AngularJS; Cypress; |
| 0.7.3 | 16 May 2020 | Discontinued | Dropped rapydo-confs repo; Unwrapped responses; Angular 9; rapydo create; |
| 0.7.2 | 21 Mar 2020 | Discontinued | Dropped py34; |
| 0.7.1 | 19 Jan 2020 | Discontinued | Dropped utils repo; PostgreSQL 12; |
| 0.7.0 | 25 Nov 2019 | Discontinued | Angular CLI; Dropped swagger yamls |
| 0.6.7 | 23 Sep 2019 | Discontinued | Angular 8; Celery-beat; PostgreSQL 11; |
| 0.6.6 | 28 Jun 2019 | Discontinued | |
| 0.6.5 | 19 Apr 2019 | Discontinued | Angular 7; rapydo install auto;|
| 0.6.4 | 11 Feb 2019 | Discontinued | |
| 0.6.3 | 06 Dec 2018 | Discontinued | |
| 0.6.2 | 30 Jul 2018 | Discontinued | Angular 5; |
| 0.6.1 | 26 Apr 2018 | Discontinued | |
| 0.6.0 | 17 Jan 2018 | Discontinued | PostgreSQL 10; |
| 0.5.7 | 03 Nov 2017 | Discontinued | |
| 0.5.6 | 24 Oct 2017 | Discontinued | |
| 0.5.5 | 25 Sep 2017 | Discontinued | |
| 0.5.4 | 12 Sep 2017 | Discontinued | |
| 0.5.3 | 1 Aug 2017 | Discontinued | |
| 0.5.2 | 28 Jul 2017 | Discontinued | |
| 0.5.1 | 18 Jul 2017 | Discontinued | |
| 0.5.0 | 14 Jul 2017 | Discontinued | |

| Version | Build templates | Controller | HTTP-API | Rapydo-Angular |
| --- | --- | --- | --- | --- |
| 2.0 | [![Docker Build](https://github.com/rapydo/build-templates/workflows/Build/badge.svg?branch=2.0)](https://github.com/rapydo/build-templates/actions?query=branch%3A2.0+workflow%3A%22Build%22) | [![Test](https://github.com/rapydo/do/workflows/Test/badge.svg?branch=2.0)](https://github.com/rapydo/do/actions?query=branch%3A2.0+workflow%3ATest) | [![Test](https://github.com/rapydo/http-api/workflows/Test/badge.svg?branch=2.0)](https://github.com/rapydo/http-api/actions?query=branch%3A2.0+workflow%3ATest) | [![Test](https://github.com/rapydo/rapydo-angular/workflows/Test/badge.svg?branch=2.0)](https://github.com/rapydo/rapydo-angular/actions?query=branch%3A2.0+workflow%3ATest) |
| 1.2 | [![Docker Build](https://github.com/rapydo/build-templates/workflows/Build/badge.svg?branch=1.2)](https://github.com/rapydo/build-templates/actions?query=branch%3A1.2+workflow%3A%22Build%22) | [![Test](https://github.com/rapydo/do/workflows/Test/badge.svg?branch=1.2)](https://github.com/rapydo/do/actions?query=branch%3A1.2+workflow%3ATest) | [![Test](https://github.com/rapydo/http-api/workflows/Test/badge.svg?branch=1.2)](https://github.com/rapydo/http-api/actions?query=branch%3A1.2+workflow%3ATest) | [![Test](https://github.com/rapydo/rapydo-angular/workflows/Test/badge.svg?branch=1.2)](https://github.com/rapydo/rapydo-angular/actions?query=branch%3A1.2+workflow%3ATest) |
| 1.1 | [![Docker Build](https://github.com/rapydo/build-templates/workflows/Build/badge.svg?branch=1.1)](https://github.com/rapydo/build-templates/actions?query=branch%3A1.1+workflow%3A%22Build%22) | [![Test](https://github.com/rapydo/do/workflows/Test/badge.svg?branch=1.1)](https://github.com/rapydo/do/actions?query=branch%3A1.1+workflow%3ATest) | [![Test](https://github.com/rapydo/http-api/workflows/Test/badge.svg?branch=1.1)](https://github.com/rapydo/http-api/actions?query=branch%3A1.1+workflow%3ATest) | [![Test](https://github.com/rapydo/rapydo-angular/workflows/Test/badge.svg?branch=1.1)](https://github.com/rapydo/rapydo-angular/actions?query=branch%3A1.1+workflow%3ATest) |
| 1.0 | [![Docker Build](https://github.com/rapydo/build-templates/workflows/Build/badge.svg?branch=1.0)](https://github.com/rapydo/build-templates/actions?query=branch%3A1.0+workflow%3A%22Build%22) | [![Test](https://github.com/rapydo/do/workflows/Test/badge.svg?branch=1.0)](https://github.com/rapydo/do/actions?query=branch%3A1.0+workflow%3ATest) | [![Test](https://github.com/rapydo/http-api/workflows/Test/badge.svg?branch=1.0)](https://github.com/rapydo/http-api/actions?query=branch%3A1.0+workflow%3ATest) | [![Test](https://github.com/rapydo/rapydo-angular/workflows/Test/badge.svg?branch=1.0)](https://github.com/rapydo/rapydo-angular/actions?query=branch%3A1.0+workflow%3ATest) |


| Controller | HTTP-API | Rapydo-Angular |
| --- | --- | --- |
| ![](https://codecov.io/gh/rapydo/do/branch/1.1/graphs/sunburst.svg) | ![](https://codecov.io/gh/rapydo/http-api/branch/1.1/graphs/sunburst.svg) | ![](https://codecov.io/gh/rapydo/rapydo-angular/branch/1.1/graphs/sunburst.svg) |
