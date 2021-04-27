> 小米运动 `bash mimotion.sh $PARAMETER`  

####  使用AC每天自动运行
* Fork后进入仓库,点击`Settings`,右侧栏点击`Secrets`,点击`New secret`,添加`PARAMETER`的值为脚本支持的参数,间隔符使用空格  

| PARAMETER参数 | 说明 |
| -------- | ----- |
| `18812345678@password@10000-20000` | 账号@密码@随机步数起止点,可多次传入支持多账号 |
| `token@*** chat_id@***` | 为telegram bot通知所需参数，无则不进行信息通知 |
| `others` | 其它说明查看脚本内容 |

* 默认每天运行一次,也可再参数设置完毕后点击star仓库立即促发ac运行  

#### thanks:  
* jd_docker
* [mimotion](https://github.com/Squaregentleman/mimotion)