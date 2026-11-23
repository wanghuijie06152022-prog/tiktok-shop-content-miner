# TikTok Shop Content Miner

TikTok Shop 图文案例拆解与 AI 创作 Skill。支持读取持续更新的日用家纺及全品类图文榜单，按品类、内容类型、AOV和真实GMV证据筛选案例，并完成商品Brief、创意、分镜、视觉规范和逐张制作指令。

## 实时案例源

- [日用家纺行业专属－优质图文内容榜单](https://bytedance.sg.larkoffice.com/base/HItOb9EmmarvbjsdvbTlPkQHgHb?table=tblHzigDo2GfiEgK&view=vewUg1CAvT)
- [🔥 优质图文榜单（持续更新）](https://bytedance.sg.larkoffice.com/base/YrsUb0baMa6OpRsSdXxl01wLgWh?table=tbl5onwbm2IeHpPV&view=vewUCAwef1)

两个链接指向实时视图。维护者更新榜单后，AI 在下一次调用 Skill 时读取当前内容，无需重新发布 Skill。Skill 不会在后台自动同步或保存榜单副本；能否读取取决于使用者的账号权限。无法访问时，需要提供有权导出的 Excel/CSV 或筛选结果。

## 安装

下载本仓库后，将 `tiktok-shop-content-miner` 文件夹复制到你的 Codex skills 目录：

```bash
mkdir -p ~/.codex/skills
cp -R tiktok-shop-content-miner ~/.codex/skills/
```

重新打开会话后，即可调用 `$tiktok-shop-content-miner`。

## 使用示例

> 使用 $tiktok-shop-content-miner。我的商品是[商品信息]，目标市场为美国。请从我提供的案例库中寻找品类和AOV相近的高GMV案例，拆解HOOK、BODY、商品证明和CTA，提炼可复用结构。完成案例学习前不要直接生成图片。

## 工作流

案例学习 → Product & Content Brief → Creative Brainstorming → Storyboard → Visual Style Guide → 逐张制作 → 后期配文与发布复盘。

公开版不打包商家经营数据或案例素材，只保存实时榜单入口和分析方法。安装本 Skill 不会自动获得任何平台或知识库权限。

## License

MIT License。你可以自由使用、修改和分发本项目，但应保留原始版权和许可声明。
