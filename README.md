
whalesafe4r
===========

<p align="center">
<img width="460" height="300" src="./man/figures/floaty.gif">
</p>
##### Table of Contents

[Installation](#installation)
[Overview](#overview)
[Crawlers](#crawlers) [Readers](#readers) [Updaters](#updaters) [Stats](#stats)

The WhaleSafe4r package harvests AIS data located at [this site](https://ais.sbarc.org/), which are collected and maintained by the [Santa Barbara Amateur Radio Club | K6TZ](https://www.sbarc.org/). The data is then written to a postgres database and analyzed in order to generate vessel speed report cards.

<a name="installation"/>

Installation
------------

You can install the released version of whaletrails from: [Github](https://github.com/BenioffOceanInitiative/whalesafe4r) with:

``` r
devtools::install_github("BenioffOceanInitiative/whalesafe4r")
```

<a name="overview"/>

Overview
--------

The primary areas our functions address are:

1.  [Crawlers](whalesafe4r/R/crawlers.R)
2.  [Readers](./R/readers.R)
3.  [Updaters](./R/update_ais.R)
4.  [Stats](./R/seg_stats.R)
