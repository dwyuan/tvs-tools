### 取消事件
```json
{
    "event": {
        "header": {
            "namespace": "ExceptionReporter",
            "name": "Cancel",
            "messageId": "{{STRING}}"
        },
        "payload": {
            "token": "{{STRING}}",
            "dialogRequestId": "{{STRING}}"
        }
    }
}
```

***Header Paramters***

|    Parameter            |    Type        |    必选    |    描述                            |
|    :-------------------    |    :--------    |    :-----    |    :-----------------------------    |
|    messageId            |    string    |    Yes    |    消息ID                        |

***Payload Paramters***

|    Parameter                    |    Type        |    必选    |    描述                                    |
|    :---------------------------    |    :--------    |    :-----    |    :-----------------------------------    |
|    token                        |    string    |    No    |    ExpectSpeech指令的token    |
|    dialogRequestId            |    string    |    No    |    对话ID                                |

### 退出多轮事件
```json
{
    "event": {
        "header": {
            "namespace": "ExceptionReporter",
            "name": "ExitMultiTurn",
            "messageId": "{{STRING}}"
        },
        "payload": {
            "token": "{{STRING}}"
        }
    }
}
```

***Header Paramters***

|    Parameter            |    Type        |    必选    |    描述                            |
|    :-------------------    |    :--------    |    :-----    |    :-----------------------------    |
|    messageId            |    string    |    Yes    |    消息ID                        |

***Payload Paramters***

|    Parameter                    |    Type        |    必选    |    描述                                    |
|    :---------------------------    |    :--------    |    :-----    |    :-----------------------------------    |
|    token                        |    string    |    No    |    ExpectSpeech指令的token    |