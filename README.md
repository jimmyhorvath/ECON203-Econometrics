# ECON203-Econometrics
If Economics-202 is designed to develop a student’s ability to solve problems by supplementing common sense with simple quantitative models, Economics-203: Econometrics is designed to build upon the Econ-202 foundation. The class expands the list of concepts and techniques considered, thus broadening the types of problems that can be addressed using quantitative models. Additionally, the class considered methodological issues related to data quality. We constantly asked the question: “What is the use of fancy statistical/econometric models if the data are faulty?” 

We had four goals for the class. First, Professor Blunch wanted us to understand and be able to critically discuss potential pitfalls of data analysis, especially pertaining to the analysis of education and health data. I found the health data portion the most interesting, and as such, took Economics-376: Global Public Health as a result. Secondly, we wanted to know the classical conditions and the Gauss-Markov Theorem, understanding the importance of these as crucial underpinnings of applied econometric analysis. Thirdly, my group understood and critically applied different estimation methods and corrections. These included OLS, correction for serial correlation and/or heteroskedasticity. Lastly, to culminate these thoughts, we formulated and conducted an empirical group project for a topic of our choice, based on economic theory. We used the Stata statistical package to do “real time” data analyses, helping develop our research.

I chose Maddie Weller as my project partner, as she was reliable and intelligent during the Economics-202 project. I also knew she enjoyed sports, as she’s a two-year captain on the volleyball team. I wanted to sprinkle sports onto my love for econometrics, and Maddie was on the same page. Thus, we set sail on a statistical voyage to explore the NFL Draft. 

There are many variables influencing when a player is selected in the draft. Our paper analyzed these variables and answered two research questions. First, what are the most important factors in producing first-round draft picks in the NFL? Secondly, conditionally that a player is a first-round pick, what are the factors that affect where they’re picked in the round?

Being college athletes, we understood better than non-athletic economists that the results have massive implications for colleges. With lucrative media contracts, sponsorship deals, and ticket sales, schools continue to find ways to maximize their revenue potential. For many large colleges, football is the largest revenue earner. Thus, programs focusing on the most influential variables can theoretically produce more first-round picks, earning more money for the school overall. Additionally, a program that produces more first-round picks can better recruit top-tier high school players, improving the team and enhancing the future of the college. 

To answer the first question, we used the linear probability model to measure a player's likelihood of being picked in the first round. The coefficients suggested the expected change in percentage points that a player is selected in the first round, given the conditional explanatory variable. 

To answer the second question, we used the traditional OLS estimator based on the given regressors in the theory section. It is essential to explain that a "higher" draft pick is desired; being drafted #1 overall versus #10 is a massive difference. Therefore, some of the coefficients produced by this model were negative. This means a player is drafted earlier and "higher," so they are closer to being the #1 pick, which is what we were looking to observe. The variables that yielded the most negative OLS estimators were the most relevant for answering this question. Ultimately, we titled this variable “pick height” in the first round. 

Our regressions comprised ten variables: school winning percentage, school football expenses, race, height, weight, if a player played in the Southeastern Conference (SEC), if a player grew up in the Deep South area of the United States, and position. 

Clinically, we were able to draw conclusions on statistically significant results, which only resulted with offensive positions. First, quarterbacks are 88% more likely to be first-round picks than second-round picks. On average, QBs move up 7 slots if they are first-round selections. Additionally, Black QBs are 3% more likely than white QBs to be a first-round pick than a second-round pick. Secondly, offensive linemen are 90% more likely to be first-round picks than second-round picks. Additionally, if a lineman is 23 pounds heavier than the average from 2013–2023, they’re 62% more likely to be a first-round pick than a second-round pick. Ultimately, these findings confirmed our theory that the NFL is a passing league, and as such, general managers want quarterbacks who can throw, and heavy offensive linemen to protect them. Also, a significant result is that we’re 90% confident that both school winning percentage and college football expenses impact a player’s draft stock. 

A few takeaways are critical to understand. First, college programs should emphasize their strength & conditioning and nutrition programs to improve where their players are selected. This is especially important for offensive linemen. Secondly, quarterbacks are the top draft priority to NFL teams. They are the "face of their franchise," increasing visibility of their alma mater to the entire nation. Thirdly, schools should spend more money on football, improving factors like strength and conditioning or facilities. Lastly and surprisingly, all defensive positions, the Deep South variable, and the SEC variable lacked significance, questioning the pertinence of these variables in draft tendency.

