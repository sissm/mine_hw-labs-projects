# 计算机组成原理

本分支用于整理计算机组成原理课程资料与实验工程。

## 目录内容

- `计算机组成原理第1章.pdf` ～ `计算机组成原理第7章.pdf`：课程章节资料。
- `计算机组成原理复习.pdf`、`CO第2章.pdf`：复习与补充资料。
- `计算机组成原理实验教程(2026版).docx`：实验教程。
- `计算机组成原理实验报告模板(2026版).doc`、`计算机组成原理实验报告模板_重新排版.docx`：实验报告模板。
- `Quartus使用指南.pptx`：Quartus 使用参考。
- `lab1/`：实验一 Quartus 工程及仿真波形文件。

## 实验一

- 工程文件：`lab1/lab1.qpf`、`lab1/register.qsf`
- 通用寄存器组：`lab1/GPRs.bdf`、`lab1/GPRs.vwf`
- LPM 触发器：`lab1/lpm_dff.bdf`、`lab1/lpm_dff.vwf`
- LPM 组件文件：`lab1/lpm_dff0.*`

工程由 Quartus II 9.1 SP2 创建，目标器件为 Cyclone III `EP3C16Q240C8`，当前顶层实体为 `lpm_dff`。

`db/`、`incremental_db/`、编译报告和器件配置文件等生成物已通过 `.gitignore` 排除。
