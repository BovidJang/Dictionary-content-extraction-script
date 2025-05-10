通过修改源码内内容，可以在现代汉语词典中提取所有以X开头的文字的组词，可以自行调整提取的词语长度
ps：我是做一个姓名提取脚本的时候用到的 提取出各个姓氏的所有组词，然后筛除掉，避免提取到多余内容
使用方法：
SINGLE_SURNAMES 写入你想提取的词组的开头文字
dict_path output_path 两个路径需要自己更改
len(word) == 2: 将2更改为其他数字可以修改提取的内容长度

By modifying the content in the source code, we can extract all the words starting with X from the modern Chinese dictionary, and we can adjust the length of the extracted words by ourselves.
Ps: I used to extract all the words of each surname when I made a name extraction script, and then filtered them out to avoid extracting redundant content.
How to use:
SINGLE_SURNAMES writes the beginning text of the phrase you want to extract.
Dict_path output_path need to be changed by yourself.
Len(word) == 2: Changing 2 to another number can modify the length of the extracted content.
