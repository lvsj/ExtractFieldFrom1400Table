  此脚本用来从1400文档的表格中提取字段信息，并生成java字段定义的文本文件（autoGenerate.txt），直接复制所有字段即可。使用前需要注意：
- 需要安装 python-docx 库
- 提取整个表格，例如机车，人员到一个新的word文档中，同时要去掉表头，文件名使用"table.docx"
- 除了int类型会定义成Integer类型，别的类型都暂定义为String类型 
