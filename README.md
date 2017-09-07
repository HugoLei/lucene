# Lucene

#### Lucene是干嘛用的？

Lucene可以用来做全文检索，例如找出微博评论中包含敏感词的评论。

#### MySQL索引使用的是B+树，那Lucene用的是什么？

Lucene底层使用倒排索引技术，倒排索引更适合做全文检索。

#### 在项目中如何使用Lucene？

Lucene原生是用Java编写的。因其广受欢迎，现已有多种语言的移植版本（包括C/C++、C\#、Ruby、Perl、Python、PHP）。

Lucene不是一个完整的全文检索引擎，不能拿来直接用。

Lucene是一个全文检索引擎的架构，是个工具包，是个类库。它提供了完整的查询引擎和索引引擎，以及针对部分语言的文本分析引擎。

