@snap[north]
@size[1.5em](Diversity and Demographic Bias in Recommender Systems with a focus on the  music industry)
@snapend

@snap[south]
@css[byline](Maaike Visser, Robin Cromjongh and Cedric Willekens)
@snapend

Note:
  - Summary of the introduction
    - Recommender systems have become more and more popular since everything is going more and more online. A lot of these systems focus on metrics such as accuracy. Lately a lot of research has switched to a more social aspect, investigating the fairness of these systems. We want to therefore investigate the efforts that haver been made to combat unfairness in these recommender systems. Specifically with respect to demograpic biases and diversity. 

    - This paper is not so much computer science oriented??

---

@snap[west span 30]
Research questions
@snapend

@snap[east span-50]
@ol
- What efforts have been made by the community to increase fairness in recommender systems?
- What efforts have been made to increase fairness in music recommender systems in particular?
@olend
@snapend

note: 
  - Our first research question is: .... 
    - sub divided in diversity and demographic biases. 
  - Our second research question is...  

---

@snap[west span-45]
What our paper covers
@snapend

@snap[east text-white span-50]

@ol
- Recommender Systems
- Fairness in Recommender Systems
- Fairness in music recommender systems
- Conclusion and recommendations
@olend

@snapend


---

## Recommender Systems

note: 
  - so before we can talk about rec syss we need to talk about what kind of systems there exist and how they work. The 3 main ones are content based approach, collaborative approach and the hybrid approach. We will start of with the content based approach. 

+++ 

### Content based approaches

@ul
- Recommend items similar to those the user has already expressed interest towards
- features to compare these items with are difficult to extract
- danger of overspecialization
@ulend
+++ 

### Collaborative approaches

@ul[spaced-list-items]
- Recommendations based on items peer users have rated
- Cold start problem  
  + Sub-optimal recommendations for new users
  + Missing ratings for new items
- Danger of overspecialization
@ulend
+++ 

### Hybrid approaches

@ul[spaced-list-items]
- Implementation combines collaborative and content based approach
  - Incorperate some content based characteristics into collaborative approaches
  - Incorperate some collaborative appraoches characteristics into content based approaches
  - Construct a model which unifies content and collaborative approaches.
@ulend

note: 
  - The idea is that we combine collaborative and content based approaches. This can be done in 4 ways. first way ... 

---

### Fairness in Recommender Systems

note: 
  - Fairness of rec sys has recently gained more attation. This is a tricky measurement because it has many aspects. In our paper we considered fairness in diversity and demograhpic biases. Furthermore we also looked at not only the fairness towards the user but also towards the producer. 

+++ 

### Diversity
@ul
- filter bubbles
  - What are they? 
  - How do they form
  - Effect on user/producer
- popularity bias
  - What is it?
  - Effect on user/producer
@ulend

+++ 

### Demographic Biases

@ul
- What is it? 
- Why undesirable
@ulend

+++

@snap[west span-20]
The Table
@snapend

@snap[east span-80]
![TableOfPapers](table.PNG)
@snapend

note: 
  - Collecting all the literature we have read for this paper we have created a table to indicate which topic each of these papers cover. Our findings from this table will be discussed in the next section. 

--- 
### Fairness in music recommender systems
<!-- @size[0.5em](Fairness in music recommender systems) -->

@ul
- A small fraction of the research done considers fairness in music recommender systems
- No focus on producers or on demographic biases
- Lot of research about increasing diversity, but not about the effect on the producers
@ulend


note: 
  - From the table we can see that there is only a limited number of papers (5) considers fairness for music recommender systems. Furthermore none of these 5 papers focus on the music producers or on demograhpic biases. This means that the papers about music mainly cover the topics of diversity, but not how this effects the producer. 

---

### General Conclusions

@ul
- Limited amount of research done on demographic bias compared to diversity
- Most papers do not explicitly consider producers
- There is a lack of research into music potentially due to a lack of available databases. 
@ulend

--- 

### Recommendations

@ol
- Collect more anonymous datasets
- Look into the effects of current recommender systems on producers
- Look into the existence of demographic bias
- Examine the effect of recommender systems on fiarness in the music industry
@olend

---

![Thank you](./template/img/thanks.jpg)

---

### Refernces
Abdollahpouri, H., Burke, R., and Mobasher, B. (2017).  Con-trolling Popularity Bias in Learning-to-Rank Recommenda-tion.   InProceedings  of  the  Eleventh  ACM  Conference  onRecommender Systems - RecSys ’17, pages 42–46.Adomavicius,   G.   and   Kwon,   Y.   (2008).OvercomingAccuracy-Diversity Tradeoff in Recommender Systems : AVariance-Based Approach.Adomavicius, G. and Kwon, Y. (2009).  Toward More DiverseRecommendations:  Item  Re-Ranking  Methods  for  Recom-mender  Systems.    In19th  Workshop  on  Information  Technologies and Systems.Adomavicius,  G.  and  Kwon,  Y.  (2014).   Optimization-basedapproaches  for  maximizing  aggregate  recommendation  di-versity.INFORMS Journal on Computing, 26(2):351–369.Adomavicius,   G.   and   Kwon,   Y.   O.   (2012).Improvingaggregate  recommendation  diversity  using  ranking-basedtechniques.IEEE  Transactions  on  Knowledge  and  DataEngineering, 24(5):896–911.Adomavicius,  G.  and  Tuzhilin,  A.  (2005).   Toward  the  nextgeneration of recommender systems: A survey of the state-of-the-art and possible extensions.Anderson, C. (2006).The Long Tail. Why the future of businessis selling less of more.Hyperion, Hachette, UK.Bradley,  K.  and  Smyth,  B.  (2001).   Improving  Recommen-dation  Diversity.   InProceedings  of  the  Twelfth  NationalConference in Artificial Intelligence and Cognitive Science(AICS-01), pages 75–84.Brynjolfsson,  E.,  Hu,  Y.,  and  Smith,  M.  D.  (2006).    FromNiches  to  Riches:  Anatomy  of  the  Long  Tail.MIT  SloanManagement Review, 47(4):67–71.Burke, R. (2017).  Multisided Fairness for Recommendation.Burke,  R.  and  Abdollahpouri,  H.  (2017).    Educational  rec-ommendation  with  multiple  stakeholders.   InProceedings-  2016  IEEE/WIC/ACM  International  Conference  on  WebIntelligence Workshops, WIW 2016, pages 62–63. IEEE.Burke, R., Sonboli, N., and Ordo ̃nez-Gauger, A. (2018).  Bal-anced  Neighborhoods  for  Multi-sided  Fairness  in  Recom-mendation.  InProceedings  of  the  1st  Conference  on  Fair-ness,  Accountability  and  Transparency,  volume  81,  pages1–13.Celma,`O. (2008).Music Recommendation and Discovery inthe Long Tail.  PhD thesis, Universitat Pompeu Fabra.Celma,`O.  (2010).Music  recommendation  and  discovery:The long tail, long fail, and long play in the digital musicspace.Music  Recommendation  and  Discovery:  The  LongTail, Long Fail, and Long Play in the Digital Music Space,pages 1–194.Celma,`O.  and  Cano,  P.  (2008).From  hits  to  niches?  orhow  popular  artists  can  bias  music  recommendation  anddiscovery.   InProceedings  of  the  2nd  KDD  Workshop  onLarge-Scale  Recommender  Systems  and  the  Netflix  PrizeCompetition  -  NETFLIX  ’08,  pages  1–8,  New  York,  NewYork, USA. ACM Press.Channamsetty, S. and Ekstrand, M. D. (2015).  RecommenderResponse to Diversity and Popularity Bias in User Profiles.pages 5–8.Domingues,  M.  A.,  Gouyon,  F.,  Jorge,  A.  M.,  Leal,  J.  P.,Vinagre,  J.,  Lemos,  L.,  and  Sordo,  M.  (2013).  Combiningusage and content in an online recommendation system formusic in the Long Tail.International Journal of MultimediaInformation Retrieval, 2(1):3–13.Ekstrand,  M.  D.,  Tian,  M.,  Ekstrand,  J.  D.,  Anuyah,  O.,Mcneill,  D.,  and  Pera,  M.  S.  (2018).   All  The  Cool  Kids,How Do They Fit In? Popularity and Demographic Biases inRecommender Evaluation and Effectiveness. InProceedingsof   the   1st   Conference   on   Fairness,   Accountability   andTransparency, volume 81, pages 172–186.Fleder,  D.  and  Hosanagar,  K.  (2009).   Blockbuster  Culture’sNext Rise or Fall: The Impact of Recommender Systems onSales Diversity.Management Science, 55(May 2017):697–712.Gaffney,  M.  and  Rafferty,  P.  (2009).   Making  the  Long  Tailvisible:  Social  networking  sites  and  independent  musicdiscovery.Program, 43(4):375–391.Hinz, O. and Eckert, J. (2010). The Impact of Search and Rec-ommendation  Systems  on  Sales  in  Electronic  Commerce.Business & Information Systems Engineering, 2(2):67–77.Hu, R. and Pu, P. (2011). Enhancing recommendation diversitywith  organization  interfaces.   InProceedings  of  the  15thinternational conference on Intelligent user interfaces - IUI’11, page 347, New York, New York, USA. ACM Press.Jannach, D., Kamehkhosh, I., and Bonnin, G. (2016).  Biasesin  Automated  Music  Playlist  Generation.   InProceedingsof the 2016 Conference on User Modeling Adaptation andPersonalization - UMAP ’16, pages 281–285.Jannach,  D.,  Lerche,  L.,  Kamehkhosh,  I.,  and  Jugovac,  M.(2015).   What  recommenders  recommend:  an  analysis  ofrecommendation biases and possible countermeasures.UserModeling and User-Adapted Interaction, 25(5):427–491.Kamishima, T., Akaho, S., Asoh, H., and Sakuma, J. (2012).Enhancement  of  the  Neutrality  in  Recommendation.InHuman  Decision  Making  in  Recommender  Systems  (De-cisions@RecSys’12)  In  conjunction  with  the  6  th  ACMConference on Recommender Systems, pages 8–14.Kamishima, T., Akaho, S., Asoh, H., and Sakuma, J. (2014).Correcting  popularity  bias  by  enhancing  recommendationneutrality.  InCEUR Workshop Proceedings, volume 1247,pages 4–5.Kamishima,  T.,  Akaho,  S.,  Asoh,  H.,  and  Sato,  I.  (2017).Model-Based Approaches for Independence-Enhanced Rec-ommendation.  InIEEE  International  Conference  on  DataMining Workshops, ICDMW, pages 860–867. IEEE.Kim,  H.  K.,  Kim,  J.  K.,  and  Ryu,  Y.  U.  (2010).   A  Local
9Scoring Model for Recommendation.  InProceedings of the20th Workshop on Information Technologies and Systems.Knijnenburg, B. P., Sivakumar, S., and Wilkinson, D. (2016).Recommender Systems for Self-Actualization.  InProceed-ings of the 10th ACM Conference on Recommender Systems- RecSys ’16, pages 11–14.Lee, E. L., Lou, J.-K., Chen, W.-M., Chen, Y.-C., Lin, S.-D.,Chiang, Y.-S., and Chen, K.-T. (2014). Fairness-Aware LoanRecommendation for Microfinance Services.Proceedings ofthe  2014  International  Conference  on  Social  Computing  -SocialCom ’14, pages 1–4.Levy,  M.  and  Bosteels,  K.  (2010).   Music  Recommendationand the Long Tail.  InWOMRAD 2010 Workshop on MusicRecommendation and Discovery.Matt,  C.,  Hess,  T.,  and  Weiß,  C.  (2013).    The  DifferencesBetween  Recommender  Technologies  in  their  Impact  onSales Diversity.  InICIS 2013 Proceedings.McNee,  S.  M.,  Riedl,  J.,  and  Konstan,  J.  a.  (2006).   Beingaccurate is not enough: how accuracy metrics have hurt rec-ommender systems.CHI’06 extended abstracts on Humanfactors in computing systems, page 1101.McSherry,  D.  (2002).   Diversity-Conscious  Retrieval.   pages219–233. Springer, Berlin, Heidelberg.Modani,  N.,  Jain,  D.,  Soni,  U.,  Gupta,  G.  K.,  and  Agarwal,P.  (2017).   Fairness  aware  recommendations  on  behance.InLecture Notes in Computer Science (including subseriesLecture  Notes  in  Artificial  Intelligence  and  Lecture  Notesin  Bioinformatics),  volume  10235  LNAI,  pages  144–155.Springer, Cham.Nelson,  J.  L.  (2015).   It’s  Time  to  Start  Paying  Attention  toLocal News.Nguyen,  T.  T.,  Hui,  P.-M.,  Harper,  F.  M.,  Terveen,  L.,  andKonstan,  J.  A.  (2014).   Exploring  the  Filter  Bubble  :  TheEffect  of  Using  Recommender  Systems  on  Content  Diver-sity. InProceedings of the 23rd international conference onWorld wide web - WWW ’14, pages 677–686.Pariser, E. (2011).The Filter Bubble.  The Penguin Group.Park, Y. J. (2013). The adaptive clustering method for the longtail  problem  of  recommender  systems.IEEE  Transactionson Knowledge and Data Engineering, 25(8):1904–1915.Park,  Y.-J.  and  Tuzhilin,  A.  (2008).  The  long  tail  of  recom-mender systems and how to leverage it.Proceedings of the2008 ACM conference on Recommender systems RecSys 08,page 11.Resnick,  P.,  Iacovou,  N.,  Suchak,  M.,  Bergstrom,  P.,  andRiedl,  J.  (1994).   GroupLens.   InProceedings  of  the  1994ACM conference on Computer supported cooperative work- CSCW ’94, pages 175–186, New York, New York, USA.ACM Press.Smyth,  B.  and  McClave,  P.  (2001).  Similarity  vs.  Diversity.pages 347–361. Springer, Berlin, Heidelberg.Van Alstyne, M. and Brynjolfsson, E. (2005).  Global Villageor  Cyber-Balkans?  Modeling  and  Measuring  the  Integra-tion  of  Electronic  Communities.Management  Science,51(6):851–868.Vargas, S. (2011). New approaches to diversity and novelty inrecommender  systems.The  Fourth  BCS-IRSG  Symposiumon  Future  Directions  in  Information  Retrieval  -  FDIA’11,pages 8–13.Wilkins, D. (2009).  The generic long tail.Yao,  S.  and  Huang,  B.  (2017a).Beyond  Parity:  FairnessObjectives for Collaborative Filtering.  (Nips).Yao,  S.  and  Huang,  B.  (2017b).   New  Fairness  Metrics  forRecommendation that Embrace Differences.Zhang,  M.  and  Hurley,  N.  (2008).   Avoiding  monotony.   InProceedings of the 2008 ACM conference on Recommendersystems - RecSys ’08, page 123, New York, New York, USA.ACM Press.Zhang,  M.  and  Mi  (2009).Enhancing  diversity  in  Top-N  recommendation.InProceedings  of  the  third  ACMconference  on  Recommender  systems  -  RecSys  ’09,  page397, New York, New York, USA. ACM Press.Ziegler,  C.-N.,  McNee,  S.  M.,  Konstan,  J.  A.,  and  Lausen,G.  (2005).   Improving  recommendation  lists  through  topicdiversification.    InProceedings  of  the  14th  internationalconference on World Wide Web - WWW ’05, page 22, NewYork, New York, USA. ACM Press.


---

@snap[top]
Questions?
@snapend

![questions](./template/img/questions-3.png)