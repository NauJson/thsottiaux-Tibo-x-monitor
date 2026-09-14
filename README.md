# thsottiaux-x-monitor

自动监控 X (Twitter) 用户 [@thsottiaux](https://x.com/thsottiaux) (Tibo, Codex & ChatGPT @OpenAI) 的最新发帖和回复情况。

## 功能
- 定时扫描 @thsottiaux 的最新推文（发帖）及其回复互动情况
- 将扫描记录更新到本仓库的 `logs/` 目录
- 每天早上 6:00 至晚上 23:00（香港时间）每小时执行一次监控

## 目录结构
- `logs/`：按日期存储的扫描日志（Markdown 格式）
- `latest.md`：最新一次扫描摘要

## 自动化
由 Grok Automations 驱动，使用 X 搜索工具抓取数据并推送到本仓库。

## 仓库
- Owner: NauJson
- Repo: https://github.com/NauJson/thsottiaux-x-monitor
