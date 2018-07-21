# PoetryData

## 简介

唐诗宋词数据集

- 简体中文版: `QuanTangShi_tb_chinese_poems.sql`
- 繁体中文版: `QuanTangShi_tb_poems.sql`


## 使用

直接导入到 MySql 数据库中即可, 会自动创建相关表及其结构.


## 数据来源

感谢网友 `jackeyGao` 整理的 [全唐诗数据库](https://github.com/chinese-poetry/chinese-poetry)

本项目中数据由上述项目中的 `json` 数据转换而来，且简体中文版数据去除了繁体转换过程中的错别字符(否则无法插入到数据库).