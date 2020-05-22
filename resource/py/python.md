<!--
 * @Date        : 2020-05-07 19:15:05
 * @LastEditors : anlzou
 * @Github      : https://github.com/anlzou
 * @LastEditTime: 2020-05-22 23:39:15
 * @FilePath    : \blog\resource\py\python.md
 * @Describe    : 
--> 
# python

#### [peterbe](https://github.com/peterbe)/[mincss](https://github.com/peterbe/mincss)

> Tool for finding out which CSS selectors you're NOT using. https://peterbe.github.io/mincss/

> 删除css中没有使用的代码。

#### [saffsd](https://github.com/saffsd)/[langid.py](https://github.com/saffsd/langid.py)
> Stand-alone language identification system

>  用于识别输入文本数据所属的语种，目前支持 97 种语言识别。

 示例代码:
 ```
 import langid
text1 = "I am a coder and love data mining"
text2 = "请注明作者和出处并保留声明和联系方式"

print langid.classify(text1)
print langid.classify(text2)

# ('en', 0.9999957874458753)
# ('zh', 1.0)
 ```