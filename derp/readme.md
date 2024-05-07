# 注意事项

```
1. HostName 直接填 derper 的公网 IP，即和 IPv4 的值相同。
2. InsecureForTests 一定要设置为 true，以跳过域名验证。
3. Regions 是对象，下面的每一个对象表示一个可用区，每个可用区里面可设置多个 DERP 节点，即 Nodes。
4. 每个可用区的 RegionID 不能重复。
5. 每个 Node 的 Name 不能重复。
6. RegionName 一般用来描述可用区，RegionCode 一般设置成可用区的缩写
7. DERPPort为docker运行的derper服务443端口映射出来的端口

上面的配置中域名和 IP 部分，你需要根据你的实际情况填写
```

> derp ip 模式