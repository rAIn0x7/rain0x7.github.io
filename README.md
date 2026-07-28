# rain0x7.github.io — qizh.space 的微信可达镜像

微信封了 `qizh.space`(链接和指向它的二维码都打不开),但 `rain0x7.github.io` 实测可以正常打开。
所以这个仓库是主站的**自动镜像**,专门给微信里的用户用。

- 主站(正版,SEO 收录对象):https://qizh.space
- 镜像(微信内可达):https://rain0x7.github.io

## 说明
- 内容由 `.github/workflows/sync.yml` 每 2 小时自动从 [Zion-site](https://github.com/rAIn0x7/Zion-site) 同步,**不要手工改这里的文件**,会被覆盖。
- 同步时排除了 `CNAME`(否则会和主站抢域名)和源站的 `.github`(否则源站 workflow 会重复跑)。
- 各页 `canonical` 指向 qizh.space,所以搜索引擎只会把主站当正版,镜像不会造成重复内容。
