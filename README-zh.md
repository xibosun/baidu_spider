## 百度图片爬虫

[![Build Status](docs/build_status.svg)](https://github.com/xibosun/spider)
[![issues](docs/issues.svg)](https://github.com/xibosun/spider/issues)
[![Stars](docs/stars.svg)](https://github.com/xibosun/spider/stargazers)
[![Dependencies](docs/dependencies.svg)](https://www.python.org/downloads/release/python-363/)
[![Release](docs/release.svg)](https://github.com/xibosun/spider)
[![License](docs/license.svg)](https://opensource.org/licenses/mit-license.php)
[![](docs/chinese.svg)](README-zh.md)

### 介绍

百度图片爬虫可以通过关键词查询图片

### 依赖库

通过 `pip` 安装 `gzip`, `json`, `re` 等库

### 使用方法

首先输入关键词，以“The Starry Night”为例

```python
input keyword：The Starry Night
```

随后输入图片数量

```python
number of pics：12
```

### result

之后它可以保存图片或将图片的url以*JSON*的形式返回

```python
['https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=3151821785,2257953516&fm=27&gp=0.jpg', 'https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=2180750087,196933357&fm=27&gp=0.jpg', 'https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=3934163105,2026184406&fm=27&gp=0.jpg', 'https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=3378451335,1895294952&fm=27&gp=0.jpg', 'https://ss2.bdstatic.com/70cFvnSh_Q1YnxGkpoWK1HF6hhy/it/u=3879481087,3883224317&fm=27&gp=0.jpg', 'https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=386725354,2830833392&fm=27&gp=0.jpg', 'https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=2074250503,1148182660&fm=27&gp=0.jpg', 'https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=3201361018,3145236084&fm=27&gp=0.jpg', 'https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=1472224935,1575682395&fm=27&gp=0.jpg', 'https://ss1.bdstatic.com/70cFvXSh_Q1YnxGkpoWK1HF6hhy/it/u=1081326597,2339731606&fm=27&gp=0.jpg', 'https://ss1.bdstatic.com/70cFuXSh_Q1YnxGkpoWK1HF6hhy/it/u=4026543696,3011650539&fm=27&gp=0.jpg', 'https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=4139601809,3953991665&fm=27&gp=0.jpg']
```