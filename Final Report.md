1. Introuduction 

Corpus research has provided extensive data on how often words are used in texts and the typical patterns in which they appear. This information helps prioritize which vocabulary and phrases should be taught to learners, based on their real-world relevance and frequency. Unlike traditional methods that focused on teaching grammar rules by difficulty, a lexical approach emphasizes teaching vocabulary based on its practical usage in everyday language. This approach ensures learners acquire language skills that are more effective and applicable in real-life contexts. Additionally, corpus studies emphasize the importance of teaching collocations—words that frequently occur together in natural language. Mastering collocations enhances fluency and naturalness in language use, reflecting how native speakers naturally express themselves. By incorporating collocations and frequently used vocabulary into language instruction, educators can better prepare learners to understand and use language proficiently in various contexts. Thus, integrating corpus-based lexical research into language teaching not only makes learning materials more relevant and practical but also supports learners in developing communication skills that closely align with real-world language use. Well-selected chunks in the syllabus offer the learner the practical value of being among the most frequent, and hence most useful, elements of the language. (Lewis et al., 1997)

2. Literature Review

* The primacy of chunks
   
 The traditional approach to language learning initially emphasized single words alongside multiword combinations, but there has been a noticeable shift towards focusing predominantly on these multiword units, known as lexical chunks. These chunks serve as the primary building blocks in organizing a lexical syllabus. They encompass both grammatical and non-grammatical structures and vary in terms of fixedness, allowing different degrees of flexibility in usage. Some expressions, like "on the other hand," are highly fixed, while others, such as "make a long story short," allow more variation. Chunks also differ in how transparent their meanings are based on their component words, with some being highly compositional (like "banana yellow") and others less so (like idiomatic expressions such as "bite the big one"). And the discussion of primacy of chunks has been connected with the research of collocation. According to Conzett et al. 2000, Collocations might be described as the words that are placed or found together in a predictable pattern. Examples range from two word combinations such as problem child to extended combinations such as He’s recovering from a major operation. 

* Frequecny of words
   
 The frequency of collocations dictates the development of lexical phrases, influencing how easily idioms are understood. Idioms that appear frequently are more accessible because their figurative meanings are widely recognized through repeated exposure, overshadowing their literal interpretations (Giora, 1997; Nippold & Rudzinski, 1993). When cognitive demands are high, relying on established phrases becomes essential, reflecting the principle that retrieving familiar expressions is less taxing than constructing new ones (Bresnan, 1999). Kuiper's (1996) examination of "smooth talkers," such as sports commentators and auctioneers, underscores how frequent exposure to communicative contexts enhances the ability to process and articulate observations in real time. This highlights the pivotal role of frequency in language comprehension and production, emphasizing the practical benefits of mastering commonly used phrases and idiomatic expressions.

* Research Questions
  
1)	How does the frequency of the adverb "very" differ between written and spoken texts?
2)	What are the different distributional patterns of "very" as an adverb, adjective in written and spoken text? 
3)	Which are thte alloccaion patterns "very" in written and spoken texts? And how different?
4)	What is the relative frequency of other intensifiers in comparison to "very" in written and spoken texts? And how different?

* Hypothesis Formation + Approach to Hypothesis testing (rationale)
  
Hypothesis Based on Research questions 1: 'Very' is used more frequently in spoken texts than written texts
Hypothesis Based on Research questions 2: 'Very' is used more frequently as an adverb than as an adjective in both written and spoken texts, reflecting its primary function to intensify adjectives and adverbs.
Hypothesis Based on Research questions 3: “Very” is most frequently collocated with much in both spoken and written text. 
Hypothesis based on Research Question 4: Other intensifiers is frequently used as much as very in spoken and written text. 

3.	Methodology 
  
*	Data Description
   
A.	Spoken data : TED Talks are free online videos from experts on various topics, including communication. The selected TED Talks are between 6 and more than 18 minutes long, providing sufficient content for analysis. We removed speakers with strong accents to ensure clear speech patterns and deleted all time stamps and speaker names to focus on the content. After cleaning data, we combined them into a single dataset. This dataset, saved in CSV format, is ready for analysis using computational tools.

B.	Written data : The Corpus of Contemporary American English (COCA) is a large collection of American English texts used for language research. For our study, we focused on COCA texts about communication to see how people use language in different situations. We removed texts with strong regional accents to keep the language patterns clear and uniform. We also deleted all time stamps and author names to focus only on the content. After cleaning the texts to remove extra information, we combined them into one dataset and saved it in CSV format for easy analysis. To ensure uniform lexical size between the two datasets, the COCA texts were reduced to match the lexical size of the TED transcripts. (219,507 words) 

4.	Data analysis methods
   
A.	Frequency comparison of very in both Spoken and written text: word count
B.	The distributional patterns of "very" as an adverb, adjective, and noun in written and spoken text: Loading NLP Model, Chunk Processing, POS Tagging   
C.	Collocated words following very in spoken and written text: Collocation Analysis, Tokenization, Bigram Finder, Filtering and Sorting
D.	Other intensifier frequency in spoken and written text: Text Extraction, Text Tokenization and Counting, Plotting Frequencies 

5. Results and Discussion  
RQ1 
Data Analysis 
Reporting results
Data visualization 
![image](https://github.com/Englishson0909/S24Corpus-final/assets/127401703/a5e2c8c3-711c-4c6d-88bf-258ef3805c1a)


RQ2 
Data Analysis 
Reporting results
Data visualization
![image](https://github.com/Englishson0909/S24Corpus-final/assets/127401703/0da2eca0-3ae6-4403-b23a-ad5b484fe28c)

RQ3
Data Analysis 
Reporting results
Data visualization
![image](https://github.com/Englishson0909/S24Corpus-final/assets/127401703/c0f461d8-6044-4e40-9327-8da719bd576e)

RQ4
Data Analysis 
Reporting results
Data visualization
![image](https://github.com/Englishson0909/S24Corpus-final/assets/127401703/c0058213-ea2c-49c9-8282-3e0680e8dd6d)


Hypothesis testing using chi-square test (Frequency data)
  
* RQ1 
Null Hypothesis (H0): The frequency of "very" is independent of the type of text (Spoken: TED, Written: COCA).
Alternative Hypothesis (HA): The frequency of "very" is dependent of the type of text (Spoken: TED, Written: COCA).

Chi-squared test result: The Chi-squared test of independence was applied to assess if the observed differences in frequeny of very across text types were statistically significant ( χ2=103.95755 , df = 1, p<0.01 ).
Interpretation: The Chi-squared statistic of 103.95755 with 1 degree of freedom and a p-value of p<0.01 suggests that there is a statistically significant association between text type (TED vs. COCA) and the frequency of the word "very". The observed differences between actual and expected frequencies are significant at the conventional significance level of 0.05 (and even much lower thresholds).
Conclusion: The test results indicate that the type of text (TED vs. COCA) significantly influences the frequency of the word "very". This significant difference suggests that the usage of "very" varies considerably between spoken (TED) and written (COCA) texts. Language researchers and educators might consider these differences when analyzing language use in different contexts or when designing language learning materials that target different types of text. 


* RQ2 
Null Hypothesis: The distributional patterns of "very" as an adverb and adjective are independent of the type of text (Spoken: TED, Written: COCA).
Alternative Hypothesis: The distributional patterns of "very" as an adverb and adjective are dependent on the type of text (Spoken: TED, Written: COCA).

Chi-squared test result: The Chi-squared test of independence was applied to assess if the observed differences in the distributional patterns of "very" as an adverb and adjective are independent of the type of text. The test was not statistically significant (χ2=0.0641, df=1, p=0.8).

Interpretation: The Chi-squared statistic of 0.0641 with 1 degree of freedom and a p-value of 0.8 suggests that there is no statistically significant association between the distribution patterns of "very" as an adverb and adjective and the type of text (TED vs. COCA). The observed differences between actual and expected frequencies are not significant at the conventional significance level of 0.05.

Conclusion: The test results indicate that the type of text (TED vs. COCA) does not significantly influence the distribution of the word "very" as an adverb and adjective. This lack of significant difference suggests that the usage of "very" as an adverb and adjective is similar between spoken (TED) and written (COCA) texts. Language researchers and educators might consider that these similarities imply consistent usage patterns of "very" across different types of texts when analyzing language use or designing language learning materials.

* RQ3 
 Null hypothesis: The collocation patterns of "very" with other words are independent of the type of text (Spoken: TED, Written: COCA). 
Alternative Hypothesis: The collocation patterns of "very" with other words are dependent of the type of text (Spoken: TED, Written: COCA).

Chi-squared test result: The Chi-squared test of independence was applied to assess if the observed differences in the collocation patterns of "very" are not independent of the type of text. The test was statistically significant (χ2=120.4340, df=25, p=0.0).

Interpretation: The Chi-squared statistic of 120.4340with 25 degree of freedom and a p-value of 0.0 suggests that there is statistically significant association between the collocation patterns of "very" and the type of text (TED vs. COCA). The observed differences between actual and expected frequencies are significant at the conventional significance level of 0.05.

Conclusion: The test results indicate that the type of text (TED vs. COCA) does significantly influence the collocation distribution of the word "very" This significant difference suggests that the collocation distribution of  "very"  is differernt between spoken (TED) and written (COCA) texts. Language researchers and educators might consider that these differences imply consistent usage patterns of "very" across different types of texts when analyzing language use or designing language learning materials


* RQ4 
Null Hypothesis 
The frequency of intensifiers is independent of types of text. 
Alternative hypothesis 
The frequency of intensifiers is dependent of types of text.

 
Chi-Squared Test Result:The Chi-squared test of independence was applied to assess if the observed differences in the use of other intensifier patterns are not independent of the type of text. The test was statistically significant (χ² = 83.3710, df = 8, p < 0.001).

Interpretation:The Chi-squared statistic of 83.3710 with 8 degrees of freedom and a p-value less than 0.000 suggests that there is a statistically significant association between the use of other intensifiers and the type of text (TED vs. COCA). The observed differences between actual and expected frequencies are significant at the conventional significance level of 0.05.

Conclusion: We reject the null hypothesis and conclude that the frequency of intensifiers is dependent on the type of text. This indicates that the usage patterns of intensifiers vary significantly between spoken texts (TED) and written texts (COCA). This finding could be useful for linguists and educators to understand stylistic differences and to tailor language learning materials accordingly.

6. Summary
  
  The research examined four key questions regarding the usage patterns of the word "very" and other intensifiers across spoken (TED) and written (COCA) texts. Findings revealed significant differences in the frequency of "very" between TED and COCA, indicating its varied usage in different contexts. However, the distribution of "very" as an adverb and adjective showed no significant variation between TED and COCA, suggesting consistent usage patterns across spoken and written texts. Collocation patterns of "very" exhibited significant dependency on text type, highlighting distinct linguistic contexts between spoken and written language. Additionally, the study confirmed that the frequency of other intensifiers is significantly influenced by text type, underscoring the need for tailored linguistic analyses and educational approaches across different textual domains.
  
* Limitations and future research directions
  
Limitation: The study lacks research on the frequency of different parts of speech of "very". Additionally, the spoken text consists of speeches, which may not represent all spoken texts, and the written text consists of news articles, which may not represent all written texts.
Future Research directions: There is a need for research on the trends in the use of "very" and "so" among native English speakers in respect of spoken and Written.  

* Reference 
Conzett, J., Hargreaves, P. H., Hill, J., Lewis, M., & Woolard, G. C. (2000). Teaching collocation: Further developments in the lexical approach (pp. 163-199). M. Lewis (Ed.). Boston: Thomson Heinle.

Ellis, N. C. (2002). Frequency effects in language processing: A review with implications for theories of implicit and explicit language acquisition. Studies in second language acquisition, 24(2), 143-188.

Lewis, M., Gough, C., Martínez, R., Powell, M., Marks, J., Woolard, G. C., & Ribisch, K. H. (1997). Implementing the lexical approach: Putting theory into practice (Vol. 3, No. 1, pp. 223-232). Hove: Language Teaching Publications.

강선희.(2011).고등학교 1학년 영어교과서에 나타난 확대어들(amplifiers)의 코퍼스 분석.석사학위논문.공주대학교 교육대학원,공주

심춘화.(2012).“부사+형용사”연어의 코퍼스 기반 분석:제 7차 개정 중등 및 고등 전 학년 영어 교과서에 나오는 정도 부사를 중심으로.석사학위 논문,동국대학교 교육대학원,서울

정연창.(2009).부사 유의어 ‘Entirely,Totally,Wholly’의 사용에 관한 코퍼스 기반 연구.언어 연구,26(2),85-101.

정원일.(2005).고등학교 영어교과서에 나타난 정도부사의 코퍼스 기반 연구. 석사학위논문.동국대학교 교육대학원,서울

[Google Colab](https://colab.research.google.com/), 

[Google Colab Link](https://colab.research.google.com/drive/1GZhWO_XkkVohyj899aADQL_vBpyFX3Ow#scrollTo=vzm2S2IKyGhB)

Chatgpt (https://chatgpt.com/)

Oxford dictionary 
