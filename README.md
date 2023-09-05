# FinArg-1_ARI_MacB2
## Financial Argument Relation identification (FinArg-1_ARI)

## Table of contents
The introduction of FinArg-1_ARI_MacB2  
The contribution and insight of FinArg-1_ARI_MacB2  
Source  
Other  
References

## The introduction of FinArg-1_ARI_MacB2  
---------------------------------------------------
The global financial landscape's complexity and volatility necessitate robust methodologies and tools for decision-making and risk management. With the rapid evolution of financial technology and the rise of natural language models, we're entering a transformative era in fintech. Traditionally, fintech focused on data analytics for efficient services. However, thanks to advances in natural language processing (NLP), the focus has shifted to textual data, unlocking unprecedented opportunities. Textual sources like news articles, social media, and market commentary offer rich market insights. NLP enables us to extract valuable forecasts and insights for investors, risk managers, and financial professionals.
Previous financial NLP studies mainly focused on binary sentence classifications for stock market predictions, but this narrow approach falls short of meeting the industry's demand for multifaceted analyses. Recognizing the limitations of traditional quantitative models, sentiment NLP analysis is crucial for understanding market forces.
In finance, understanding market sentiment remains a cornerstone of decision-making, influenced by economic metrics, geopolitics, and market narratives. Researchers are exploring the value of financial texts and simulating investors' thought processes. This convergence of linguistics, behavioral finance, and technology is reshaping financial analysis.
In light of this, our focus has pivoted towards examining inter-sentential relationships within financial narratives, aiming to capture correlations between financial events in a more comprehensive and detailed manner. Specifically, our task aims to identify the attack and support argumentative relationships in the social media discussion thread. Instead of analyzing a single social media post, we consider the whole discussion thread. In this task, we attempt to link the posts with attack and support labels. With these labels, we can understand the argumentation structure among opinions. We are confident that through this exploration, we are better equipped to tackle the challenges of the financial market and bolster sustainable growth in the sector.  

![Image](https://github.com/nlptmu/FinArg-1_ARI_MacB2/blob/main/figure/framework_for_github.png)

Figure 1 The system architecture of our proposed method


## The contribution and insight of FinArg-1_ARI_MacB2   
---------------------------------------------------
-	Sentiment and Emotion Recognition in Textual Content: By rigorously analyzing sentiments within financial narratives from sources such as social media and news outlets, our approach unveils intricate insights into market mood and investor sentiment.  
-	Strategic Decision Analysis: Our methodology efficiently dissects financial articles and social media commentaries, unveiling their latent implications on specific stocks, industries, or entire market trajectories. This analysis not only predicts market trends but empowers investors with refined insights, facilitating astute investment choices.  
-	Empirical Efficacy of Our Approach: Our BERT-Ensemble Learning mechanism, enriched with Linguistic Features, has proven its mettle in analyzing attack and support relations within financial social media analytics, showcasing both feasibility and superior performance.

## Source  
---------------------------------------------------
- You can find this tutorial on how to use FinArg-1_ARI_MacB2 for a quick start [here](https://github.com/nlptmu/FinArg-1_ARI_MacB2/blob/main/code/Financial%20Argument%20Relation%20identification.ipynb). All related code is putted at folder named “code“.

## Other 
---------------------------------------------------
This method is inspired by our paper BERT-Ensemble Learning with Linguistic Features for Analyzing Attack and Support Relations in Financial Social Media Analytics in which more information about the model detail can be found.  

### Abstract
As the financial domain evolves, there's a pressing need for nuanced comprehension of its texts. This research delves into natural language reasoning within financial discourses by analyzing inter-sentence relationships, utilizing a diverse Chinese financial dataset from social media spanning stocks, housing prices, and tech firms. Recognizing that text relationships are contextual and can be swayed by varying lexicon, we introduce an approach that integrates external knowledge into expansive language models. This not only enriches text feature representation but also prioritizes crucial terms while sidelining potentially misleading ones. Performance-wise, our model surpasses its contemporaries, validating its prowess in offering precise and holistic insights into financial text relationships. Experimental results substantiate that our approach not only effectively predict the relationship but also outperforms the comparisons and achieve SOTA performance. This underscores the potential of our method in fine-grained argument understanding within financial analysis.


## References 
---------------------------------------------------
Please cite these papers in your publications if FinArg-1_ARI_MacB2 helps your research.

    @Article{
      author = {Hen-You Lin, Eugene Sy, Tzu-Cheng Peng, Shih-Hsuan Huang, Yung-Chung Chang},
      conference = {NTCIR-17},
      title = {TMUNLP at the NTCIR-17 FinArg-1 Task},
      year = {2023}
    }
    @Article{
      author = {Hen-You Lin, Tzu-Cheng Peng, Yung-Chung Chang},
      conference = {TANET & NCS},
      title = {BERT-Ensemble Learning with Linguistic Features for Analyzing Attack and Support Relations in Financial Social Media Analytics},
      year = {2023}
    }
