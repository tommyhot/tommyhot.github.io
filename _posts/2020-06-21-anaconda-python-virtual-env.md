---
layout: post
title: anaconda-python虚拟环境
tags: python
---


Welcome to Hydrogen!<br>If you saw this post, your blog has been successfully deployed.So enjoy the fun of writing now!

```sh
conda create -n python37 python=3.7
source activate python37
pip install ipykernel
python -m ipykernel install python37
```

### pypi国内源
* 阿里源
```
[global]
index-url = http://mirrors.aliyun.com/pypi/simple/ 

[install]
trusted-host = mirrors.aliyun.com
```

	