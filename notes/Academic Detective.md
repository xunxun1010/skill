source:https://github.com/yadnuses/Academic-Detective  
官方网站：https://www.academic-detective.top/  
新手上手指南：https://hcne37wbg3ch.feishu.cn/wiki/Rrh5wjw12ipRRQkuG56cw9Drnic?from=from_copylink  
### 1.项目总览
这是一个开源学术背景核查引擎，核心目标是帮学生选导师之前做一次基于公开数据的背景调查。

### 2.核心理念
选导师，先查一查 —— 把学术声誉检测工具民主化

### 3.三大调查轨道（Track）
Track	适用对象
domestic	仅在国内机构任职的学者
international	海外学者或在海外机构任职
cross_border	有海归/跨境经历的学者
### 4.七步调查框架（Step 0–7）
案件注册 · 生成唯一 ID
基础画像 · 学者身份时间线
产出核实 · 声称 vs 实际论文数
质量评估 · Nature 同行审核机制的六维评分（创新性/方法/论证/文献/写作/贡献）
关系网络 · D3.js 可视化合作图谱 + 基金关联
异常检测 · 46 个已知案例的模式比对 + 数据取证（尾数分析、图像元数据、双语重复发表、审稿周期异常等）
多源验证 · 研学网 7.5 万+ 学生评价匹配 + 小红书/知乎口碑 + CRAAP 信息源评估
报告生成 · Markdown → 精美 PDF + 自动图表 + 零宽水印保护
### 5.工具链规模
scripts/ 下有 40+ 个子命令，编排引擎是 investigate.py
深度证据层覆盖：数据取证、发表链追踪、伦理审计、同行评议情报
配有 config.yaml 统一配置入口
### 6.数据基础
46 个已知不端案例的脱敏特征数据库
学科基准线（Z-score/对数正态/t 分布异常评分）
研学网 7.5 万+ 结构化学生评价
