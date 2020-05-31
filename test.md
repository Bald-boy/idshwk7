# idshwk7
项目使用的是LSB算法。

源文件：
	LSBSteg.py：源程序
	test.png：目标图片
	info.txt：隐藏的内容文件

生成文件：
	encode.png：隐藏后的文件
	decode.txt：解密后得到的隐藏内容的文件

加密：
python37 LSBSteg.py  encode -i test.png -o encode.png -f info.txt
解密：
python37 LSBSteg.py  decode -i encode.png -o decode.txt
