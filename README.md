# hz2py
汉字转拼音
convert函数:无声调 
convert_sd函数:有声调
例子
```
a = hz2pyclass()
print a.convert("当")
print a.convert_sd("当")
print a.convert("解")
print a.convert_sd("解")
```
输出
```
['DANG']
[['DANG', '1'], ['DANG', '4']]
['JIE', 'XIE']
[['JIE', '3'], ['JIE', '4'], ['XIE', '4']]
```
