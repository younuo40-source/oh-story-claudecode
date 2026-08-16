# CODEX 从“研究项目”到“完整路线老师”
## 原子执行链 + 双轨发现 + 赚钱路径扩容 修复包 v1

> 目的：把当前“海外工作与定居路径”项目从 **Route Research Database** 修正为 **China → Legal Income → Stable Work → Long-term Option 的现实执行系统**。
>
> 本包不推翻现有研究。现有 `ROUTE_UNIVERSE / NODE_TRUTHS / JOB_MARKET / CREATOR_REGISTRY / SOURCE_REGISTRY / EVIDENCE_LEDGER` 继续作为后台真相库。
>
> 修复的是：**后台真相库没有被强制消费成从用户今天开始的一条完整路线。**

---

# 0. 先定产品：用户到底要什么

项目最终产品不是：

```text
德国护理研究深度 15/16
韩国 E-9 status = WAITING
澳洲 Anchor pair = PASS
151 sources
55 claims
```

最终产品是：

```text
“我是一个今天人在中国的用户。
如果我要沿路线 X 合法赚钱，我从今天开始第一步干什么？
去哪儿？
开什么网站？
需要什么？
多少钱？
多久？
什么算做完？
卡住怎么办？
下一步是什么？
一直带到真正开始合法获得收入。”
```

更高一级再继续：

```text
开始收入
→ 稳定工作
→ 续签/换签
→ 长期居留/永居（如该路线存在）
```

---

# 1. 为什么老王式案例能跑通，而当前项目没有

## 1.1 老王案例不是“研究完以后再执行”

真实结构是：

```text
广泛调研
→ 确定几个低门槛链
→ 立即跑第一条
→ 每走一步暴露新的材料和现实问题
→ Agent 现场解决
→ 用户返回截图/邮件/结果
→ Agent 更新资源库和真相源
→ 继续下一步
```

因此：

```text
现实执行本身 = 下一轮研究问题生成器
```

而不是：

```text
研究完成 = 执行的前提
```

---

## 1.2 当前项目把一个错误前提写进了架构

当前实际上变成：

```text
Route Universe
→ Profile
→ Challenger
→ Practitioner parity
→ Global optimality O6
→ P10 Execution
```

由于：

```text
O6 永远还有 unknown
```

于是：

```text
P10 永远锁着
```

Agent 就只能不断：

```text
Research
→ Research
→ Research
```

这会产生一个很荒唐的结果：

> 已经知道德国护理签证要什么材料，
> 已经知道工资、住房、学历认可、学校和实践机构，
> 但仍然没有一个“用户今天开始，从第一步到最后一步怎么走”的 runbook。

这是产品架构错误，不是“资料还不够”。

---

# 2. 任务本身确实比老王案例更开放，但这不能成为不落地的理由

海外工作/长期居留比开户/资金平台多一层：

```text
老王任务：
目标已确定
→ 找多条技术链实现同一个目标

当前任务：
先决定哪一种赚钱机制
→ 再决定哪一个国家/法律入口
→ 再执行
```

因此它有真正的：

```text
META-DECISION LAYER
```

包括：

- 去哪个国家；
- 做什么职业；
- 学哪门语言；
- 是先培训、先工作、WHV、跨境销售还是毕业后技术岗；
- 暂时赚钱还是长期身份优先。

但是错误做法是：

```text
必须先证明 Global Best
才能跑任何一条链
```

正确做法：

```text
探索和执行并行。
```

---

# 3. 新架构：EXPLORE 与 RUN 两条轨道并行

## TRACK A — EXPLORE

负责：

```text
还有没有更好的赚钱机制？
还有没有被漏掉的国家/职业/语言杠杆？
当前 incumbent 会不会被 challenger 击败？
```

它可以持续存在。

---

## TRACK B — RUN

至少始终有：

```text
1 条当前最值得现实化的 runnable lane
```

RUN 不需要等待：

```text
Global Optimality
```

只需要：

```text
- 合法
- 当前没有被硬淘汰
- 现实价值足够高
- 有明确下一步
- 下一步可逆/低风险，或者已获得用户授权
```

---

## 核心规则

```text
O6 NOT FINAL
≠
NO EXECUTABLE ROUTE
```

允许：

```text
INCUMBENT_RUNBOOK
CHALLENGER_RUNBOOK
PROBE_RUNBOOK
```

同时存在。

---

# 4. GATE H26 — COMMON CHINA ROOT

所有海外路线必须先共享一个“中国侧公共根节点”。

不是每条国家路线重新从半路开始。

固定要求建立在现有 `NODE_TRUTHS.md` 中：

```text
COMMON-CHINA-ROOT
```

至少回答：

## 身份证件

```text
用户现在持有什么合法出境身份证件？
是否已经有中华人民共和国普通护照？
有效期到什么时候？
剩余有效期是否满足目标路线？
是否需要新办 / 换发 / 无动作？
```

如果用户已经持有效普通护照：

```text
ACTION != “去办护照”
```

而是：

```text
确认到期年月
→ 判断目标时间点是否需换发
```

不得为了流程完整让用户重复办理已有资源。

---

## 中国侧基础材料

只建立：

```text
material inventory
```

不要过早办理短时效证明。

至少覆盖：

```text
身份证明
普通护照
高中毕业证
高中成绩/科目
高考证明（若目标节点要求）
大学在读证明
大学成绩单
语言证书
职业证书
无犯罪（仅目标节点要求时）
体检/疫苗（仅目标节点要求时）
翻译
公证
附加证明书/Apostille（仅使用国明确要求时）
```

每项必须：

```yaml
current_state:
required_by_which_route:
where_to_get:
cost:
lead_time:
validity:
when_to_prepare:
do_not_prepare_before:
completion_evidence:
```

---

## 中国侧基础数字能力

至少确认：

```text
稳定国际邮箱
能接收短信/邮件
国际视频会议能力
可使用的支付渠道
文件扫描/命名/PDF能力
官方门户账号
```

这不是为了凑材料，而是为了避免执行到一半才发现基础设施缺失。

---

# 5. GATE H27 — ATOMIC EXECUTION NODE

任何路线只要进入 RUNBOOK，就必须从中国当前状态拆到原子级。

每个节点固定 schema：

```yaml
node_id:
route_id:
actor: USER | AGENT | EXTERNAL

goal:
why_required:

prerequisites:
current_user_state:

official_entry:
  website:
  exact_page:
  current_ui_checked_on:

what_you_will_see:
  - 页面名称
  - 关键栏目/按钮/搜索框

exact_steps:
  1:
  2:
  3:

inputs_needed:
documents_needed:

cost:
  mandatory:
  optional:
  service_fee:
  uncertainty:

time:
  preparation:
  official_processing:
  waiting:

do_not_do:
common_mistakes:
practitioner_warnings:

completion_evidence:

if_success:
next_node:

if_failure:
diagnostic:
fallback:

external_side_effect:
authorization_required:
```

---

# 6. “网站怎么弄”必须真的看当前网站

禁止只写：

```text
“去德国外交部申请签证。”
```

必须至少达到：

```text
官方入口是什么
→ 目前网页叫什么
→ 用户该选择哪一类
→ 点进去之后填什么类型
→ 上传什么
→ 什么时候产生预约/预审
→ 完成凭证是什么
```

如果当前页面 UI 能公开访问：

```text
Agent 必须实际打开当前页面并按当前 UI 写 walkthrough。
```

如果必须登录：

```text
先把登录前部分做完
→ 到用户登录节点再让用户操作
→ 用户截图回来
→ 继续
```

---

# 7. GATE H28 — FULL ROUTE GRAPH

任何 Serious Route 不允许只有中段知识。

必须存在：

```text
TODAY
↓
COMMON CHINA ROOT
↓
路线资格准备
↓
技能/语言
↓
获得真实入口（名额/合同/抽签/雇主）
↓
材料
↓
申请
↓
审核
↓
出境
↓
落地
↓
开始合法工作/培训收入
↓
工资/税/住房/保险
↓
续签/职业升级
↓
长期身份桥
↓
退出/失败回国
```

不是每个节点今天都可执行。

允许：

```text
READY
WAITING
FUTURE
BLOCKED_EXTERNAL
USER_AUTH_REQUIRED
```

但：

```text
图必须完整。
```

这样用户第一次就能知道：

```text
“这条路全长是什么。”
```

---

# 8. 每条候选路线必须生成两个用户产品

不新增文件；写入对应 `NODE_TRUTHS` / `CURRENT` / `ACTION_QUEUE`。

## 产品 A：这条路线你必须知道的 10–20 件事

必须包含：

```text
入口
证件
语言
考试
合同
资金
时间
工作内容
工资/扣款
住房
签证
失败点
换路线
长期身份
```

---

## 产品 B：从今天起的 First 10 Actions

不是：

```text
“学德语”
```

而是：

```text
1. 确认你的普通护照到期年月
2. ...
3. ...
```

每一步有：

```text
入口 + 材料 + 成本 + 完成凭证
```

---

# 9. GATE H29 — FIRST-MILE COVERAGE

任何路线在 Agent 花高成本继续深研前，必须先回答：

```text
用户从今天到“第一次真实对外动作”之前的每一步是什么？
```

第一次真实对外动作例如：

```text
提交语言考试
投递培训岗位
参加官方抽签
报名 EPS
正式注册签证门户
```

如果 First Mile 都没闭合：

```text
FORBID_EXPENSIVE_DEEP_RESEARCH
```

这直接防止：

```text
研究到德国永居
却没告诉用户怎么进入第一个网站。
```

---

# 10. GATE H30 — EXECUTION SHADOW RUN

对尚未授权现实提交的路线，Agent 也不能停。

允许执行：

```text
SHADOW RUN
```

含义：

```text
Agent 自己打开所有公开页面
→ 从入口一路模拟
→ 找到登录/提交/付款边界
→ 记录当前 UI、材料字段、费用、下一页
→ 到有真实副作用的位置停止
```

因此：

```text
“用户没授权申请”
```

不能成为：

```text
“所以我不知道网站实际怎么走”
```

的借口。

---

# 11. GATE H31 — ROUTE PROGRESS 必须按用户距离衡量

禁止主要用：

```text
source count
cycle count
research depth
claim count
```

表达项目进展。

主要进度改成：

```text
TOTAL_ROUTE_NODES
NODES_FULLY_SPECIFIED
NODES_USER_READY
NODES_REALITY_VERIFIED
DISTANCE_TO_FIRST_LEGAL_INCOME
```

例如：

```yaml
DE_CARE:
  total_nodes: 24
  fully_specified: 17
  user_ready_now: 4
  reality_verified: 0
  current_position: node_1
  first_unresolved_blocker: node_7
```

---

# 12. 赚钱路径宇宙必须扩容：签证路线 ≠ 赚钱路线

当前最大 ontology 漏洞：

```text
ROUTE_UNIVERSE
```

几乎把：

```text
legal residence mechanism
```

当成：

```text
economic opportunity universe
```

但用户问的是：

> “我有哪些办法通过海外市场赚钱、工作、最后可能出国？”

所以必须额外维护：

```text
EARNING_STRATEGY
```

仍写入现有 `ROUTE_UNIVERSE.md`，不新建文件。

---

# 13. EARNING_STRATEGY 至少覆盖

## E1 直接短缺劳动出境

```text
Ausbildung
E-9
SSW
employer-sponsored labour
```

## E2 临时劳动 / 现金探针

```text
AU 462
NZ WHV
其他合法 youth mobility
```

## E3 学历完成后专业就业

```text
AI/IT/工程
Blue Card
skilled worker
```

## E4 语言杠杆 + 中国企业海外市场

这就是此前漏掉的：

```text
学西班牙语
+
中国制造/科技/电商/设备公司
+
拉美/西班牙市场
+
海外销售 / Sales Support / Business Development /
Market Development / Localization / Project Coordination
```

这个路线不一定一开始就出国。

典型链：

```text
中国境内学西语
→ 获得可工作的西语 + 英语
→ 进入有拉美业务的中国企业
→ 做外贸/海外销售/市场/项目协调
→ 积累行业产品知识 + B2B 销售经验
→ 出差/驻外/本地团队
→ 可能形成雇主海外派驻、当地合同或跨国跳槽
```

它是一条：

```text
CAREER / EARNING ROUTE
```

不是天然的：

```text
IMMIGRATION ROUTE
```

所以后半段必须再绑定具体国家的合法工作/居留机制。

## E5 跨境电商 / 本地化运营

例如：

```text
西语内容
拉美平台运营
Marketplace
客户运营
广告
本地化
```

必须单独验证：

```text
职位数量
薪资
新人门槛
是否需要本地人
是否需要行业经验
是否真的可形成海外派驻
```

## E6 中国公司海外工程/项目派驻

例如：

```text
通信
电力
新能源
制造
基建
供应链
```

语言可成为稀缺能力，但必须审计：

```text
工时
派驻制度
合同主体
安全
工资
轮休
身份性质
```

## E7 远程跨境服务

只有真实市场验证后进入：

```text
remote sales support
translation/localization
cross-border operations
```

不得把“会西语”直接推成“能自由职业赚钱”。

---

# 14. 西班牙语＋市场路径必须进入 Challenger

新增：

```text
route_id: LANG-ES-LATAM-MARKET
family: LANGUAGE_LEVERAGE_GLOBAL_BUSINESS
```

当前只标：

```text
CHEAP_SCREEN_REQUIRED
```

不能直接称推荐路线。

必须回答：

```text
1. 当前中国人 + 西班牙语真正可申请的岗位有哪些？
2. 应届/零经验岗位有多少？
3. 西语到底要 B1/B2/C1 哪个区间？
4. 英语是否也是硬门？
5. 需要什么行业知识？
6. 销售/BD 是否要求经验？
7. 工作地点是在中国还是拉美？
8. 哪些中国公司有稳定拉美业务？
9. 出差/派驻/本地合同的真实比例如何？
10. 工资、佣金、工时和 KPI 什么样？
11. 西语相对于德语/韩语的机会成本是什么？
12. 该路线怎样接到合法长期海外工作？
```

---

# 15. 西语路线不要只搜“Spanish jobs”

先按真实角色族搜索：

```text
International Sales
Overseas Sales
LATAM Sales
Sales Support
Business Development
Market Development
Country Operations
Localization
Project Coordinator
Tender / Bid Support
Supply Chain Coordination
Customer Success
```

再结合：

```text
Chinese / Mandarin
Spanish
Latin America
LATAM
Mexico
Chile
Peru
Colombia
Argentina
Panama
Spain
```

---

# 16. 为什么这个方向值得 Cheap Screen

不是因为“西班牙语很牛”。

而是因为需要检验一种结构：

```text
用户的原生中文
+
可训练西语
+
中国企业的产品/供应链优势
+
拉美市场扩张
```

是否能够产生：

```text
比直接去海外从零竞争更低的 Point A 门槛。
```

如果可以，它可能成为：

```text
先在国内产生收入/经验
→ 再国际化
```

的 sibling strategy。

如果实际岗位大量要求：

```text
2–5 年 B2B 经验
native Spanish
当地合法工作权
```

则必须相应降级。

---

# 17. 新的研究预算原则

任何高成本 research packet 先回答：

```text
THIS WILL CLOSE WHICH RUNBOOK GAP?
```

如果答案只是：

```text
“进一步提高置信度”
```

不够。

必须是：

```text
会补全某个具体 node：
- 入口
- 材料
- 费用
- UI
- 时间
- 成功/失败分支
```

否则：

```text
NO_RESEARCH_BUDGET
```

---

# 18. TIME-WASTE GATE

当前项目已经花了大量时间，所以增加：

```text
MAX_CONSECUTIVE_PACKETS_WITHOUT_RUNBOOK_NODE = 1
```

两轮研究如果：

```text
没有新增/关闭任何 Atomic Execution Node
```

则：

```text
RESEARCH_MODE = FROZEN
RUNBOOK_REPAIR_MODE = TRUE
```

直到把已有知识转成执行链。

---

# 19. 对德国当前研究的修复方式

禁止重新研究德国基础政策。

现有材料已经足够开始构造：

```text
DE-CARE INCUMBENT RUNBOOK
```

优先补缺：

```text
TODAY
↓
COMMON CHINA ROOT
↓
护照有效期判断
↓
教育材料 inventory
↓
德语学习/考试节点
↓
当前真实 Ausbildung 岗位搜索入口
↓
雇主/学校双申请
↓
条件性预录取
↓
学历等值
↓
双合同
↓
§81a（如使用）
↓
Consular Services Portal
↓
预审
↓
面签/生物信息
↓
签证
↓
出境
↓
落地登记/住房/保险
↓
培训开始
↓
工资
↓
国家考试
↓
合格就业
↓
永居桥
```

已有 Node Truth 要被消费，不要从头搜索。

---

# 20. 用户界面：每次只给两个视图

## VIEW 1 — GLOBAL MAP

用极简方式告诉用户：

```text
当前有哪些赚钱路线族
哪几条最值得继续
各自最大问题是什么
```

## VIEW 2 — CURRENT STEP

真正执行时只显示：

```text
你现在在 Step X
你今天只做什么
去哪儿
多少钱
要什么
做完给我什么
```

不要让用户自己阅读后台账本。

---

# 21. FINAL GATE — 老王式协作标准

只有当 Agent 可以做到以下对话，才允许称“达到原案例水准”：

```text
Agent：
你现在走路线 X。
你已经有 A，不需要重复办。
你还缺 B。

今天只做第 1 步：
打开这里。
选择这里。
准备这几个东西。
预计花费 X。
这里不要点。
做到这个页面/拿到这个凭证就停。

做完把结果/截图给我。

User：
做完了，但出现 Y。

Agent：
这是 Node X 的已知/新 friction。
根据官方源 + Practitioner Truth，
现在改走 Z。
……
```

然后：

```text
真实结果
→ USER_EVIDENCE
→ NODE_TRUTH 更新
→ 后面的步骤更准确
```

才算真正复刻成功。

---

# 22. Codex 立即执行顺序

```text
1. 不再新开宏观 research
2. 读取老王原始人机协作案例
3. 读取现有 NODE_TRUTHS / ROUTE_MATRIX / USER_PROFILE
4. 建 COMMON-CHINA-ROOT
5. 从现有研究构造 DE-CARE 完整 route graph
6. 对每个 node 补 atomic schema
7. 对公开官网做 SHADOW RUN
8. 生成“必须知道的事”
9. 生成 First 10 Actions
10. CURRENT 改成 Global Map + Current Step
11. EXPLORE 与 RUN 解耦
12. Route Universe 增加 EARNING_STRATEGY
13. 对 LANG-ES-LATAM-MARKET 做 Cheap Screen
14. 再决定它是否进入 Serious Challenger
15. 此后每个 research packet 必须绑定一个 runbook gap
```

---

# 23. 禁止行为

```text
禁止 O6 未定 = P10 全锁
禁止研究永居却没有 First Mile
禁止只写“去官网办理”
禁止只有材料清单没有网站入口
禁止只有网站入口没有完成凭证
禁止把签证路线宇宙当赚钱路径宇宙
禁止遗漏语言+海外市场这种职业策略
禁止继续靠来源数/Cycle制造进展
禁止已有资料足够时再次泛搜
禁止因为用户今天还不能提交就不做 SHADOW RUN
禁止要求用户自己把 20 个后台文档拼成攻略
```

---

# 24. 一句话机械原则

```text
每一份研究，必须最终落到一个具体执行节点；
每一条候选路线，必须从“用户今天”画到“第一次合法收入”；
全局最优可以晚一点确定，
但完整可运行链不能永远等它。
```
