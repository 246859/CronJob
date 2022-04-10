# CronJob
QQ machine group server timing task system plug-in based on node-cron

需要 Nilbrige 和 node-cron 前置

配置文件注释

```txt
{
   "test":{
        "enable":false,//是否启用该定时任务
        "severName":"测试",//对应服务器名字
        "cronEx":"0 * * * * *",//cron表达式
        "chatJob":{
            "enable":true,
            "chatMsg":"测试",//发送的聊天信息
        },
        "cmdJob":{//对服务器发送指令
            "enable":false,
            "cmd":""
        },
        "serverJob":{//服务器开关操作
           "enable":false,
           "type":1//-1 关服,1 开服
        },
    }
}
```

