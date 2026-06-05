# skill
### 1.emil-design-eng:
description:This skill encodes Emil Kowalski's philosophy on UI polish, component design, animation decisions, and the invisible details that make software feel great.  
install:
```
npx skills add emilkowalski/skill  
```
[notes:emil-design-eng](https://github.com/xunxun1010/skill/blob/main/emil-design-eng.md)
### 2.skills:
description:This repository contains Anthropic's implementation of skills for Claude. For information about the Agent Skills standard, see agentskills.io.  
install:
```
npx skills add anthropics/skills
```
[notes:anthropics/skills]()


### 3.Academic Detective · 学术侦探
description:一个开源的学术背景调查系统。输入导师姓名和学校，系统从公开数据中提取证据链，自动生成调查报告。  
install:
```
# 1. 克隆
git clone https://github.com/yadnuses/Academic-Detective.git
cd Academic-Detective

# 2. 安装依赖
pip install -r archive/flat_export_redundant_20260501/requirements.txt

# 3. 初始化配置
cp scripts/config.template.yaml ./config.yaml
# 然后编辑 config.yaml 填写学者信息

# 4. 初始化案例目录
python scripts/investigate.py init --case-dir ./output/案例名

# 5. 查看当前状态与推荐步骤
python scripts/investigate.py status --case-dir ./output/案例名

```
[notes:Academic Detective](https://github.com/xunxun1010/skill/blob/main/notes/Academic%20Detective.md)


