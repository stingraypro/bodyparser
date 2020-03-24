<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [4.3.0 / 2020-03-24](#430--2020-03-24)
- [4.2.1 / 2018-05-21](#421--2018-05-21)
- [4.2.0 / 2017-03-21](#420--2017-03-21)
- [4.1.0 / 2017-03-02](#410--2017-03-02)
- [4.0.0 / 2017-02-27](#400--2017-02-27)
- [2.3.0 / 2016-11-14](#230--2016-11-14)
- [2.2.0 / 2016-05-16](#220--2016-05-16)
- [2.1.0 / 2016-05-10](#210--2016-05-10)
- [2.0.1 / 2015-08-12](#201--2015-08-12)
- [2.0.0 / 2015-05-07](#200--2015-05-07)
- [1.6.0 / 2015-05-01](#160--2015-05-01)
- [1.5.0 / 2015-04-04](#150--2015-04-04)
- [1.4.1 / 2015-03-10](#141--2015-03-10)
- [1.4.0 / 2015-02-26](#140--2015-02-26)
- [1.3.1 / 2015-01-27](#131--2015-01-27)
- [1.3.0 / 2014-11-27](#130--2014-11-27)
- [1.2.0 / 2014-11-07](#120--2014-11-07)
- [1.1.0 / 2014-10-28](#110--2014-10-28)
- [1.0.0 / 2014-04-23](#100--2014-04-23)
- [0.1.0 / 2014-03-06](#010--2014-03-06)
- [0.0.2 / 2014-02-26](#002--2014-02-26)
- [0.0.1 / 2014-02-18](#001--2014-02-18)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


4.3.0 / 2020-03-24
==================

**features**
  * [[`705673d`](http://github.com/koajs/bodyparser/commit/705673d634818727dbdb25ee999560970bd268a2)] - feat: support xml (#131) (TZ | 天猪 <<atian25@qq.com>>)

**others**
  * [[`6fd7e9c`](http://github.com/koajs/bodyparser/commit/6fd7e9c321684adc239d2afb270782c21d0b6231)] - docs: add multipart tips (dead-horse <<dead_horse@qq.com>>)
  * [[`57c0022`](http://github.com/koajs/bodyparser/commit/57c00225d54b5b5dd1a7526478ad3eae8495222f)] - Fix typo in README.md (#112) (Adrian Pascu <<1521321+adipascu@users.noreply.github.com>>)

4.2.1 / 2018-05-21
==================

**others**
  * [[`b270d5d`](http://github.com/koajs/bodyparser/commit/b270d5d138662f41dc63527505ea02dea0c1e7e8)] - deps: upgrade co-body (#104) (Haoliang Gao <<sakura9515@gmail.com>>)
  * [[`d234345`](http://github.com/koajs/bodyparser/commit/d234345ffa2dadbab2ef0ce970fb8a58059e5f47)] - docs(readme): update opts encode -> encoding (#103) (Matthew Scragg <<scragg@gmail.com>>)
  * [[`db193f5`](http://github.com/koajs/bodyparser/commit/db193f5d46860393521ad38f90a554968b2ba98a)] - chore:replace indexOf with includes (#90) (coderzzp <<coderzzp@gmail.com>>)

4.2.0 / 2017-03-21
==================

  * feat: ctx.request.rawBody to get raw request body (#70)

4.1.0 / 2017-03-02
==================

  * deps: upgrade co-body@5 (#64)

4.0.0 / 2017-02-27
==================

  * refactor: use async function and support koa@2 (#62)

2.3.0 / 2016-11-14
==================

  * feat: support dynamic disable body parser

2.2.0 / 2016-05-16
==================

  * feat: support enableTypes and text (#44)

2.1.0 / 2016-05-10
==================

  * deps: co-body@4

2.0.1 / 2015-08-12
==================

  * chore: upgrade co-body@3.1.0

2.0.0 / 2015-05-07
==================

  * deps: co-body@2, default to strict mode

1.6.0 / 2015-05-01
==================

  * feat: support custom error handler

1.5.0 / 2015-04-04
==================

  * Use an empty object instead of null, if no body is parsed

1.4.1 / 2015-03-10
==================

  * bump co-body@1.1.0

1.4.0 / 2015-02-26
==================

  * feat: custom json request detect

1.3.1 / 2015-01-27
==================

  * fix: extend

1.3.0 / 2014-11-27
==================

  * support extendTypes
  * Merge pull request #8 from coderhaoxin/json-patch
  * add support for json patch

1.2.0 / 2014-11-07
==================

  * add example.js
  * bump dependencies
  * Merge pull request #7 from rudijs/develop
  * Add support for JSON-API

1.1.0 / 2014-10-28
==================

  * Merge pull request #6 from tunnckoCore/master
  * resolve https://github.com/tunnckoCore/koa-better-body/issues/3#issuecomment-60458238

1.0.0 / 2014-04-23
==================

  * update readme
  * refactor

0.1.0 / 2014-03-06
==================

  * Merge pull request #2 from fengmk2/remove-co
  * Remove co deps and improve coverage to 100%

0.0.2 / 2014-02-26
==================

  * Merge pull request #1 from fengmk2/jsonLimit
  * add jsonLimit options to fix json and form body limit confuse

0.0.1 / 2014-02-18
==================

  * update package name, merge middleware into module.exports
  * complete readme
  * complete bodyparser and bodyparser.middleware
  * Initial commit
