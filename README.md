# Purchase Shared Data

这个仓库现在专门用于共享 `Wmix采购系统` 的无价格业务数据。

仓库里会保留：

- 供应商基础信息
- 商品基础信息
- 订货单
- 收货单

仓库里不会保留：

- 商品单价
- 成本项 / 成本结构
- 价格历史
- 任何内部价格权限信息

当前主文件：

- `shared-data/wmix-shared-latest.json`
- `shared-view.html`

这份 JSON 适合：

- 给同事共享日常业务数据
- 作为公开仓库备份
- 作为后续同步到其他系统的数据源

更友好的共享入口：

- 页面版：`https://cdn.jsdelivr.net/gh/Emilyahuang/Purchase@main/shared-view.html`
- 原始 JSON：`https://raw.githubusercontent.com/Emilyahuang/Purchase/main/shared-data/wmix-shared-latest.json`

如果以后需要价格权限，请单独使用私有仓库或私有文件分发，不要放进这个公开仓库。
