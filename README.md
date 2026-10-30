# DM-Exp-Tourism-GroupX-2026Fall
《数据挖掘》探索性实验｜旅游领域文本挖掘与知识图谱构建｜含数据预处理、实体识别、路线解析、共指消解、条件抽取、图谱融合及旅游规划Agent全流程实现｜支持可复现运行与失败反思记录

## 实验五：条件性游览建议抽取

[代码、Notebook与结果](experiments/exp05/) · [使用说明](experiments/exp05/使用说明.md)

使用实验一提供的48篇结构化文章，提取条件及对应行动，生成95条主体建议和10条其他地点建议，并保留来源原句和字符位置。

```bash
cd experiments/exp05
python -m pip install -r requirements.txt
python run_experiment.py
python verify.py
```
