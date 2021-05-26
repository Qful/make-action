# [make action](https://github.com/Qful/make-action)

[![Build Status](https://github.com/Qful/make-action/workflows/CI/badge.svg)](https://github.com/Qful/make-action/actions/workflows/CI.yml)


| Gcc version |  测试 |  测试 | 测试 | 接口 | 测试 | 测试 | 测试 |
| ----------- | ----- | ---- | ---- | ---- | ---- | ---- | ---- |
|  10-2020-q4 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   9-2020-q2 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   9-2019-q4 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   8-2019-q3 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   8-2018-q4 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   7-2018-q2 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   7-2017-q4 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   6-2017-q2 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   6-2017-q1 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   6-2016-q4 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   5-2016-q3 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   5-2016-q2 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   5-2016-q1 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
|   5-2015-q4 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
| 4.9-2015-q3 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
| 4.9-2015-q2 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
| 4.9-2015-q1 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
| 4.9-2014-q4 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
| 4.8-2014-q3 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
| 4.8-2014-q2 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
| 4.8-2014-q1 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
| 4.7-2014-q2 | √     |  X   |  X   |  X   |  X   |  X   |  X   |
## Usage

```yaml
steps:
- name: arm-none-eabi-gcc
  uses: Qful/make-action@master
  with:
    release: '10-2020-q4' # The arm-none-eabi-gcc release to use.
- run: ...
```
