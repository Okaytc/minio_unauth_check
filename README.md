# minio_unauth_check
CVE-2023-28432,minio未授权访问检测工具

**本工具仅用于教育和研究目的，以提高安全意识和改进软件开发实践。在使用本工具之前，请确保您遵守了相关法律法规和道德准则。**

开发环境： python3

```python
使用方式（支持单个URL检测和批量检测）：//url做了合规处理，支持输入ip、ip:port样式

单个检测：python minio_unauthcheck.py -u

示例：python minio_unauthcheck.py -u http://192.168.1.1/

批量检测：python minio_unauthcheck.py -f

示例：python minio_unauthcheck.py -f url.txt
```

演示截图：

单个检测：

![图片](https://user-images.githubusercontent.com/50813688/227418128-8298aa20-0a68-43cd-8333-5d5b7a786fb1.png)


批量检测:

![图片](https://user-images.githubusercontent.com/50813688/227418406-06c24f04-d353-4ce0-a710-bd2005f512c7.png)
