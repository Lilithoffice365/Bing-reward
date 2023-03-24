# Bing-reward
Auto Search
### 青龙 部署

1. `依赖管理`——`新建依赖`——nodejs

```bash
axios@1.1.3
https-proxy-agent
```

2. `定时任务`——`新建任务`

```bash
# 命令
ql raw https://raw.githubusercontent.com/emtry/Bing-Auto-Search/main/Bing-Auto-Search.js

# 定时规则
0 0 15 * * *
```

3. `环境变量`–`新建变量`

```bash
# 名称
BingAutoSearch_MicroSoft_COOKIE

# 值
填入获取的Cookie
```

4. 运行新建的任务获取脚本`raw_main_Bing-Auto-Search.js`，并设置每天下午5点自动执行脚本
```bash
# 定时规则
0 0 17 * * *
```
