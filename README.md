# A票长红 · 公共数据通道

这个仓库只存放 A票长红 的**公共数据包**（行情/评分/决策/策略/广度），不包含任何个人持仓、亏损、私有备注。

- `latest_meta.json`：版本/大小/校验信息
- `latest_data.txt`：数据包，`GZ1:` + base64(gzip(JSON))

App / 桌面端通过 jsDelivr 读取：
`https://cdn.jsdelivr.net/gh/toshiba888/apch-data@main/latest_meta.json`
