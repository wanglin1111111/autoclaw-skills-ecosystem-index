# 🦞 AutoClaw 技能生态总索引

> **本 README 由 2026-11-21 舰队审计重写**：所有数字带盘点日期与分母口径，逐仓验活（27 个索引内链全部有效），凭证面扫描 0 命中。旧版「52 技能 / 240 测试案例 100% 通过」口径已过期，见文末修订记录。

## 舰队总画像（2026-11-21 盘点）

| 口径 | 数字 | 说明 |
|---|---|---|
| 账号仓库总数 | **123** | `gh repo list --limit 200` 实测 |
| 非 fork | 119 | — |
| 已归档（archived） | 15 | 含 2 个已归档旧仓（anti-free-riding-framework / product-launch） |
| forks | 4 | semantica / Hy-Memory / ling-cookbook + 上游镜像 |
| 本索引收录范围 | **102** | 123 − 4 fork − 15 archived − 本仓 − profile 仓 |
| 技能承载仓 | **83** | 77 单技能仓 + 6 集合仓 |
| 技能总数 | **123** | 77 单技能 + 6 集合仓内 46 个 SKILL.md（18+1+11+3+0+13） |
| 活跃度（非 fork 非归档） | 活跃 81 / 陈旧化 23 / 归档候选 0 | 活跃=90 天内有推送；mtime 是「最后修改」代理，不等于「最后使用」，不构成删除建议 |

## 集合仓一览

| 仓库 | 内含 SKILL.md | 说明 |
|---|---|---|
| [autoclaw-skills](https://github.com/wanglin1111111/autoclaw-skills) | 18 | 多智能体健康诊断等 |
| [ai-agent-skills-collection](https://github.com/wanglin1111111/ai-agent-skills-collection) | 1 | AI Agent 技能集合 |
| [enterprise-ai-skills-collection](https://github.com/wanglin1111111/enterprise-ai-skills-collection) | 11 | 企业 AI 应用（已脱敏） |
| [personal-development-skills-collection](https://github.com/wanglin1111111/personal-development-skills-collection) | 3 | 个人发展与商业 |
| [artistic-creation-skills-collection](https://github.com/wanglin1111111/artistic-creation-skills-collection) | **0** | ⚠️ 修正：main 分支无 SKILL.md（实为 harness 配置仓），旧索引「1 技能 5 测试」口径失真 |
| [ai-workflow-skills](https://github.com/wanglin1111111/ai-workflow-skills) | 13 | 企业合规等 workflow 技能集 |

## 全量仓库矩阵（102 仓）

| 类别 | 仓库 | 可见性 | 最近推送 | 一句话说明 |
|---|---|---|---|---|
| 单技能 | [academic-research-skills](https://github.com/wanglin1111111/academic-research-skills) | 私有 | 2026-06-10 | 综合技能包 |
| 单技能 | [ad-compliance-cn](https://github.com/wanglin1111111/ad-compliance-cn) | 公开 | 2026-11-20 | 中文营销内容广告法合规审查（营销域第一个技能）— 发布前审查：公众号/小红书/抖… |
| 单技能 | [adk-agent-skill-construction-skill](https://github.com/wanglin1111111/adk-agent-skill-construction-skill) | 公开 | 2026-11-03 | ADK智能体Skill构建技能包 |
| 单技能 | [agent-delegation](https://github.com/wanglin1111111/agent-delegation) | 公开 | 2026-11-20 | 把 AI Agent 当'外包助理'管理的委派方法论 — 战场从爆款产品转向塞进… |
| 项目 | [agent-financial-ecosystem-research](https://github.com/wanglin1111111/agent-financial-ecosystem-research) | 私有 | 2026-08-19 | Agent 金融功能生态调研——龙虾缺口与行业版图（六协议/中间层生态位/Evi… |
| 单技能 | [agent-permission-gate](https://github.com/wanglin1111111/agent-permission-gate) | 公开 | 2026-11-20 | Agent 权限治理与运行时硬拦截技能（OpenShell 方法论）— 规则从提… |
| 单技能 | [agent-skill-methodology](https://github.com/wanglin1111111/agent-skill-methodology) | 私有 | 2026-08-10 | Agent Skill 设计、构建、验证、分发与认知升级的工程方法论体系 |
| 单技能 | [agent-workspace-token-economy](https://github.com/wanglin1111111/agent-workspace-token-economy) | 公开 | 2026-07-30 | Agent Workspace Token Economy — interfac… |
| 单技能 | [ai-agent-evolution-self-evolution](https://github.com/wanglin1111111/ai-agent-evolution-self-evolution) | 公开 | 2026-11-20 | AI Agent架构演进与自我进化 - Harness本质、Self-Evolu… |
| 单技能 | [ai-agent-skills](https://github.com/wanglin1111111/ai-agent-skills) | 公开 | 2026-07-30 | AI Agent技能集合 - 架构演进、情感分析、市场分析 ， Branches… |
| 集合 | [ai-agent-skills-collection](https://github.com/wanglin1111111/ai-agent-skills-collection) | 公开 | 2026-07-30 | AI Agent技能集合统一仓库 - 7个技能整合 |
| 单技能 | [ai-agent-software-construction-skill](https://github.com/wanglin1111111/ai-agent-software-construction-skill) | 公开 | 2026-11-03 | AI Agent时代软件构建技能包 |
| 单技能 | [ai-billing-payment-platform-practice](https://github.com/wanglin1111111/ai-billing-payment-platform-practice) | 公开 | 2026-11-03 | AI 商业化计费支付平台实践技能 — 市场空白识别与验证、商业模式举一反三方法论… |
| 单技能 | [ai-chain-embed](https://github.com/wanglin1111111/ai-chain-embed) | 公开 | 2026-11-20 | AI 全链路嵌入方法论技能 — 工具人人可得差距在嵌得多深：四节点AI/人配对嵌… |
| 单技能 | [ai-coding-skills-playbook](https://github.com/wanglin1111111/ai-coding-skills-playbook) | 公开 | 2026-11-03 | 人工智能编程技能库应用方法完整文字版 — Matt Pocock skills … |
| 单技能 | [ai-coding-trend-industry-frontier](https://github.com/wanglin1111111/ai-coding-trend-industry-frontier) | 公开 | 2026-07-30 | AI 编码趋势与行业前沿动态实践技能 — 多元视角融合提升决策质量的方法论 |
| 单技能 | [ai-content-insight-brand-marketing](https://github.com/wanglin1111111/ai-content-insight-brand-marketing) | 公开 | 2026-07-30 | AI 驱动全域内容洞察与品牌营销实践技能 — AI 时代品牌力评估新模型（已脱敏… |
| 单技能 | [ai-development-trend-social-impact](https://github.com/wanglin1111111/ai-development-trend-social-impact) | 公开 | 2026-07-30 | AI发展趋势与社会影响应对技能（已脱敏）- 九维度AI发展模型 |
| 单技能 | [ai-digital-employee](https://github.com/wanglin1111111/ai-digital-employee) | 公开 | 2026-07-30 | AI数字员工模式 — Dan Koe方法论：把AI从老虎机升级为数字员工 |
| 单技能 | [ai-enterprise-application-human-collaboration](https://github.com/wanglin1111111/ai-enterprise-application-human-collaboration) | 公开 | 2026-07-30 | AI企业应用落地与人机协同实践技能（已脱敏）- 九维度应用模型 |
| 单技能 | [ai-inclusive-education-special-education](https://github.com/wanglin1111111/ai-inclusive-education-special-education) | 公开 | 2026-11-03 | AI赋能融合教育与特殊教育实践技能（已脱敏）- 六维度融合教育模型 |
| 单技能 | [ai-industrial-upgrade-intelligent-manufacturing](https://github.com/wanglin1111111/ai-industrial-upgrade-intelligent-manufacturing) | 公开 | 2026-11-03 | AI驱动产业升级与智能制造实践技能（已脱敏）- 九维度产业升级模型 |
| 单技能 | [ai-knowledge-management-skill](https://github.com/wanglin1111111/ai-knowledge-management-skill) | 公开 | 2026-11-03 | AI知识管理技能包 |
| 单技能 | [ai-marketing-sales-landing-practice](https://github.com/wanglin1111111/ai-marketing-sales-landing-practice) | 公开 | 2026-11-03 | AI驱动营销与销售场景落地实践技能（已脱敏）- 九维度营销销售模型 |
| 单技能 | [ai-methodology-skills](https://github.com/wanglin1111111/ai-methodology-skills) | 私有 | 2026-08-05 | AI时代人生方法论技能库 |
| 单技能 | [ai-reading-cube-skills](https://github.com/wanglin1111111/ai-reading-cube-skills) | 公开 | 2026-11-03 | 2026上海书展·静安区分会场「AI阅读大魔方」Skill面参展作品 — 把一本… |
| 单技能 | [ai-retail-ecommerce-content-creation](https://github.com/wanglin1111111/ai-retail-ecommerce-content-creation) | 公开 | 2026-11-03 | AI驱动零售与跨境电商内容创作实践技能（已脱敏）- 九维度内容创作模型 |
| 单技能 | [ai-seo-cn](https://github.com/wanglin1111111/ai-seo-cn) | 公开 | 2026-11-20 | 中文 AI 搜索优化（AEO/GEO 中文语境）— 诚实性总纪律：渠道引用偏好分… |
| 单技能 | [ai-task-economy](https://github.com/wanglin1111111/ai-task-economy) | 公开 | 2026-11-20 | AI 应用商业化的任务驱动付费与 Token 经济技能 — 先盘任务量(频次×版… |
| 单技能 | [ai-video-prompt-studio](https://github.com/wanglin1111111/ai-video-prompt-studio) | 公开 | 2026-11-20 | Model-agnostic AI video prompt studio: s… |
| 集合 | [ai-workflow-skills](https://github.com/wanglin1111111/ai-workflow-skills) | 私有 | 2026-07-25 | 个人 AI 工作流技能库：6 个 Qoder Agent Skills（文字稿整… |
| 项目 | [ai4ai-bench](https://github.com/wanglin1111111/ai4ai-bench) | 公开 | 2026-11-20 | AI4AI-Bench: Auditing Recursive Self-Imp… |
| 项目 | [apex-math-2026](https://github.com/wanglin1111111/apex-math-2026) | 公开 | 2026-11-03 | Apex Math 悬赏论文（凸 Nivat 附录 C.2）的独立精确验证：10… |
| 集合 | [artistic-creation-skills-collection](https://github.com/wanglin1111111/artistic-creation-skills-collection) | 公开 | 2026-11-03 | 艺术创作与田野调查技能集合统一仓库 - 后创作方法与身体语言创新 |
| 单技能 | [autism-education-lifecycle-support-international-cooperation](https://github.com/wanglin1111111/autism-education-lifecycle-support-international-cooperation) | 公开 | 2026-11-03 | 孤独症儿童全生命周期教育支持与国际合作实践技能（已脱敏）- 九维度教育支持模型 |
| 集合 | [autoclaw-skills](https://github.com/wanglin1111111/autoclaw-skills) | 公开 | 2026-11-03 | AutoClaw 多智能体系统健康诊断与优化技能（system-health-o… |
| 项目 | [BreathGuard](https://github.com/wanglin1111111/BreathGuard) | 公开 | 2026-11-03 | 护院鹅·居家安全守护系统 — WiFi CSI 无感感知独居老人跌倒与呼吸，六区… |
| 项目 | [career-development](https://github.com/wanglin1111111/career-development) | 公开 | 2026-11-03 | 职场精英/中层管理：面临晋升瓶颈或裁员危机，急需高管教练（Executive C… |
| 单技能 | [central-oss-design-philosophy](https://github.com/wanglin1111111/central-oss-design-philosophy) | 公开 | 2026-11-03 | Central OSS 设计哲学与 AI 原生开发实践技能 — 可调试性优先设计… |
| 项目 | [china-us-embodied-ai-research](https://github.com/wanglin1111111/china-us-embodied-ai-research) | 私有 | 2026-07-30 | 中美具身智能路径分化研究：基于垂直整合与工具化两条路线的比较分析。核心命题——'… |
| 项目 | [cj-dashboard](https://github.com/wanglin1111111/cj-dashboard) | 公开 | 2026-11-03 | 仓颉生态创新开发挑战赛推荐命题数据看板：报名团队数与提交作品数实时查询 |
| 单技能 | [claude-api-skill](https://github.com/wanglin1111111/claude-api-skill) | 私有 | 2026-09-01 | claude-api Skill 优化版:精修 description 1071… |
| 单技能 | [code-quality-guardian](https://github.com/wanglin1111111/code-quality-guardian) | 公开 | 2026-11-03 | 🛡️ 代码质量守护者 - 代码智能辅助与质量保障 Skill ， 代码审查、测试… |
| 单技能 | [code-video-pipeline](https://github.com/wanglin1111111/code-video-pipeline) | 公开 | 2026-11-20 | 用代码模型做视频的生产管线技能 — LLM 写 Three.js 网页动画 + … |
| 单技能 | [competition-theme-occam-distillation](https://github.com/wanglin1111111/competition-theme-occam-distillation) | 公开 | 2026-11-03 | 竞赛作品主题奥卡姆蒸馏法 — 从 N 个参赛项目中蒸馏 ≤5 个核心方向的系统方… |
| 单技能 | [content-creation-skill](https://github.com/wanglin1111111/content-creation-skill) | 公开 | 2026-11-03 | 内容创作技能包 |
| 单技能 | [creation-density](https://github.com/wanglin1111111/creation-density) | 公开 | 2026-11-20 | AI 时代创造密度与闭环工作流技能 — 追闭环数不追开题数/六步工作流/真实问题… |
| 单技能 | [creative-skills](https://github.com/wanglin1111111/creative-skills) | 公开 | 2026-11-03 | 创意设计技能集合 - 设计辅助、创意生成 ， Branches as Speci… |
| 单技能 | [cross-border-investment-financing-risk-control](https://github.com/wanglin1111111/cross-border-investment-financing-risk-control) | 公开 | 2026-11-03 | 跨境投融资实践与风险控制技能（已脱敏）- 七维度跨境投融资模型 |
| 单技能 | [cross-border-listing-ma-finance-practice](https://github.com/wanglin1111111/cross-border-listing-ma-finance-practice) | 公开 | 2026-11-03 | 中概股境外上市与跨境并购实践技能（已脱敏）- 七维度跨境金融模型 |
| 单技能 | [depth-video-control](https://github.com/wanglin1111111/depth-video-control) | 公开 | 2026-11-20 | 深度驱动AI视频控制技能 — 实拍视频抽深度图/深度序列当空间骨架约束AI生成：… |
| 项目 | [desktop-healing-pet](https://github.com/wanglin1111111/desktop-healing-pet) | 公开 | 2026-11-03 | 桌面治愈电子宠物 - 沉浸式多模态交互空间 ， Edge TTS语音 ， 8种动… |
| 单技能 | [dl-training-testing](https://github.com/wanglin1111111/dl-training-testing) | 公开 | 2026-11-20 | 深度学习模型训练（SFT/RLHF/GRPO/DPO）与测试场景引擎 — 7阶段… |
| 单技能 | [emotional-mirror-cognitive-scaffold](https://github.com/wanglin1111111/emotional-mirror-cognitive-scaffold) | 公开 | 2026-11-03 | AI作为情感镜像与认知脚手架 - 亲密关系建立与成长辅助技能 |
| 集合 | [enterprise-ai-skills-collection](https://github.com/wanglin1111111/enterprise-ai-skills-collection) | 公开 | 2026-11-03 | 企业 AI 应用技能集合统一仓库 - 10 个技能（已脱敏）：AI 创业方法论、… |
| 单技能 | [enterprise-ai-transformation-skill](https://github.com/wanglin1111111/enterprise-ai-transformation-skill) | 公开 | 2026-11-03 | 企业AI转型技能包 |
| 单技能 | [enterprise-strategic-transformation](https://github.com/wanglin1111111/enterprise-strategic-transformation) | 公开 | 2026-11-03 | 企业战略转型与硬核突破实践技能（已脱敏）- 七维度转型模型 |
| 单技能 | [fde-business-embed](https://github.com/wanglin1111111/fde-business-embed) | 公开 | 2026-11-20 | FDE 前置部署工程师方法论技能 — 企业 AI 瓶颈不在模型而在落地：蹲现场/… |
| 单技能 | [field-research-artistic-creation-practice](https://github.com/wanglin1111111/field-research-artistic-creation-practice) | 公开 | 2026-11-03 | 田野调查与艺术创作实践技能（已脱敏）- 七维度艺术创作模型 |
| 单技能 | [gate-contract](https://github.com/wanglin1111111/gate-contract) | 私有 | 2026-10-12 | 技能闸门契约仓（审查方独立于被审技能仓库）：GATE-CONTRACT.md 阻… |
| 单技能 | [government-document-intelligence](https://github.com/wanglin1111111/government-document-intelligence) | 私有 | 2026-07-30 | 政务公文智能处理专家 - 支持15种法定公文格式校验、智能提取、政策分析、会议纪… |
| 单技能 | [hands-on-loop](https://github.com/wanglin1111111/hands-on-loop) | 公开 | 2026-11-20 | 技术传播最小单位是'亲手跑通'的技能 — 10分钟最小闭环(不跑通不进决策)/C… |
| 单技能 | [install-skills-from-zip](https://github.com/wanglin1111111/install-skills-from-zip) | 私有 | 2026-08-06 |  |
| 项目 | [journey-guide-security-fixes](https://github.com/wanglin1111111/journey-guide-security-fixes) | 私有 | 2026-08-20 | journey-guide 安全与质量修复存档：XSS/竞态/定时器泄漏/错误处… |
| 快照 | [knowledge-base](https://github.com/wanglin1111111/knowledge-base) | 私有 | 2026-07-30 | ????? |
| 快照 | [local-memory-docs](https://github.com/wanglin1111111/local-memory-docs) | 私有 | 2026-10-28 | 本机记忆工作区文档树私有备份（Markdown 笔记 + 技能快照 + 基础设施… |
| 快照 | [local-memory-docs-desensitized](https://github.com/wanglin1111111/local-memory-docs-desensitized) | 私有 | 2026-11-03 | 本机记忆快照的脱敏副本（用户名/快照根/主机名/凭证均已占位符化） |
| 单技能 | [macro-micro-linkage-analysis](https://github.com/wanglin1111111/macro-micro-linkage-analysis) | 公开 | 2026-11-03 | 宏观-中观-微观三层联动分析技能 |
| 单技能 | [mcd-diet-guard](https://github.com/wanglin1111111/mcd-diet-guard) | 公开 | 2026-11-03 | 麦当劳膳食守门员 — 基于麦当劳 MCP 真实营养数据，按8 类人群画像做阈值判… |
| 单技能 | [memhub-kb-ops](https://github.com/wanglin1111111/memhub-kb-ops) | 私有 | 2026-11-20 | MemHub / one-memory knowledge-base ops s… |
| 单技能 | [multi-agent-coupling](https://github.com/wanglin1111111/multi-agent-coupling) | 公开 | 2026-11-20 | 多智能体拆分判定与编排治理技能 — 三问耦合体检/单Agent基线任务集/交接契… |
| 快照 | [my-knowledge-base](https://github.com/wanglin1111111/my-knowledge-base) | 私有 | 2026-08-02 | 知识库快照 2026-07-29：FDE 模式采访提炼 + FDE 共学营 Da… |
| 快照 | [pandaai-factor-run](https://github.com/wanglin1111111/pandaai-factor-run) | 私有 | 2026-11-09 | PandaAI 因子大赛研究留痕（孤儿快照 2026-11-09；按 #26 裁… |
| 单技能 | [paper-collage-animation](https://github.com/wanglin1111111/paper-collage-animation) | 公开 | 2026-11-03 | 纸艺拼贴风格科普短视频创作 Skill — 输入一个科普主题，产出可直接执行的完… |
| 集合 | [personal-development-skills-collection](https://github.com/wanglin1111111/personal-development-skills-collection) | 公开 | 2026-11-03 | 个人发展与商业技能集合统一仓库 - 4个技能整合 |
| 单技能 | [pipeline-onboard](https://github.com/wanglin1111111/pipeline-onboard) | 公开 | 2026-11-20 | Pipeline 型工具（多平台分发/多智能体流水线）接入工作流的阶梯方法论 —… |
| 单技能 | [productivity-skills](https://github.com/wanglin1111111/productivity-skills) | 公开 | 2026-11-03 | 生产力工具技能集合 - 文件生成、自动化 ， Branches as Speci… |
| 单技能 | [rsi-automation-playbook](https://github.com/wanglin1111111/rsi-automation-playbook) | 公开 | 2026-11-20 | RSI 自动化分级与治理技能 — AL0-AL5 任务分级/先造验证器再造自动化… |
| 快照 | [semantica-knowledge-graph](https://github.com/wanglin1111111/semantica-knowledge-graph) | 私有 | 2026-10-01 | 本机知识图谱持久化备份：Semantica 实例数据（45节点/35边）+ OW… |
| 快照 | [session-archive](https://github.com/wanglin1111111/session-archive) | 私有 | 2026-09-12 | 本地会话资源归档（2026-09）— 核验笔记/部署配置/方法论提炼，随时调用 |
| 项目 | [shenji-audit](https://github.com/wanglin1111111/shenji-audit) | 私有 | 2026-09-18 | 审迹 SHENJI · 证据链式 AI 审计员（业财AI创新黑客松2026 AI… |
| 单技能 | [skill-lib-iterate](https://github.com/wanglin1111111/skill-lib-iterate) | 公开 | 2026-11-20 | 开源 Skill 库的「事实核对 + 三层迭代」方法论 — N1-N4 核对(S… |
| 项目 | [Smart-refrigerator-food-management-system](https://github.com/wanglin1111111/Smart-refrigerator-food-management-system) | 公开 | 2026-11-03 | 鲜知 FreshKnow — 智能冰箱食材管家：追踪保质期、按现有食材推荐菜谱、… |
| 单技能 | [step-collapse](https://github.com/wanglin1111111/step-collapse) | 公开 | 2026-11-20 | 步数塌缩方法论技能 — 多步迭代是在还分布建模粒度的债：unify→中间粒度→硬… |
| 单技能 | [step-model-ecosystem-practice](https://github.com/wanglin1111111/step-model-ecosystem-practice) | 公开 | 2026-07-30 | Step 系列大模型生态实践技能 — 提炼自 Step-3.5 Flash 技术… |
| 单技能 | [stepfun-harness](https://github.com/wanglin1111111/stepfun-harness) | 私有 | 2026-08-16 | StepFun Harness - 基于OpenSquilla架构的智能任务分发… |
| 单技能 | [super-agentic-diner](https://github.com/wanglin1111111/super-agentic-diner) | 公开 | 2026-11-03 | 智能咖啡馆 AI 店长 — FastAPI + MySQL + Redis + … |
| 单技能 | [taste-gate](https://github.com/wanglin1111111/taste-gate) | 公开 | 2026-11-20 | AI 影像/内容生产的审美闸门技能 — 人从制作者变裁判：立项先对齐'什么叫好'… |
| 单技能 | [tdai-powershell-encoding-fix](https://github.com/wanglin1111111/tdai-powershell-encoding-fix) | 公开 | 2026-11-03 | PowerShell Invoke-RestMethod 中文编码问题导致 Ag… |
| 单技能 | [upwind-time](https://github.com/wanglin1111111/upwind-time) | 公开 | 2026-11-20 | 方向选择与时间投入的元方法论 — 别追伟大目标，挪到上风口(≥30%时间地板+锁… |
| 单技能 | [verified-anchor-code-notes](https://github.com/wanglin1111111/verified-anchor-code-notes) | 私有 | 2026-09-30 | 可复核锚点的源码精读笔记 Skill - 每条「文件:行号」引用当轮 sed/g… |
| 单技能 | [web-ui-wallpaper-injection-skill](https://github.com/wanglin1111111/web-ui-wallpaper-injection-skill) | 私有 | 2026-08-14 | Web UI 壁纸注入与自调节控制台技能：三层结构+CSS变量透明+localS… |
| 单技能 | [windows-bsod-device-triage](https://github.com/wanglin1111111/windows-bsod-device-triage) | 私有 | 2026-08-21 | Windows 蓝屏/意外关机/设备失效证据优先排查循环 Skill:纯Powe… |
| 单技能 | [work-tri-layer](https://github.com/wanglin1111111/work-tri-layer) | 公开 | 2026-11-20 | AI 重定义'什么算工作'的应对技能 — 工作三层拆解(可替层/指挥层/判断层)… |
| 单技能 | [workplace-evaluation-art](https://github.com/wanglin1111111/workplace-evaluation-art) | 公开 | 2026-11-03 | 职场高情商评价艺术实践技能 — 捧虚不捧实、捧抽象不捧具体的沟通方法论（已脱敏） |
| 单技能 | [xiaohongshu-66-anniversary](https://github.com/wanglin1111111/xiaohongshu-66-anniversary) | 私有 | 2026-10-01 | 小红书市集「66周年庆」大促攻略技能 — 活动时间 / 商家&买手政策 / 报名… |
| 单技能 | [xiaohongshu-booth-copy](https://github.com/wanglin1111111/xiaohongshu-booth-copy) | 私有 | 2026-10-01 | 展台照片→小红书文案技能 — 四层流程（抽取/提炼/成稿/运营）+ 信源纪律红线… |
| 单技能 | [xiaohongshu-copywriting](https://github.com/wanglin1111111/xiaohongshu-copywriting) | 公开 | 2026-11-03 | 小红书高质量文案创作技能 |
| 单技能 | [xiaohongshu-post-diagnosis](https://github.com/wanglin1111111/xiaohongshu-post-diagnosis) | 公开 | 2026-11-03 | 小红书帖子表现诊断框架：三步法+四维度+软文判定 |
| 单技能 | [xiaohongshu-prohibited-words](https://github.com/wanglin1111111/xiaohongshu-prohibited-words) | 公开 | 2026-11-03 | 小红书违禁词替换技能 — 涵盖最/级/独/无/一等 72 个高频违禁词及合规替换… |
| 单技能 | [xiaohongshu-skills](https://github.com/wanglin1111111/xiaohongshu-skills) | 私有 | 2026-10-02 | 小红书相关 Agent 技能迭代仓库 — v1: xiaohongshu-boo… |
| 快照 | [zcode-memory-backup](https://github.com/wanglin1111111/zcode-memory-backup) | 私有 | 2026-09-21 | ZCode 项目记忆备份（2026-08-26 更新：AI原生SDLC拆解/GM… |

## 结构质量基线（2026-11-21）

| 缺口 | 数量 | 说明 |
|---|---|---|
| 缺 validate.py | 3/84 | 分母=84 个含 SKILL.md 的**非归档**非 fork 仓（审计器 v4 归档感知口径，13 个归档技能仓冻结排除）；余 3 = 治理仓 gate-contract + 快照仓×2（政策豁免，见修订 4） |
| 缺 tests/ 双样例 | 3/84 | 同 v4 口径；余 3 = 治理仓 + 快照仓×2（政策豁免） |
| 缺 LICENSE | 6→0 | 6 个技能仓已补 MIT（2026-11-21 本轮补齐） |
| 缺 README | 4→0 | gate-contract / memhub-kb-ops / verified-anchor-code-notes / web-ui-wallpaper-injection-skill 已补（2026-11-21） |

## 修订记录

- **2026-11-21（修订 4）**：Round 3 逐仓定制校验器——16 个非归档集合仓装集合扫描器（enterprise 11 技能、autoclaw 18 技能优先，扫描 skills/*/SKILL.md frontmatter，逐技能 PASS/FAIL）+ 2 个域校验器仓按其真实 schema 补域样例（dl-training-testing 六检查、paper-collage 七段/分镜表/语速约束）+ ai-reading-cube-skills 补齐 + install-skills-from-zip 补 README；11 个归档技能仓 fail-closed 确认冻结（403 拒写，正确行为）。终局：非归档 84 技能仓中可补份额全部补完。

- **2026-11-21（修订 3）**：Batch A 批量补齐 31 仓 validate.py+tests 双样例（漏斗分层：根级 SKILL.md 单技能仓全补，7 仓非根级/集合仓排除），补 2 仓 LICENSE；审计器升 v3（readme 标志同时认 README/README.md）后复测——缺 validate.py 27/97、缺双样例 33/97、缺 README 仅 3。

- **2026-11-21（修订 2）**：审计工具 v1 只认 .md 样例导致缺口高估，v2 口径（.md+.json）实测缺 validate.py 60/97、缺双样例 66/97；最新 26 批次仓确认已五件套齐全。
- **2026-11-21（本轮）**：全舰队只读审计（123 仓 trees/contents/code-search 三通道）；索引从「52 技能」口径重写为实测画像；补 6 LICENSE + 4 README；旧版「240 测试案例 100% 通过率」无分母口径，删除；旧版「本周/本月/本年」未勾选承诺（2026-05-25 建）已过期，删除。
- **2026-10-01**：新增小红书专区（5 单技能仓）。
- **2026-05-25**：创建。

## 相关入口

- 个人主页仓：[wanglin1111111](https://github.com/wanglin1111111/wanglin1111111)
- 审计可复跑：本轮审计数据（fleet.json / structure.json / scan_results.json）留档于本地工作区 `.zcode/tmp-fleet-audit/`，任务完成后按工作区规则清理；舰队级复跑入口为 `gh api repos/wanglin1111111/<repo>/git/trees/HEAD?recursive=1` 逐仓查询。
