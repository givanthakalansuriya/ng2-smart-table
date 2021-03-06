<a name="1.1.0"></a>
# 1.1.0 (2017-04-21)

### Bug fixes

* **docs:** update docs ([80b3b22](https://github.com/akveo/ng2-smart-table/commit/80b3b224868a0d716eeceb8239042a1f83ac3bb9)), ([#308](https://github.com/akveo/ng2-smart-table/pull/308))
* **docs:** update docs ([9920b3c](https://github.com/akveo/ng2-smart-table/commit/9920b3c14b09364c7c4e97344c89856557b3b8c1)), ([#309](https://github.com/akveo/ng2-smart-table/pull/309))
* **table:** performing an edit might result in an error when the data source is being updated by an Observable ([4221b4c](https://github.com/akveo/ng2-smart-table/commit/4221b4cfb13e965f41f62603ced85b9e0d5237d4)), ([#280](https://github.com/akveo/ng2-smart-table/pull/280)), closes ([#279](https://github.com/akveo/ng2-smart-table/issues/279))
* **docs:** fix the links ([68205eb](https://github.com/akveo/ng2-smart-table/commit/68205eb17d2d893995808a74fe1bd8d7b6cb1d37))
* **table:** change style deployment as external file for better flexibility ([4504fcf](https://github.com/akveo/ng2-smart-table/commit/4504fcf2a952505f5cfdf800dadf73b3369144e6)), closes ([#112](https://github.com/akveo/ng2-smart-table/issues/112)), ([#290](https://github.com/akveo/ng2-smart-table/issues/290))

### Features

* **table:** allow for default value to be set for new cells ([9065c52](https://github.com/akveo/ng2-smart-table/commit/9065c5249c8c9b6aca72a10429f78caa487f3e23)), ([#311](https://github.com/akveo/ng2-smart-table/pull/311))
* **table:** add column width property ([77be67e](https://github.com/akveo/ng2-smart-table/commit/77be67ee915b1ac4fbd781c145cdd3f0d67a5214)), ([#313](https://github.com/akveo/ng2-smart-table/pull/313)), closes ([#134](https://github.com/akveo/ng2-smart-table/issues/134)), ([#201](https://github.com/akveo/ng2-smart-table/issues/201))
* **table:** add an 'addable' option ([abc8a84](https://github.com/akveo/ng2-smart-table/commit/abc8a8420bc1db1fd31ebbb5cbf62f04139cfd49)), ([#307](https://github.com/akveo/ng2-smart-table/pull/307))

<a name="1.0.4"></a>
# 1.0.4 (2017-04-13)

### Bug fixes

* **build:** added mising rxjs imports ([24c3098](https://github.com/akveo/ng2-smart-table/commit/24c309807e758ce62011d8bf5b16b3e3793d8b22)), closes ([#304](https://github.com/akveo/ng2-smart-table/issues/304))

<a name="1.0.3"></a>
# 1.0.3 (2017-04-05)

### Bug fixes

* **build:** added mising rxjs imports ([86de89f](https://github.com/akveo/ng2-smart-table/commit/86de89fffccffa8002d16ad17754c1a07574adc5)), ([#283](https://github.com/akveo/ng2-smart-table/pull/283)), closes ([#229](https://github.com/akveo/ng2-smart-table/issues/229))


<a name="1.0.2"></a>
# 1.0.2 (2017-04-04)

### Bug fixes

* **build:** move ng2-completer and lodash from peerDependencies to dependencies

<a name="1.0.1"></a>
# 1.0.1 (2017-03-29)

### Bug fixes

* **build:** fix package.json

<a name="1.0.0"></a>
# 1.0.0 (2017-03-29)

### Features

* **demo:** @angular/cli integration
* **demo:** setup demo deploying to the github pages
* **demo:** setup e2e and unit testing
* **table:** update to angular 4.0.0
* **table:** integrate gulp for npm package bundling
* **table:** add a row hover event ([68b73ee](https://github.com/akveo/ng2-smart-table/commit/68b73eef0b4607cef522f201c3e67a230a5ee03e)), ([1ceca0d](https://github.com/akveo/ng2-smart-table/commit/1ceca0d6afa3be3ba5f2ef53447d9a75f360150a)), ([#253](https://github.com/akveo/ng2-smart-table/pull/253)), ([#262](https://github.com/akveo/ng2-smart-table/pull/262))
* **table:** add a deselect row ([2ab02b4](https://github.com/akveo/ng2-smart-table/commit/2ab02b4949c577da34153f7ad1870e7acaa399e6)), ([#94](https://github.com/akveo/ng2-smart-table/pull/94))
* **table:** add a getFilteredAndSorted function ([df3f343](https://github.com/akveo/ng2-smart-table/commit/df3f343caaff9aff1ecc6d8b94767e3466524068)), ([#249](https://github.com/akveo/ng2-smart-table/pull/249))

### Bug fixes

* **table:** ng2-completer failed with empty value ([b0e1797](https://github.com/akveo/ng2-smart-table/commit/b0e1797e9d22ca4a076e01120525f16628e3e6a6)), closes ([#164](https://github.com/akveo/ng2-smart-table/issues/164))
* **table:** add a check for existing filters ([8daa70f](https://github.com/akveo/ng2-smart-table/commit/8daa70f8434cfb4036cec07dc68208a3c3c51d00)), ([#40](https://github.com/akveo/ng2-smart-table/pull/40))
* **table:** fix the actions column positioning ([ebfbd54](https://github.com/akveo/ng2-smart-table/commit/ebfbd5424a227217484494fc48a5f2fb854a470d)), ([#245](https://github.com/akveo/ng2-smart-table/pull/245))

### Code Refactoring

* **table:** move the components to the modules
* **demo:** move some examples to new /examples route ([#213](https://github.com/akveo/ng2-smart-table/pull/213))

### Breaking Changes

* **table:** remove div container with the css styles from ng2-smart-table component
* **table:** remove the css classes from table container

<a name="0.6.0-0"></a>
# 0.6.0-0 (2017-03-02)

### Features

* **table:** configuring column filters ([#185](https://github.com/akveo/ng2-smart-table/pull/185))
* **table:** custom cell view component ([#193](https://github.com/akveo/ng2-smart-table/pull/193))
* **table:** update to angular 2.4.9

### Bug Fixes

* **demo:** fix url redirect to gh-pages ([8a54dea141](https://github.com/akveo/ng2-smart-table/commit/8a54dea141041d8db19f42430db46d2a2c2dcae8))

### Code Refactoring

* **table:** grouping components by section ([#172](https://github.com/akveo/ng2-smart-table/pull/172))

<a name="0.3.1"></a>
# 0.3.1 (2016-09-19)

### Features

* **table:** update to angular 2.0

### How to update

* Install 0.2.1 version
* Checkout README.md installation section for more details

<a name="0.2.1"></a>
# 0.2.1 (2016-08-29)

### Features

* **table:** update to angular rc.5

### How to update

* Install 0.2.1 version
* Checkout README.md installation section for more details on configuration for rc.5
