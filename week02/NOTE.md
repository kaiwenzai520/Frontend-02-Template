学习笔记

1.TextEncoder.encode(String);接收一个String类型的参数返回一个Unit8Array;

2.encodeURI(str)，其中如果碰到中文字符之类的，就会按照 utf8 编码之后变成 %E5%91 这个样子，我们利用这个，完了之后再将 % 替换成 \x，就得到了单个字节的串。

3.fromCharCode fromCharCode() 可接受一个指定的 Unicode 值，然后返回一个字符串

其他的都比较模糊，止步于理解字面意思上，将会继续深入学习。