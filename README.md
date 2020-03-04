# webtech
Identify the technologies used on websites. (Dig-deep into web tech from your terminal)

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/e1f930ad4e9049109d73459f1edb7392)](https://app.codacy.com/manual/kaiiyer47/webtech?utm_source=github.com&utm_medium=referral&utm_content=kaiiyer/webtech&utm_campaign=Badge_Grade_Dashboard)
[![CircleCI](https://circleci.com/gh/kaiiyer/webtech.svg?style=svg)](https://circleci.com/gh/kaiiyer/webtech)
[![GitHub top language](https://img.shields.io/github/languages/top/kaiiyer/webtech?color=yellow&logo=python)]() 
![Only 32 Kb](https://badge-size.herokuapp.com/kaiiyer/webtech/master/Burp-WebTech.py)
[![GitHub issues](https://img.shields.io/github/issues/kaiiyer/webtech.svg)](https://GitHub.com/kaiiyer/webtech/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/kaiiyer/webtech.svg)](https://GitHub.com/kaiiyer/webtech//pull/)
[![GitHub contributors](https://img.shields.io/github/contributors/kaiiyer/webtech.svg)](https://GitHub.com/kaiiyer/webtech/graphs/contributors/)
![Last Commit on GitHub](https://img.shields.io/github/last-commit/kaiiyer/webtech.svg)
[![GitHub forks](https://img.shields.io/github/forks/kaiiyer/webtech.svg?style=social&label=Fork&maxAge=2592000)](https://github.com/kaiiyer/webtech)
[![GitHub stars](https://img.shields.io/github/stars/kaiiyer/webtech.svg?style=social&label=Star&maxAge=2592000)](https://github.com/kaiiyer/webtech)
[![GitHub watchers](https://img.shields.io/github/watchers/kaiiyer/webtech.svg?style=social&label=Watch&maxAge=2592000)](https://github.com/kaiiyer/webtech/watchers/)

## Installation
WebTech is available on pip:
```
pip install webtech
```
It can be also installed via setup.py:

```
pip install -r requirements.txt
python setup.py install --user
```

## Usage
![Webtech Interface](https://user-images.githubusercontent.com/24914913/74858499-6fc4dc80-536b-11ea-996a-6c6b9bb20a1f.png)

Scan a website:

```
$ webtech -u https://example.com/

Target URL: https://example.com
```
## Resources for database matching

[HTTP Headers information](http://netinfo.link/http/headers.html)

[Cookie names](https://webcookies.org/top-cookie-names) 

## Burp Integration

Download Jython 2.7.0 standalone and install it into Burp.

In "Extender" > "Options" > "Python Environment":

    Select the Jython jar location

Finally, in "Extender" > "Extension":

    Click "Add"
    Select "py" or "Python" as extension format
    Select the Burp-WebTech.py file in this folder

PRs are highly appreciated !!!

Read [info about burp](https://github.com/keshakaneria/webtech/blob/master/docs/info_about_burpsuite.md) in docs folder for more information about Burpsuite.

Read [Guidelines](/CONTRIBUTING.md) for making a PR.

Inspired by [webtech](https://github.com/ShielderSec/webtech)
