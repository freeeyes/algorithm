#MD5
##算法描述
>Message Digest Algorithm MD5（中文名为消息摘要算法第五版）为计算机安全领域广泛使用的一种散列函数，用以提供消息的完整性保护。该算法的文件号为RFC 1321（R.Rivest,MIT Laboratory for Computer Science and RSA Data Security Inc. April 1992）。
>
>MD5即Message-Digest Algorithm 5（信息-摘要算法5），用于确保信息传输完整一致。是计算机广泛使用的杂凑算法之一（又译摘要算法、哈希算法），主流编程语言普遍已有MD5实现。将数据（如汉字）运算为另一固定长度值，是杂凑算法的基础原理，MD5的前身有MD2、MD3和MD4。
>MD5算法具有以下特点：
>
* 1、压缩性：任意长度的数据，算出的MD5值长度都是固定的。
* 2、容易计算：从原数据计算出MD5值很容易。
* 3、抗修改性：对原数据进行任何改动，哪怕只修改1个字节，所得到的MD5值都有很大区别。
* 4、强抗碰撞：已知原数据和其MD5值，想找到一个具有相同MD5值的数据（即伪造数据）是非常困难的。

>MD5的作用是让大容量信息在用数字签名软件签署私人密钥前被"压缩"成一种保密的格式（就是把一个任意长度的字节串变换成一定长的十六进制数字串）。除了MD5以外，其中比较有名的还有sha-1、RIPEMD以及Haval等。

##算法用例
* C/C++用例
><font color=#0099ff size=3>引用md5.h头文件  
>获得32位MD5字符串   
>pData 数据指针（可以是二进制块，可以是字符串）  
>size_t 数据长度  
>pMd5 返回的Md5字符串  
>void get\_md5\_32\_string(const char* pData, size_t stSize, char* pMd5); 
>获得16位MD5字符串(32位)  
>pData 数据指针（可以是二进制块，可以是字符串）  
>size_t 数据长度  
>pMd5 返回的Md5字符串(16位)   
>void get\_md5\_16\_string(const char* pData, size_t stSize, char* pMd5);  
></font>
>测试用例编译语句 g++ -o test md5.c main.cpp

* Java用例
><font color=#0099ff size=3>引用Md5.Java文件  
>获得32位MD5字符串   
>plainText 要加密的字符串  
>public static String get\_md5\_32\_string(String plainText);  
>获得16位MD5字符串(16位)  
>plainText要加密的字符串  
>public static String get\_md5\_16\_string(String plainText);  
></font>   
* Python用例  
><font color=#0099ff size=3>引用Md5.py文件  
>获得32位MD5字符串   
>strData 要加密的字符串  
>def get\_md5\_32\_string(strData)  
>获得16位MD5字符串(16位)  
>strData要加密的字符串  
>def get\_md5\_16\_string(strData)  
></font>  
* Shell用例
><font color=#0099ff size=3>使用语句  
>strMD5=`echo test |md5sum|awk '{print $1}'`  
></font> 

##应用场景
>C/C++支持Linux和windows平台编译执行

##相关附件下载
>[C/C++测试用例下载](../Code/MD5_C.rar)  
>[Java测试用例下载](../Code/MD5_JAVA.rar)  
>[Python测试用例下载](../Code/MD5_PYTHON.rar)
