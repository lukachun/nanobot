---
name: weather
description: 根据城市查询当地天气
homepage: https://uapis.cn/api/v1/misc/weather
---

# 天气查询

使用 uapis.cn 免费天气API查询当前天气信息，支持中文城市名称，无需API密钥。
此技能使用返回结果中的所有字段，包括 `weather`（天气状况）、`temperature`（温度）、`humidity`（湿度）、`wind_direction`（风向）、`wind_power`（风力等级）等

## 快速开始

### 基础查询

# 查询北京天气
curl -s "https://uapis.cn/api/v1/misc/weather?city=北京&lang=zh"

# 查询上海天气
curl -s "https://uapis.cn/api/v1/misc/weather?city=上海&lang=zh"

# 查询广州天气
curl -s "https://uapis.cn/api/v1/misc/weather?city=广州&lang=zh"

