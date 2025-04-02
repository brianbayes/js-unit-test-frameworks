# Introduction
The purpose of this repository is to compare different JavaScript unit tests frameworks within the context of an AWS SAM application. There are 2 apis to enable the comparision:

### sam-api-jest
This is the default that the SAM CLI configures and includes jest as part of its `package.json`

### sam-api-vitest
This is a modified version that the SAM CLI default, with jest replaced with vitest in `package.json`, and the same default tests updated to use vitest.


## Pre-requisites



