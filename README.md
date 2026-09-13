# My GitHub Starred Repositories

自动生成的 GitHub 星标仓库列表，按 ⭐ 降序排序。

- **stars.md** — 完整列表（694 个仓库，含语言与描述，⭐ 降序）
- **stars.csv** — 同一份数据的 CSV 版本，便于表格工具/脚本处理

生成时间：2026-09-13

## 重新生成

```bash
gh api "/user/starred?per_page=100&page=1" --jq '.[].full_name'
```
