# 词向量
一种映射处理，将种将非结构化数据，如单词、句子或者整个文档，映射到嵌入空间（事实上就是一个向量空间），我认为是一种度量，是否能在这种映射上采取度量学习的方法。

以更好地将相似或相关的对象在嵌入空间中聚合，满足“相似度高则距离更近”

## RAG为什么选择了词向量
* 词向量比文字更适合检索，其本身包含着相似度的信息，转换为向量空间后，通过距离就能表征语义层面的相似度信息。

* 词向量比其它媒介的综合信息能力更强，当传统数据库存储文字、声音、图像、视频等多种媒介时，很难去将上述多种媒介构建起关联与跨模态的查询方法；但是词向量却可以通过多种向量模型将多种数据映射成统一的向量形式。

## 构建词向量
* 使用各个公司的 Embedding API；
* 在本地使用嵌入模型将数据构建为词向量。
# 向量数据库
事实上，这就是一个向量空间（或者说是映射后的度量空间），所有数据被表示为向量形式。
