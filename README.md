# tanda-content

每日 GEO 文章的写入目录。内容会被主站构建流程取走并发布到 tandastructures.com。

## 目录

- `topic_queue.json` —— 选题队列。问句来自真实搜索结果检索，不是编的。
- `insights/` —— 文章存放处，一篇一个 JSON，文件名 `YYYY-MM-DD-<英文 slug>.json`
- `insights/_template.json` —— 输出格式

## 写作规则

**第一段就是答案。** `answer` 字段两到三句，直接回答标题里的问题，要能被单独摘出来
引用仍然成立。不要铺垫，不要「随着行业发展」这类开场 —— AI 搜索引用的就是这一段。

**不写任何没有第三方实测依据的参数。** 工作压力、抗拉与抗撕裂强度、阻燃等级、
使用年限、跨度、风压等级一律不给数字。需要提到时明确说明尚未取得第三方检测数据、
有文件才发数字。这是本站已对外声明的立场，写了数字就是自打脸。

**诚实对比。** 涉及竞品或替代方案时，必须写清楚对方在什么情况下更合适。
只夸自己的对比内容不会被 AI 引用，也不会被买家信任。

**不编造** 客户、案例、项目、交付记录。

## 产品背景

drop-stitch 充气膜结构（气墙式）：两层基布之间由数万根等长内拉线连接，充气后
拉线绷紧使两个面保持平行，墙体成为有厚度的刚性板，而不是鼓起来的气囊。

与之相对的两种构造：

- **气柱式 air-beam** —— 少数几根大直径气柱作骨架，之间蒙一层布。承载集中在气柱上，
  破一根就是结构性事故。市面上多数充气军用帐篷是这一种。
- **气承式 air-supported / Traglufthalle** —— 靠持续送风的内压撑起整个膜面，需要气密门，
  断电会塌。多数充气体育馆是这一种。

产品覆盖：住宿、应急安置、医疗、指挥、防务、防洪围控、水上平台、材料代工。

## 各语种行业术语

写作涉及外语术语时用这些词。它们是逐语种查真实供应商页面得来的，
机翻给出的同义词语法正确但没人搜。

| 概念 | 英 | 德 | 法 | 俄/乌 |
|---|---|---|---|---|
| 充气帐篷 | inflatable tent | aufblasbares Zelt | tente gonflable | пневмокаркасная палатка |
| 快速部署掩蔽所 | rapid deployment shelter | Schnelleinsatzzelt | abri à déploiement rapide | быстроразворачиваемое укрытие |
| 野战医院 | field hospital | Feldlazarett | hôpital de campagne | полевой госпиталь |
| 前方急救站 | forward medical post | Verbandplatz | poste médical avancé (PMA) | медичний пункт |
| 气承式结构 | air dome | Traglufthalle | structure à air captif | воздухоопорное сооружение |
| 挡水屏障 | inflatable flood barrier | mobiler Hochwasserschutz | barrière anti-inondation gonflable | протипаводковий бар'єр |

注意：`drop-stitch` 与 `DWF` 各语种普遍直接借用英文，不要硬译。
西语 `inflable`（拉美）与 `hinchable`（西班牙）并存，两个市场都要覆盖。
