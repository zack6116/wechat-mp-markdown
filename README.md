# wechat-mp-markdown

让 Claude 或 Codex 写出 [公众号 MD Paste](https://coderfather.com/wechat-markdown/) 能直接导入的 Markdown。图片用 `![说明](images/01.png)` 或公网 https 地址，导入时由扩展自动上传。

## Claude 和 Codex 安装

```bash
npx skills add zack6116/wechat-mp-markdown -a claude-code -a codex -g -y
```

需要本机有 Node.js。

也可以下载压缩包后手动放置：[wechat-mp-markdown.zip](https://coderfather.com/wechat-markdown/wechat-mp-markdown.zip)。解压后把 `wechat-mp-markdown` 文件夹放到 Claude 的 `~/.claude/skills/`，或 Codex 的 `~/.agents/skills/`。

规则在 [SKILL.md](SKILL.md)。

## 许可证

尚未选择开源许可证，版权保留。可以安装到自己的 Claude、Codex 或 Cursor 里使用。
