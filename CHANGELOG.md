# Changelog

## 1.0.1

- Add MCP tool annotations to all five tools: `readOnlyHint: true` (the tools
  read/capture and never mutate the caller's own resources) and
  `openWorldHint: true` (they fetch arbitrary external URLs). Required by the
  Anthropic Connectors and OpenAI Apps directories; absent annotations are a
  common cause of directory rejection.

## 1.0.0

- Initial release: stdio MCP server with `take_screenshot`,
  `bulk_screenshots`, `compare_screenshots`, `run_lighthouse`,
  `capture_sitemap`, backed by the ScreenshotInk REST API.
