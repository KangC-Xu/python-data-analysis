# Python 数据分析学习实践

围绕 Titanic 数据集整理的数据分析课程练习与个人学习记录，使用 Jupyter Notebook 展示分析过程。

## 学习内容

| 章节 | 内容 |
| --- | --- |
| [第一章](数据分析/第一章/) | 数据载入与初步观察、Pandas 基础、探索性数据分析 |
| [第二章](数据分析/第二章/) | 数据清洗与特征处理、数据重构、数据可视化 |
| [第三章](数据分析/第三章/) | 模型建立与评估 |

## 技术栈

- 数据处理：Pandas、NumPy
- 数据可视化：Matplotlib、Seaborn
- 建模与评估：scikit-learn
- 交互式学习：Jupyter Notebook

## 浏览与运行

可以直接在 GitHub 上打开各章节的 `.ipynb` 文件，查看课程内容、代码和已保存的输出。

本地运行时，先克隆仓库，再创建独立的 Python 环境：

```powershell
git clone https://github.com/KangC-Xu/python-data-analysis.git
cd python-data-analysis
conda create -n python-data-analysis python=3.10
conda activate python-data-analysis
python -m pip install jupyterlab pandas numpy matplotlib seaborn scikit-learn
jupyter lab
```

打开相应章节的 Notebook，按单元格顺序阅读和运行。仓库中的 CSV 数据位于 `数据分析/第一章/`；运行时需要根据 Notebook 的工作目录核对数据读取路径。

## 仓库说明

- 本仓库用于学习和实践，保留课程练习与个人记录，不作为生产系统或完整算法产品。
- 各 Notebook 的完成程度不同，章节文件的存在不代表全部练习均已完成。
- Notebook 保留了早期学习记录，尚未统一锁定依赖版本；本地复现可能需要调整路径和旧版 API 写法。
