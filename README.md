# HttpLearning
http学习资料（yueqingshu@proton.me）

## http报文格式
http是基于tcp协议实现的，其报文氛围**请求报文**和**响应报文**，  
**请求报文**  
```
POST /api/user HTTP/1.1
Content-Type: application/json

{
    "username": "three Zhang"
}
```
**响应报文**  
```
HTTP/1.1 200 OK
Content-Type: application/json

{
    "status": "OK"
}
```
**请求方式**
