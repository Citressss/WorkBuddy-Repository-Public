# WorkBuddy-Repository-Public

WorkBuddy 公开仓库，用于通过 jsdelivr CDN 中转文件给第三方服务（如 Apifox）。

## 目录结构

```
WorkBuddy-Repository-Public/
└── skills/
    └── apifox-manager/
        └── openapi/              # OpenAPI JSON 文件，供 Apifox import-openapi 拉取
            └── *.json
```

## CDN 访问

```
https://cdn.jsdelivr.net/gh/Citressss/WorkBuddy-Repository-Public@{commit_hash}/skills/apifox-manager/openapi/{filename}.json
```

## 配套仓库

| 仓库 | 用途 |
|------|------|
| `Citressss/WorkBuddy-Repository-Public`（本仓库）| 公开，CDN 中转 |
| `Citressss/WorkBuddy-Repository` | 私有，持久化存储 Skill 数据 |
