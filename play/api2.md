# user

 *  GET    /users[/]        => user.list()
 *  GET    /users/new       => user.new()
 *  GET    /users/:id       => user.show()
 *  GET    /users/:id/edit  => user.edit()
 *  POST   /users[/]        => user.create()
 *  PATCH  /users/:id       => user.update()
 *  DELETE /users/:id       => user.destroy()
 
## GET    /users/:id/edit

这是一个post2请求

### 请求连接 

http://218.247.15.102/appfuse_emm_backend/v1/appschedule/list.json

### 请求类型 

post

### 请求参数

```
没有参数
```

### 响应内容 (请求失败)

#### 错误信息

```
{
    "cause": {
        "code": "ENETUNREACH",
        "errno": "ENETUNREACH",
        "syscall": "connect"
    }
}
```



## GET    /users/new

这是一个get请求

### 请求连接 

http://218.247.15.102/appfuse_emm_backend/v1/appversions.json

### 请求类型 

get

### 请求参数

```
没有参数
```

### 响应内容 (请求失败)

#### 错误信息

```
{
    "cause": {
        "code": "ENETUNREACH",
        "errno": "ENETUNREACH",
        "syscall": "connect"
    }
}
```

### 描述 
 - aaaa
 - bbb


## PATCH  /users/:id

这是一个upload请求

### 请求连接 

http://127.0.0.1:3456/post/formdata.json

### 请求类型 

upload

### 请求参数

```
{
    "names": "pic",
    "filename": "da_qin_huang_ling_.mobi"
}
```

### 响应内容 (请求成功)

#### 响应体内容

```
{
    "data": {
        "path": "/Users/sang/test"
    },
    "status": {
        "code": 0,
        "msg": "success."
    }
}
```



