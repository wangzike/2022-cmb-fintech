# 2022招商银行数据赛道
比赛规则：
        1.竞赛时间：4月29日9:00-5月12日17:00
        2.竞赛流程：4月29日9:00-5月9日24:00，赛题开放A榜数据（test_A榜），预测结果数据每天限提交3次；5月10日00:00-5月12日17:00，赛题开放B榜数据（test_B榜），预测结果数据每天      限提交3次。重复提交或提交格式错误均扣除有效提交次数，请谨慎提交答案，结果提交后请务必点击“运行”按钮，方可查看当前个人排名。
        3.排行榜依据“最终得分”计算排名，“最终得分”计算公式为：A榜最高分 * 0.3 + B榜最高分 * 0.7。“最终得分”越大，成绩排名越前。
比赛背景：
        针对公司业务需求，需要设计一个分类预测模型，要求该模型能够预测客户在三个月后取出存款的概率
完成工作：
        使用python对提取的真实数据（包括训练集和测试集）进行清洗过滤和特征的提取
        使用训练集对集成分类预测模型LightGBM进行参数训练
        使用单目标优化算法对模型进行优化
