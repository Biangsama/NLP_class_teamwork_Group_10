课题题目 2：垃圾邮件检测 
=========================
研究内容： 
-----------
        垃圾邮件对于社会是一个危害，很容易造成个人信息泄露，对企业也很容易造成客户数据泄露的风险。各公司基本都开发了垃圾邮件识别系统，能够有效的识别垃圾邮件，删除垃圾邮件，避免因此造成的损失。垃圾邮件是一类相对容易识别的邮件类型，具有一些显著的文本特征：语法或拼写错误：骚扰邮件常常书写不严谨，经常会出现单词拼写错误，语法错误，汉字可能出现错别字的现象。 
                诱导性词汇：骚扰邮件经常会出现很多的诱导性词汇，比如“中奖”等词汇，诱导用户点击相关链接或者访问相关网站。 
                发件人地址不明：发件人邮件地址不明，不属于机构内部后缀，一般陌生后缀的发件人邮箱地址常常属于骚扰邮件的范畴。 
关键技术： 
    垃圾邮件分类是一种具有广泛应用场景的二分类问题，可以利用机器学习进行解决，市场上已经有很成熟的垃圾邮件分类软件。此课程项目，只是针对垃圾邮件分类问题，利用所学的机器学习知识进行分类模型的训练和垃圾邮件的预测。 
评价指标： 
    正确率，精确率，召回率等。 
课题要求： 
    设计一个分类器，对收到的邮件内容进行识别是否为垃圾邮件。
项目任务： 
    项目任务包括两个方面： 
        1. 自然语言大模型及其特点的调研 
        2. 课程项目需至少包括 6 大部分： 
            a) 项目背景 ：
                垃圾邮件识别网站旨在利用机器学习和自然语言处理（NLP）技术来自动识别和过滤垃圾邮件（Spam）。该网站的主要功能是分析用户输入的邮件内容，并判断其是否属于垃圾邮件，从而帮助用户提高邮件管理的效率，减少不必要的干扰。
            b) 关键技术 ：
                使用多种机器学习算法（如SVM、Random Forest、BERT等）进行训练出一个用于识别垃圾邮件的模型，同时使用爬虫提取对应邮箱的所以邮件进行处理方便用户使用，最后搭建一个基于flask或者类似架构的网页供所有人使用
            c) 系统的设计与实现 ：
                1.git 相关应用：代码备份，版本更新
                2.网页界面编写
                3.邮箱内容爬取
                4.垃圾邮件标题检测（中英文）＋评估
                5.垃圾邮件内容检测（中英文）+评估
                6.Web界面进行实时文本检测
