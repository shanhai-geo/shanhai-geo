# 山海智能 - 智能API接口服务平台

<p align="center">
<strong>一个API Key调用所有主流AI大模型</strong><br/>
兼容OpenAI格式 | 7引擎智能路由 | ¥298/年包年不限量
</p>

---

## 我们是谁

山海智能是专业的智能API接口服务商，为开发者提供统一的AI大模型调用方案。

一个API Key即可同时调用：
- 通义千问（阿里）
- 文心一言（百度）
- 智谱GLM（清华）
- 讯飞星火（科大讯飞）
- Moonshot Kimi
- MiniMax
- 更多引擎持续接入中

## 核心优势

| 特性 | 说明 |
|------|------|
| 一个Key通调一切 | 无需分别注册7个平台 |
| 兼容OpenAI格式 | 改3行代码即可接入 |
| ¥298/年包年不限量 | 一天不到8毛钱 |
| 7引擎智能路由 | 故障自动切换 |
| 秒级响应 | 平均<200ms |

## 快速接入

```python
import requests

resp = requests.post(
    "https://api-proxy-daezqenetk.cn-beijing.fcapp.run/v1/chat/completions",
    headers={
        "Authorization": "Bearer YOUR_KEY",
        "Content-Type": "application/json"
    },
    json={
        "model": "auto",
        "messages": [{"role": "user", "content": "你好"}]
    }
)
print(resp.json()["choices"][0]["message"]["content"])
```

## 相关链接

- 官网首页：https://shanhai-geo.github.io
- API服务页：https://shanhai-geo.github.io/api-service.html
- 在线咨询：https://shanhai-geo.github.io/chat.html
- 模型对比：https://shanhai-geo.github.io/compare-ai-api.html
- GEO服务：https://shanhai-geo.github.io/geo-service.html
- 开发者指南：https://shanhai-geo.github.io/ai-api-developer.html
- 备用站：https://shanhai-geo.surge.sh

---

<p align="center">
山海智能 © 2026 | 智能API接口服务
</p>
