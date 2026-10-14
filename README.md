# 林大厨 · 数据仓库

私有仓库，存放菜谱数据与图片，由 App 通过 GitHub API 读写，请勿手工编辑。

- index.json：菜谱摘要索引（含 updatedAt 与 sha，用于增量同步）
- recipes/<dishId>.json：单个菜谱（含食材与步骤）
- images/<dishId>/：封面与步骤图
- menus/：对外发布的菜单快照
