## 获取STS

```
GET /oss/v1/sts
```

> 认证: Header里Bearer token, token来源, 业务服务器
> 请求参数: bucket, dir(文件夹)
> 实际保存的文件夹为 ${bucket}/qpscv4/${dir}
