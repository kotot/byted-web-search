# byted-web-search (mirror)

火山引擎豆包搜索 Skill 的个人镜像仓库。原始来源与官方分发渠道：

```bash
npx skills add https://skills.volces.com/skills/bytedance/agentkit-samples -s byted-web-search --agent openclaw
```

即 [bytedance/agentkit-samples](https://skills.volces.com) 中的 `byted-web-search` 子目录，作者 `volcengine-search-team`（见 `byted-web-search/SKILL.md` frontmatter）。本仓库依据其 Apache License 2.0（见 `byted-web-search/LICENSE`）原样镜像，仅将 skill 内容整体挪进 `byted-web-search/` 子目录（`npx skills add owner/repo` 类安装工具要求 `SKILL.md` 不在仓库根目录，否则只会安装 `SKILL.md` 单文件、丢弃 `scripts/`、`references/`），未改动其余内容。

用于个人测试环境里以 `npx skills add kotot/byted-web-search -g -y` 方式独立安装，不代表官方分发渠道的替代。
