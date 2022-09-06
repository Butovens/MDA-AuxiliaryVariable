# Missing Data Analysis: Auxiliary variables 

## This is an example of auxiliary variable selection in missing data analysis.

The substantive goal is to fit a multiple regression model that predicts intentions to use steroids from the following predictors: knowledge of steroid effects, knowledge of testosterone effects, and knowledge of supplements. 

Here we want to assess whether there are systematic relationships between the probability of missing data and variables in the data set. More specifically, the goal is to identify variables that might relate to the probability of missing one of the analysis model variables. 

The analysis model is: mayuse = b0 + b1(sterknow) + b2(testknow) + b3(suppknow) + e

Note that among the four variables in the analysis model, only **sterknow** has complete data. These variables can potentially serve as auxiliary variables that can make the MAR (Missing At Random) assumption more plausible.

* **age** (student age)
* **gpa** (student gpa)
* **faminc** (family income)
* **mayuse** (intentions to use steroids)
* **attuse** (attitudes toward steroid use)
* **attusers** (attitudes toward steroid users)
* **streneff** (strength training efficacy)
* **athabil** (perception of athletic ability)
* **wghtsat** (satisfaction with body weight)
* **sterknow** (knowledge of steroid effects)
* **testknow** (knowledge of testosterone effects)
* **suppknow** (knowledge of supplement effects)
* **peerinfo** (peers as an information source)
* **teaminfo** (team as an information source)
* **coainfo** (coach as an information source)
* **coachtol** (coach tolerance of steroid use)
* **bodyimg** (body image)
* **esteem** (self‐esteem)
* **impuls** (impulsivity)
* **rmay** (missing data indicator for mayuse)
* **rsupp** (missing data indicator for suppknow)
* **rtest** (missing data indicator for testknow)
