# clash_yaml_academic
为clash配置的学术规则

# 使用方式
在配置文件中添加：
```
rule-providers:
  Academic:
    type: http
    behavior: classical
    format: yaml
    path: ./rule/Academic.yaml
    url: "https://raw.githubusercontent.com/SherlockChiang/clash_yaml_academic/main/academic.yaml"
    interval: 86400
```
```
rules:
  - RULE-SET,Academic,直连
```
*如果用不了那么八成是校园网或者gfw又把直连墙了。唉，卡脖子。*
