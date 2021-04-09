# FX Data Download 🐳 Action

[![Tag][github-tag-image]][github-tag-link]
[![Status][gha-image-action-master]][gha-link-action-master]
[![Status][gha-image-docker-master]][gha-link-docker-master]
[![Status][gha-image-lint-master]][gha-link-lint-master]
[![Channel][tg-channel-image]][tg-channel-link]
[![Edit][gitpod-image]][gitpod-link]

This GitHub Action downloads Forex historical data.

By default it downloads and converts the files to CSV format.

## Usage

For full documentation, please read: [GitHub Actions Documentation](https://help.github.com/en/actions).

### Latest release

```yaml
uses: fx31337/fx-data-download-action@v1
```

### Specific release

```yaml
uses: fx31337/fx-data-download-action@v1.0.0
```

Note: Check _Releases_ for more details.

### Latest development version

```yaml
uses: fx31337/fx-data-download-action@master
```

### Overriding default inputs

```yaml
uses: fx31337/fx-data-download-action@master
with:
    Pairs: 'EURUSD'
    Years: 2020
    Months: 1-2
```

## Inputs

### Main Inputs

#### `Pairs` (string)

Pair(s) to download (separated by comma). Default: `EURUSD`.

### Period Inputs

#### `Years` (int/string)

Year(s) to download (separated by comma). Default: `2020`.

#### `Months` (int/string)

Months(s) to download (separated by comma). Default: `1`.

#### `Days` (int/string)

Day(s) to download (separated by comma). Default: `1`.

#### `Hours` (int/string)

Hour(s) to download (separated by comma). Default: `all`.

### Other Inputs

#### `CmdArgs`

Extra arguments to pass to the script. Default: `-v` (for verbose output).

<!--
## Outputs

### `foo`

Foo bar.
-->

## Related actions

- To convert CSV file into different formats,
  use [FX-Data-Convert-Action](https://github.com/FX31337/FX-Data-Convert-Action)
  action.
- To generate CSV file instead,
  use [FX-Data-Generate-Action](https://github.com/FX31337/FX-Data-Generate-Action)
  action.

## Support

- For bugs/features, raise a [new issue at GitHub](https://github.com/FX31337/FX-Data-Download-Action/issues).

<!-- Named links -->

[github-tag-image]: https://img.shields.io/github/tag/FX31337/FX-Data-Download-Action.svg?logo=github
[github-tag-link]: https://github.com/FX31337/FX-Data-Download-Action/tags

[tg-channel-image]: https://img.shields.io/badge/Telegram-join-0088CC.svg?logo=telegram
[tg-channel-link]: https://t.me/EA31337

[gha-link-action-master]: https://github.com/FX31337/FX-Data-Download-Action/actions?query=workflow%3AAction+branch%3Amaster
[gha-image-action-master]: https://github.com/FX31337/FX-Data-Download-Action/workflows/Action/badge.svg
[gha-link-docker-master]: https://github.com/FX31337/FX-Data-Download-Action/actions?query=workflow%3ADocker+branch%3Amaster
[gha-image-docker-master]: https://github.com/FX31337/FX-Data-Download-Action/workflows/Docker/badge.svg
[gha-link-lint-master]: https://github.com/FX31337/FX-Data-Download-Action/actions?query=workflow%3ALint+branch%3Amaster
[gha-image-lint-master]: https://github.com/FX31337/FX-Data-Download-Action/workflows/Lint/badge.svg

[gitpod-image]: https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod
[gitpod-link]: https://gitpod.io/#https://github.com/FX31337/FX-Data-Download-Action
