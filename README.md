#  大华智慧园区综合管理平台任意密码读取漏洞 EXP
由于该平台未对接口权限做限制，攻击者可以从user_getUserInfoByUserName.action接口获取任意用户密码(MD5格式)
```
Usage:
  python3  SMART-PARK.py -h
```
![示例](https://github.com/gallopsec/SMART_PARK_ReadPasswd/blob/main/poc.png)
![示例](https://github.com/gallopsec/SMART_PARK_ReadPasswd/blob/main/test1.png)
![示例](https://github.com/gallopsec/SMART_PARK_ReadPasswd/blob/main/test.png)
