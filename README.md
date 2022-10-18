# 中国工业机器人产业研究项目
数据分析助理研究员

- 该项目为北京大学企业大数据研究中心合作项目，旨在运用企业大数据研究工业机器人企业特征和产业模式，本次助研主要任务为利用经营范围文本从所有企业中识别出工业机器人企业。

- 使用MySQL操作远程机数据库，筛选出1000万家制造业企业和5000家工业机器人制造企业，用作分类数据。

- 在进行NLP特征工程的过程中，设计了“企业经营范围标准化”算法，该算法能将企业工商注册信息中的大段文字的经营范围转化为若干条相同结构的偏正短语，每一条包含该企业的一项产品或服务，提升了模型分类效果。

- 使用Word2Vec模型对分词后的经营范围进行编码，并使用XGBoost模型进行分类，最终模型的AUC分数达0.9以上。
