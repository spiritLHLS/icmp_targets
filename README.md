# icmp_targets

闭源爬虫解析CN全国三大运营商可用ICMP的Ping地址，每日更新

`nodes.json` 字段:

- `province`: 省份/直辖市/自治区名称
- `isp_code`: 运营商代码
- `isp`: 运营商名称
- `ip_version`: `v4` 或 `v6`
- `ips`: 可用 IP 列表，逗号分隔
- `latency_ms`: 最优延迟，缺失时为空字符串
- `quality_score`: 质量评分，缺失时为空字符串
- `ips_latency_ms`: `ips` 中每个 IP 对应的延迟，逗号分隔
