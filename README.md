# 大奥克兰房价热力图

按 suburb 的房价热力图，点开任一郊区可看简介与区内 35 米网格的政府估价热力图，
右下角有一个按预算优先推荐郊区的助手。

**[打开页面 →](https://qisun317.github.io/auckland-house-heatmap/)**

单个静态 HTML，无后端、无追踪、无 cookie。

## 免责声明

个人研究项目，**不构成投资或购房建议**。页面上所有价格都是**估值**（自动估值模型与
议会政府估价 CV），**不是成交价**，个体房产可能与之相差很大。做决定前请咨询持牌中介、
注册估价师或财务顾问。

## 数据来源

| 来源 | 内容 | 许可 |
|---|---|---|
| [LINZ](https://data.linz.govt.nz/layer/113764-nz-suburbs-and-localities/) | NZ Suburbs and Localities 边界 | CC BY 4.0 |
| [Auckland Council](https://data-aucklandcouncil.opendata.arcgis.com/) | 逐地块政府估价（页面上按 35 米网格聚合，不含地址） | 公开图层 |
| [Opes Partners](https://www.opespartners.co.nz/property-markets/auckland) | 各 suburb 平均房产估值、租金、回报、成交 | — |
| [English Wikipedia](https://en.wikipedia.org/) | 郊区简介摘要 | CC BY-SA 4.0 |

议会估价数据在页面上是 **35 米网格中位数的聚合形式**，不包含地址级明细。
如果你是上述任一数据的权利方、认为此处的使用方式不妥，请开一个 issue，我会处理。

生成这个页面的流水线代码在另一个私有仓库。
