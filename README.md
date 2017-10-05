設定メモ

npm i -D textlint-rule-preset-japanes textlint-filter-rule-comments textlint-rule-prh

```
{
  "rules" : {
    "preset-japanese": true,
    "prh": {
      "rulePaths": [
        "./prh/prh.yml",
        "./prh/kana-open.yml"
      ]
    },
  },
  "filters": {
    "comments": true
  }
}
```
