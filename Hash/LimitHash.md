#可控Hash算法
##算法描述
>哈希算法将任意长度的二进制值映射为较短的固定长度的二进制值，这个小的二进制值称为哈希值。哈希值是一段数据唯一且极其紧凑的数值表示形式。如果散列一段明文而且哪怕只更改该段落的一个字母，随后的哈希都将产生不同的值。要找到散列为同一个值的两个不同的输入，在计算上是不可能的，所以数据的哈希值可以检验数据的完整性。一般用于快速查找和加密算法。  
>哈希表是根据设定的哈希函数H(key)和处理冲突方法将一组关键字映射到一个有限的地址区间上，并以关键字在地址区间中的象作为记录在表中的存储位置，这种表称为哈希表或散列，所得存储位置称为哈希地址或散列地址。作为线性数据结构与表格和队列等相比，哈希表无疑是查找速度比较快的一种。  
>通过将单向数学函数（有时称为“哈希算法”）应用到任意数量的数据所得到的固定大小的结果。如果输入数据中有变化，则哈希也会发生变化。哈希可用于许多操作，包括身份验证和数字签名。也称为“消息摘要”。  
>简单解释：哈希(Hash)算法,即散列函数。它是一种单向密码体制,即它是一个从明文到密文的不可逆的映射,只有加密过程,没有解密过程。同时,哈希函数可以将任意长度的输入经过变化以后得到固定长度的输出。哈希函数的这种单向特征和输出数据长度固定的特征使得它可以生成消息或者数据。

##算法用例
* C++用例
><font color=#0099ff size=3>引用HashTable.h的头文件  
>//得到整体数据内存大小  
>size_t Get_Size(int nHashCount, short sKeySize = DEF_HASH_KEY_SIZE);  
>//关闭Hash对象  
>Close();  
>//初始化Hash块(nKeySize为Key字符串最大长度)  
>void Init(int nHashCount, int nKeySize = DEF_HASH_KEY_SIZE);  
>//初始化Hash块  
>void Init_By_Memory(char* pData, int nHashCount, int nKeySize = DEF_HASH_KEY_SIZE, char cIsDelete = 0);  
>//得到当前对象总数  
>int Get_Count();  
>//得到数据中正在使用的个数  
>int Get_Used_Count()  
>//弹出一个在链表中的_Hash_Link_Info<T>* pT  
>T* Pop();  
>//将一个已经使用完成的对象，放回到链表  
>bool Push(const char* pKey, T* pT);
>//得到所有正在使用的指针  
>void Get_All_Used(vector<T*>& vecList);  
>//添加一个Hash数据块  
>int Add_Hash_Data(const char* pKey, T* pValue);
>/获得一个已有映射对应数值  
>T* Get_Hash_Box_Data(const char* pKey);
>//删除一个hash数据块  
>int Del_Hash_Data(const char* pKey);  
></font>

##应用场景
>C++支持Linux平台编译执行  


##相关附件下载
>[C/C++测试用例下载](../Code/HashTable_C++.rar)  