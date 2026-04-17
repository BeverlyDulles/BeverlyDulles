# Claude Version Information / Claude 版本信息

## Current Environment / 当前环境

This repository is on the `claude/opus-4-6-version` branch, indicating it's configured for **Claude Opus 4.6**.

此仓库位于 `claude/opus-4-6-version` 分支，表示已配置为使用 **Claude Opus 4.6**。

## About Claude Models / 关于 Claude 模型

### Available Claude Models / 可用的 Claude 模型

As of January 2025, Anthropic offers several Claude models:

截至 2025年1月，Anthropic 提供以下 Claude 模型：

1. **Claude Opus 4.5** - The most capable frontier model
   - Model ID: `claude-opus-4-5-20251101`
   - Best for: Complex reasoning, research, and analysis

2. **Claude Sonnet 4.5** - Balanced performance and speed
   - Model ID: `claude-sonnet-4-5-20250929`
   - Best for: Most general-purpose tasks

3. **Claude Haiku** - Fast and efficient
   - Best for: Quick tasks, simple operations

### Claude Opus 4.6 Status / Claude Opus 4.6 状态

**Important Note / 重要说明:**

As of the current date (March 2026), **Claude Opus 4.6** is not yet released. The most recent Claude Opus model is **Opus 4.5**.

截至当前日期（2026年3月），**Claude Opus 4.6** 尚未发布。最新的 Claude Opus 模型是 **Opus 4.5**。

This branch (`claude/opus-4-6-version`) appears to be:
- A placeholder for future Opus 4.6 release
- A test branch for version naming conventions
- Prepared in advance for when Opus 4.6 becomes available

此分支（`claude/opus-4-6-version`）似乎是：
- Opus 4.6 未来发布的占位符
- 版本命名约定的测试分支
- 为 Opus 4.6 可用时提前准备

## How to Use Claude Opus / 如何使用 Claude Opus

### Via API / 通过 API

```python
import anthropic

client = anthropic.Anthropic(
    api_key="your-api-key"
)

message = client.messages.create(
    model="claude-opus-4-5-20251101",  # Use latest Opus 4.5
    max_tokens=1024,
    messages=[
        {"role": "user", "content": "Hello, Claude!"}
    ]
)
```

### Via Claude Code CLI / 通过 Claude Code 命令行

The Claude Code CLI currently uses Claude Sonnet 4.5 by default. To request a specific model, you would need to configure it according to the Claude Code documentation.

Claude Code CLI 目前默认使用 Claude Sonnet 4.5。要请求特定模型，您需要根据 Claude Code 文档进行配置。

## When Will Opus 4.6 Be Available? / Opus 4.6 何时可用？

Anthropic has not announced a release date for Claude Opus 4.6. When it becomes available:
- The model will be announced officially by Anthropic
- API access will be provided with a new model ID
- This branch may need to be updated with the correct model identifier

Anthropic 尚未宣布 Claude Opus 4.6 的发布日期。当它可用时：
- Anthropic 将正式宣布该模型
- 将提供新的模型 ID 用于 API 访问
- 此分支可能需要使用正确的模型标识符进行更新

## Current Assistant Information / 当前助手信息

The current assistant responding to you is:
- **Model**: Claude Sonnet 4.5
- **Model ID**: claude-sonnet-4-5-20250929
- **Knowledge Cutoff**: January 2025

当前回复您的助手是：
- **模型**: Claude Sonnet 4.5
- **模型 ID**: claude-sonnet-4-5-20250929
- **知识截止日期**: 2025年1月

## References / 参考资料

- [Anthropic Console](https://console.anthropic.com/)
- [Claude API Documentation](https://docs.anthropic.com/)
- [Model Comparison Guide](https://www.anthropic.com/models)
