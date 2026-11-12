# 消保审查 Skill（Consumer Protection Review）

> 金融消费者权益保护（消保）审查作业规范技能 · 作者：八大权益 · 版本：v1.0.1

## 简介

面向金融机构消保审查岗位的作业规范技能，对金融产品/服务的**营销宣传材料、协议条款、产品说明、定价方案、销售话术**开展消保合规性审查。提供六维审查模型、八项权益映射、风险定级规则、法规依据库、违规模式库、制度模板与沟通话术库。

## 适用场景

- **审查一份具体材料**：五类审查对象（营销宣传 A / 协议条款 B / 产品与定价 C / 销售流程 D / 制度规则 E），L1 快速扫描 / L2 逐项审查 / L3 深度审查三档深度
- **找法规依据**：法规依据库，条款全称引用，不编造监管条款
- **判断侵害了哪项权利**：八项基本权利映射（财产安全权、知情权、自主选择权、公平交易权、依法求偿权、受教育权、受尊重权、信息安全权）
- **编制/修订制度、建要点库**：消保审查制度模板与审查要点库
- **意见被业务部门驳回**：审查意见争议的沟通说服策略
- **出报表、做抽检、查覆盖**：审查覆盖率、意见采纳率统计，质量抽检与应审尽审排查

## 目录结构

```
├── SKILL.md                          # 技能主文件（受理、六维审查模型、风险定级、工作流）
├── references/
│   ├── checklist-insurance.md        # 保险类审查清单
│   ├── checklist-non-insurance.md    # 非保险类审查清单
│   ├── legal-basis.md                # 法规依据库
│   ├── rights-map.md                 # 八项权益映射
│   ├── rule-building.md              # 制度建设与要点库
│   ├── persuasion.md                 # 争议沟通说服策略
│   ├── quality-ops.md                # 覆盖率统计与质量抽检
│   ├── techniques.md                 # 审查技术要点
│   └── integration-spec.md           # 集成说明
└── templates/                        # 审查意见单、审查报告、制度文档、要点库大纲模板
```

## 安装使用

将本目录复制到 WorkBuddy 用户级技能目录：

```
~/.workbuddy/skills/consumer-protection-review/
```

在对话中直接使用触发词即可，例如"审查这份产品宣传海报""这份协议条款有什么消保风险""帮我统计本月审查覆盖率"。

## 关联技能（八大权益 · 金融消保系列）

- [投诉管理](https://github.com/openfcp/complaint-management)
- [消保检查](https://github.com/openfcp/consumer-protection-inspection)
- [消保评价](https://github.com/openfcp/consumer-protection-annual-evaluation)
- [合规销售](https://github.com/openfcp/compliance-sales)
- [金融消保专家](https://github.com/openfcp/consumer-protection-expert)
