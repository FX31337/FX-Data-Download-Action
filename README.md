# FX Data Download 🐳 Action

<!-- [![Release][github-release-image]][github-release-link] -->
<!-- [![Docker image][docker-build-image]][docker-build-link] -->
[![Status][gha-image-action-master]][gha-link-action-master]
[![Status][gha-image-docker-master]][gha-link-docker-master]
[![Status][gha-image-lint-master]][gha-link-lint-master]
[![Telegram channel][tg-channel-image]][tg-channel-link]
[![Telegram chat][tg-chat-image]][tg-chat-link]
[![Edit][gitpod-image]][gitpod-link]

This GitHub Action downloads Forex historical data.

## Main Inputs

### `Pairs`

Pair(s) to download (separated by comma).

## Period Inputs

### `Years` (int/string)

Year(s) to download (separated by comma). Default: `2020`.

### `Months` (int/string)

Months(s) to download (separated by comma). Default: `1`.

### `Days` (int/string)

Day(s) to download (separated by comma). Default: `1`.

### `Hours` (int/string)

Hour(s) to download (separated by comma). Default: `all`.

<!--
## Outputs

### `foo`

Foo bar.
-->

## Example usage

```yaml
uses: ea31337/fx-data-download-action@master
```

## Related actions

- To convert CSV file into different formats,
  use [FX-Data-Convert-Action](https://github.com/EA31337/FX-Data-Convert-Action) action.
- To generate CSV file instead,
  use [FX-Data-Generate-Action](https://github.com/EA31337/FX-Data-Generate-Action) action.

### Support

- For bugs/features, raise a [new issue at GitHub](https://github.com/EA31337/FX-Data-Download-Action/issues).
- Join our [Telegram group][tg-chat-link] and [channel][tg-channel-link] for help.

<!-- Named links -->

[github-release-image]: https://img.shields.io/github/release/EA31337/FX-Data-Download-Action.svg?logo=github
[github-release-link]: https://github.com/EA31337/FX-Data-Download-Action/releases

[tg-channel-image]: https://img.shields.io/badge/Telegram-news-0088CC.svg?logo=telegram
[tg-channel-link]: https://t.me/EA31337_News
[tg-chat-image]: https://img.shields.io/badge/Telegram-chat-0088CC.svg?logo=telegram
[tg-chat-link]: https://t.me/EA31337

[gha-link-action-master]: https://github.com/EA31337/FX-Data-Download-Action/actions?query=workflow%3AAction+branch%3Amaster
[gha-image-action-master]: https://github.com/EA31337/FX-Data-Download-Action/workflows/Action/badge.svg
[gha-link-docker-master]: https://github.com/EA31337/FX-Data-Download-Action/actions?query=workflow%3ADocker+branch%3Amaster
[gha-image-docker-master]: https://github.com/EA31337/FX-Data-Download-Action/workflows/Docker/badge.svg
[gha-link-lint-master]: https://github.com/EA31337/FX-Data-Download-Action/actions?query=workflow%3ALint+branch%3Amaster
[gha-image-lint-master]: https://github.com/EA31337/FX-Data-Download-Action/workflows/Lint/badge.svg

[gitpod-image]: https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod
[gitpod-link]: https://gitpod.io/#https://github.com/EA31337/FX-Data-Download-Action
