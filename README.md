### Still developing, will update regularly!  
My project for CIP(Thanks Cathay LAB department for giving me the opportunity! I'm very grateful.)

## Papers I've read just for this project:  
# LIME  
https://arxiv.org/pdf/1602.04938.pdf  
My comment: A very innovative framework for interpreting a model via linear approximate

# SHAP

https://arxiv.org/abs/1705.07874  
My comment : Extraordinary theory to prove that Shapley Value(Game Theory) is the best method of attributing feature contributions. 

# Data Shapley
https://arxiv.org/pdf/1904.02868.pdf

Very recent(2019/5) paperwork  
My comment:  
Another innovative way to implement Shapley Value, SHAP uses Features as players(in game theory),while Data Shapley uses data instances as players.  
Data Shapley我認為真正進入到狹義的Global Interpretation，即可以得知＂預測模型＂(v.s.解釋模型)預測出來的結果大概是長什麼樣子  
Local interpretation我個人理解為＂得知預測模型怎麼預測(i.e.使用哪些features及相關的權重，且很好解釋)  

# Microsoft Interpret
An overall interpret Opensource package by Microsoft(has SHAP/LIME/EBM) , a very nice visualization tool for interpretation  
Internal Engine : Explainable Boosting Machine(EBM) (GA2M Paper) : http://www.cs.cornell.edu/~yinlou/papers/lou-kdd13.pdf  
Github: https://github.com/microsoft/interpret  

My comment:  
與一般機器學習不同，Microsoft所開發出來（與想推銷的）內部引擎EBM為一個可解釋的＂預測模型＂，使用統計學習方法，以GAM為Baseline Model，將GAM回歸出來的殘差，再做一次交叉項(Pairwise Interaction effect)的回歸，期望把更多的殘差以交互作用來納入整體解釋能力。  
但個人感覺光是GAM可能就很難解釋了(Smoother function，你所train出來的個別函數是什麼等等)，加上GA2M又更難解釋，見仁見智。  


## 一些pdf檔案為我看過之後加上一些自己的筆記，有需要拿就自取吧

a very good book for Interpretable Machine Learning(online,free), I learned very very much from this:
https://christophm.github.io/interpretable-ml-book/
