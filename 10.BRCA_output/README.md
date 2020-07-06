## TCGA_BRCA肿瘤分析结果

每个文件夹均为一个分类指标：

- expression为高低表达，mutation为是否突变，TumorAndNormal为正常和肿瘤
- 每个文件夹中
  - \*.significant.inthegeneset.xlsx为geneset与单个基因在分组条件下是否显著的结果，对应的火山图\*wilcox.volcan.pdf为可视化
  - 带有geneset的文件为每个geneset在分组条件下的表达情况
  - \*.fisher.related.mutation.xlsx为分组条件下low expression/mutation与哪些突变相关(fisher test)，对应的\*.fisher.significant.plot.pdf散点图展示了odd ratio优势比大于1的部分；存在该分组条件下无相关突变的情况，存在一个空的tsv文件