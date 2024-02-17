好了，为了稳定读取（保护你的内存），在取证环境动辄几十个g的文件下，我对工具做出了修改：
现在新版本的工具将不再支持pdf、bmp等文件的恢复，而只支持jpg和png类型的文件

![Snipaste_2024-02-17_21-53-37](https://github.com/SuperFengi/ExtractMe/assets/97447828/1d9ce3cd-6058-4be3-9a88-492dbccd3645)


本次更新使用了分块读取内存机制，规避了以下的情况：

![eaaf64c1bb4e2b971869587b85febd3](https://github.com/SuperFengi/ExtractMe/assets/97447828/9dacc1f3-df76-407a-aa95-a752ee3526f9)

但是并不代表1.0.0的工具就失去了价值，对于一些不是特别大的二进制文件，仍然可以提取出有关的数据
