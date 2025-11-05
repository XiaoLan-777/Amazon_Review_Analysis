# Amazon_Review_Analysis

##  项目简介
本项目基于亚马逊公开评论数据集，通过 Python 进行数据清洗、统计分析和可视化探索，揭示用户评分分布、评论行为模式与时间趋势。

##  技术栈
- Python (pandas, numpy, matplotlib, seaborn，sklearn，WordCloud)
- Jupyter Notebook
- 数据规模：100k+ 条评论

##  分析流程
1. 数据加载与结构检查  
2. 数据清洗与预处理  
3. 统计分析（评分、用户、产品）  
4. 文本清洗与词频统计  
5. 有用性指标分析  
6. 可视化展示（评分分布、用户活跃度、时间趋势等）
7. 文本情感分析

##  项目成果
- 构建完整的数据分析流程；
- 生成 9 个可视化结果；
- 提炼出用户行为洞察，可用于电商数据分析类岗位展示。

##  文件说明
| 文件 | 说明 |
|------|------|
| `analysis.ipynb` | 数据分析主文件 |
| `Reviews.csv` | 数据样例 |

---

## 🧑‍💻 运行方式
```bash
pip install -r requirements.txt
jupyter notebook analysis.ipynb
