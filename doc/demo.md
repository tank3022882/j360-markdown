用户登录
===
### 请求Url

    /login.action

### 请求方法

    Post
    
### 请求参数

|参数名 | 参数类型 | 是否必填 | 描述 | 
|---|---|---|---|
|username | String | 必填 | 用户账号 | 
|password | String | 必填 | 用户密码 |

### 调用样例

    /login.action?username=username&password=password
    
### 返回结果

	{
		"result":{
			"errorCode":1,
			"errorMessage":""
		}
		"data":{
			"modifyDate":"2015-08-31 09:24:36",
			"createDate":"2014-03-04 09:51:33",
			"id":"001",
			"name":"用户"
		}
	}
	
### 异常返回结果

    {
		"result":{
			"errorCode":0,
			"errorMessage":"用户名或密码错误"
		}
		"data":{}
	}
	
#### result

| 字段名 | 描述 | 
|---|---|
| errorCode | 返回状态码 <br/> 1：成功 <br/> 0：失败 | 
| errorMessage | 返回状态描述 <br/> 如：操作失败 |
	
#### data

| 字段名 | 描述 | 
|---|---|
| modifyDate | 修改时间 | 
| createDate | 创建时间 |
| id | 用户ID |
| name | 用户名称 |