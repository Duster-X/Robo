- 9月19日

  [第5讲数组和指针入门_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1bcYxzWEEN/?buvid=XU7729D7A2792CF4E75591374782D433105CF&from_spmid=search.search-result.0.0&is_story_h5=false&mid=Sl9k5ak8nyE%2BTJCzHP5%2BdA%3D%3D&plat_id=116&share_from=ugc&share_medium=android&share_plat=android&share_session_id=688d113d-a163-49c4-83aa-dc7988a2e863&share_source=QQ&share_tag=s_i&spmid=united.player-video-detail.0.0&timestamp=1789213278&unique_k=SQ3PbrH&up_id=1041194501&vd_source=62e22450d7f4d5f6d645f4008e9fae75&spm_id_from=333.788.videopod.episodes&p=6)



```C
#include <stdio.h>
int student1 = 67;
int student2 = 69;
int student3 = 91;
int num;
int main() {
     printf("请输入学生编号(1-3): ");
     scanf("%d", &num);
    switch (num) {
        case 1:
            printf("学生1的成绩为%d", student1);
            break;
        case 2:
            printf("学生2的成绩为%d", student2);
            break;
        case 3:
            printf("学生3的成绩为%d", student3);
            break;
        default:
            printf("未知学生");
    }
    return 0;
}
```

```c
#include <stdio.h>
int student[3]={0};
int i;
int j;

int main(void)
{
    for(i=0;i<3;i++)
    {
        printf("输入学生学号: ");
        scanf("%d",&j);
        printf("输入学生成绩: ");
            scanf("%d",&student[j-1]);
            
    }
    
    
}
```

我力竭了。周六没有歇下来全天高强度与人交流。明天再完成剩下的部分吧。

