- 9月18日

  [第4讲数制与码制和基本数据类型_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1bcYxzWEEN/?buvid=XU7729D7A2792CF4E75591374782D433105CF&from_spmid=search.search-result.0.0&is_story_h5=false&mid=Sl9k5ak8nyE%2BTJCzHP5%2BdA%3D%3D&plat_id=116&share_from=ugc&share_medium=android&share_plat=android&share_session_id=688d113d-a163-49c4-83aa-dc7988a2e863&share_source=QQ&share_tag=s_i&spmid=united.player-video-detail.0.0&timestamp=1789213278&unique_k=SQ3PbrH&up_id=1041194501&vd_source=62e22450d7f4d5f6d645f4008e9fae75&p=5&spm_id_from=333.788.videopod.episodes)

  - 一，数进制

  ​        2进制 01

  ​        8进制  12345678

  ​        16进制 123456789ABCDEF

  - 二，位权 

      1145.14

       1  10^2

      1   10^1

      4    10^0

      5      10^-1

      位值等于  10^2+10^1...............

    ​     1.14514*10^3

    - 三，进制转换：

      打开电脑计算器，选择程序员模式。

计算机存储  STC8051  8位单片机

STC32  32位单片机，一次能处理32位

0x00 - 0xff

在带正负存储系统  0最高位为正  1最高为为负   数据溢出变成负数这块缺的谁给我补啊

   存储浮 1145.14  =  3 1145.14

八位二进制

0110 1100

符号位 01        阶数10  位数1 011

int 数据  8位单片机 存储 0000 0000

第一位为正负位  能表示+-2^7  

可以用户用short int 和long int增加或者减少存储范围 long long longint



单精度浮点 Float 1位符号  8位指数  23位尾数

双精度浮点 double 1位符号 11位指数  52位数

进制转换浮点精度丢失，工程时切忌

