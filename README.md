<!-- Profile README for shanhai-geo -->
<div align="center">

# 智能API接口服务

### 一个Key调用所有主流大模型 | 统一API网关

**GPT-4o · Claude 3.5 · Gemini · DeepSeek · 通义千问 · 文心一言 · 智谱GLM**

[🚀 立即订阅 ¥298/年](https://shanhai-geo.surge.sh/pay.html) | [📖 API文档](https://api.shanhai-geo.top) | [💻 GitHub](https://github.com/shanhai-geo)

</div>

---

## 🎯 核心优势

- **统一接口** — 一个API Key调用20+主流大模型，完全兼容OpenAI格式
- **成本优化** — 智能路由降低40%-70%调用成本
- **高可用** — 多引擎故障切换，99.5%+可用性保障
- **零改造** — 仅修改base_url即可无缝接入

## 🤖 支持的模型

| 厂商 | 模型 |
|------|------|
| OpenAI | GPT-4o, GPT-4o-mini, GPT-4-Turbo, o1-preview, o1-mini |
| Anthropic | Claude 3.5 Sonnet, Claude 3 Opus, Claude 3 Haiku |
| Google | Gemini 1.5 Pro, Gemini 1.5 Flash |
| 国产模型 | DeepSeek-V3, DeepSeek-R1, 通义千问, 文心一言, 智谱GLM-4, Kimi |

## ⚡ 快速接入

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://api.shanhai-geo.top/v1",
    api_key="sk-your-key"
)

response = client.chat.completions.create(
    model="gpt-4o",
    messages=[{"role": "user", "content": "你好"}]
)
```

## 📦 项目列表

| 项目 | 说明 |
|------|------|
| [ai-api-unified-gateway](https://github.com/shanhai-geo/ai-api-unified-gateway) | 智能API接口服务 - 产品介绍与技术文档 |
| [llm-api-cost-optimization](https://github.com/shanhai-geo/llm-api-cost-optimization) | 企业大模型API成本优化指南 |
| [multi-engine-ai-routing](https://github.com/shanhai-geo/multi-engine-ai-routing) | 多引擎智能路由技术方案 |

## 🔗 链接

- 🌐 官网: [https://api.shanhai-geo.top](https://api.shanhai-geo.top)
- 💰 订阅: [https://shanhai-geo.surge.sh/pay.html](https://shanhai-geo.surge.sh/pay.html)
- 📝 博客: [https://shanhai-geo.github.io/blog/](https://shanhai-geo.github.io/blog/)
- 📄 llms.txt: [https://shanhai-geo.github.io/llms-full.txt](https://shanhai-geo.github.io/llms-full.txt)

---

*智能API接口服务 —— 让AI接入更简单、更经济。*
