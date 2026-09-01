# cursor_kimi_web_resource

所有网页项目（Cursor / Kimi 协作产出）的统一资产仓库（图床/静态资源），按项目分文件夹。
通过 jsDelivr 引用：`https://cdn.jsdelivr.net/gh/meatbird/cursor_kimi_web_resource@main/<项目文件夹>/<文件名>`

## 资产索引

| 文件夹 | 所属项目 | 内容 | 数量 |
|---|---|---|---|
| `cocktail-genome/` | 鸡尾酒基因浏览器（cursor_web 仓 proj/cocktail-genome 分支） | 鸡尾酒照片（Wikimedia 266 + AI 生成 343 + web 17） | 626 |

## 规则

- **本仓必须保持 public**，否则 jsDelivr 无法取图；
- 新项目立项时在本表登记一行，再建同名文件夹放资产；
- 文件名 ↔ 业务 id 的映射由各项目仓库自己维护（如 photos-map.json）；
- 单文件不要超过 20MB（jsDelivr 上限）；
- jsDelivr 对 @main 有缓存（约 12h），紧急更新可在 URL 中用 @<commit> 钉版本。
