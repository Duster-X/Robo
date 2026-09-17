- 9月17日

  [第3讲循环语句_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1bcYxzWEEN/?buvid=XU7729D7A2792CF4E75591374782D433105CF&from_spmid=search.search-result.0.0&is_story_h5=false&mid=Sl9k5ak8nyE%2BTJCzHP5%2BdA%3D%3D&plat_id=116&share_from=ugc&share_medium=android&share_plat=android&share_session_id=688d113d-a163-49c4-83aa-dc7988a2e863&share_source=QQ&share_tag=s_i&spmid=united.player-video-detail.0.0&timestamp=1789213278&unique_k=SQ3PbrH&up_id=1041194501&vd_source=62e22450d7f4d5f6d645f4008e9fae75&p=4&spm_id_from=333.788.videopod.episodes)

  ```c
  #include <stdio.h>
  int i=5;
  int main(void)
  {
     while(i)  //while(i--) while(--i)//--1先加减后判断i   i--先判断后加减
     {
      printf("%d\n", i);
      i--;
      //i++;
      //i=i-1;
      //i-=1;
     }
  }
  
  
  do
     {
      printf("%d\n", i);
      i--;
     }while(i)             //先执行再判断循环
     
  ```

  &&与 

```c
#include <stdio.h>

int i;
int main(void)
{
for(i=5;i>0;i--)// 中间判断 左右都执行 ;分隔
    {if(i==1)
         break;//退出)
    


    if(i==3)
         continue;//跳过

    }
    
}
        
```

学习了while  for 等循环      逻辑判断先后顺序 continue  break if