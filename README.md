
## 直接运行源文件

- parse_main函数即可

## pip 安装使用

```shell
pip install .
or 
pip install huggingface_urls
```


```py
from huggingface_urls import parse_main

url = 'https://huggingface.co/RunDiffusion/Juggernaut-XL-v9/tree/main'

print(parse_main(url))
```