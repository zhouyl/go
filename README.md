go
==
librarys, generic code, RTFSC

Common：公用代码，如Init，CheckPanic

keepalive.sh：保活脚本

BitMapCache系列：一个内存位图缓存服务。比如需要表示QQ号是否在线等7种状态，可以创建一个4位缓存。如仅表示两种状态，1位的缓存足矣。在使用1位缓存时，每10亿用户仅用128M内存。


DctDst ： 离散正弦变换及其逆变换，离散余弦变换及其逆变换
