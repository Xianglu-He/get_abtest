# get_abtest
Hello everyone,
this is a customized ab test frame work package
For time to time, I realize that there is a need to run hypothsis test on ab testing experiment
So I tried to build a python modules to automative the work a little bit
Hope everyone who see this enjoy it :) 

## Table of Contents

_Note: This is only a navigation guide for the specification, and does not define or mandate terms for any specification-compliant documents._

- [Sections](#sections)
  - [Title](#title)
  - [Description](#description)
  - [Install](#install)
  - [License](#license)
- [Definitions](#definitions)

## Sections

### Title 
**Status:** Version 0.1.1 pass

**Requirements:**
It requires pre-installed packages including re, pandas, and scipy.stats

### Description
**Status:** Hello everyone,
this is a customized ab test frame work package
For time to time, I realize that there is a need to run hypothsis test on ab testing experiment
So I tried to build a python modules to automative the work a little bit
Hope everyone who see this enjoy it :) 

**Use case:**
get_insight(file): input the file name, please make sure the file is under same dictionary as the python file
pre_test(data,col,col2): run the pre_test baseline comparison between control and experiment group. data is the data set, col is control or experiment identify col (please note 0 is control and 1 is experiment); col2 is the final outcome of the A/B Test
final_test(data,col,col2):variable definiation stay the same. The output of this function is the evluation of A/B Test final outcome and a simple conclusion. 

### Install
**Status:** pip install get_abtest


### License
**Status:** MIT




