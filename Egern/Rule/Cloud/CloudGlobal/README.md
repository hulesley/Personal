# 🧸 全球云计算

## 前言

![](https://shields.io/badge/-移除重复规则-ff69b4) ![](https://shields.io/badge/-DOMAIN与DOMAIN--SUFFIX合并-green) ![](https://shields.io/badge/-DOMAIN--SUFFIX间合并-critical) ![](https://shields.io/badge/-DOMAIN与DOMAIN--KEYWORD合并-9cf) ![](https://shields.io/badge/-DOMAIN--SUFFIX与DOMAIN--KEYWORD合并-blue) ![](https://shields.io/badge/-IP--CIDR(6)合并-blueviolet) 

全球云计算规则由《RULE GENERATOR 规则生成器》自动生成。

分流规则是互联网公共服务的域名和IP地址汇总，所有数据均收集自互联网公开信息，不代表我们支持或使用这些服务。

请通过【中华人民共和国 People's Republic of China】合法的互联网出入口信道访问规则中的地址，并确保在使用过程中符合相关法律法规。

## 规则统计

最后更新时间：2024-07-03 16:17:43

各类型规则统计：
| 类型 | 数量(条)  | 
| ---- | ----  |
| DOMAIN-SUFFIX | 19  | 
| IP-CIDR | 1983  | 
| IP-CIDR6 | 859  | 
| TOTAL(仅供参考) | 2861  | 


## Egern 

#### 使用说明
- CloudGlobal.yaml，请使用RULE-SET。
- CloudGlobal_Resolve.yaml，请使用RULE-SET。

#### 文件区别
- CloudGlobal_Resolve.yaml与CloudGlobal.list的区别仅在于后者IP-CIDR(6)类型带no-resolve。

#### 配置建议
- CloudGlobal.yaml 单独使用。
- CloudGlobal_Resolve.yaml 单独使用。

#### 规则链接
**X分支 (每日更新)**

https://raw.githubusercontent.com/hulesley/Personal/X/Egern/Rule/Cloud/CloudGlobal/CloudGlobal.yaml











## 子规则/排除规则

当前分流规则，已包含以下子规则，除非特殊需求否则不建议重复引用：
| 子规则  |  |  | 
| ---- | ---- | ----  |
| AkamaiCloud | AmazonCloud | HiNet  | 


## 数据来源

《全球云计算》的数据来自以下链接，如与本项目的《全球云计算》规则混合使用，可能会造成规则大量重复。

- https://raw.githubusercontent.com/LM-Firefly/Rules/master/CCC-Global/Akamai.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/CCC-Global/Amazon.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/CCC-Global/HiNet.list
- https://raw.githubusercontent.com/LM-Firefly/Rules/master/CCC-Global.yaml


感谢以上规则作者的辛勤付出（排名不分先后）。

## 最后

### 感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) [@chenyiping1995](https://github.com/chenyiping1995) [@vhdj](https://github.com/vhdj)

提供规则数据源及改进建议。

### 其他

请不要对外宣传本项目。