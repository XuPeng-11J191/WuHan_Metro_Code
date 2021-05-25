# Wuhan_Metro_resource
代码中的换行符，编码时默认采用的是"\r\n"，但是提交git后发现，再下载下来编译使用的时候发现编译器又采用的"\n"。所以又没办法对对应的代码中以下几行进行修改:
(1)CMfFile.cpp L53 "i+=3"改为"i+=2”
(2)CMyFle.cpp L105"1+=3"改为"i+=2”
(3) CLinelnformation.cppL225""\r\n"改为"\n”
(4)CTimeTable.cpp L137""\r\n"改为""\n"
