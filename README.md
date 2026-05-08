# clash-rules

Custom Clash/Mihomo rule-provider files.

## Files

- `ruleset/Bilibili.yaml`
- `ruleset/Overseas-AI.yaml`

## Example

```yaml
rule-providers:
  Bilibili:
    type: http
    behavior: classical
    url: "https://raw.githubusercontent.com/nurob-l/clash-rules/master/ruleset/Bilibili.yaml"
    path: ./ruleset/Bilibili.yaml
    interval: 86400

  Overseas-AI:
    type: http
    behavior: classical
    url: "https://raw.githubusercontent.com/nurob-l/clash-rules/master/ruleset/Overseas-AI.yaml"
    path: ./ruleset/Overseas-AI.yaml
    interval: 86400
```
