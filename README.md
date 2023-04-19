# smartcity-africa-sentiments
Sentiment analysis for smart city projects in Africa. 
Codebase for our paper, [Highlighting smart city mirages in public perceptions: A Twitter sentiment analysis of four African smart city projects](https://doi.org/10.1016/j.cities.2022.103857).

V1 - Using project title as the search keyword.  
V2 - Adjusted search incorparoting specific terms like 'smart city', 'smart cities' and the country the project is found in.  
V3 - Same as V2 but without tweets from the official smart city project account. This is to eliminate bias.
V4 - A redo of V3 with less preprocessing. VADER sentiment analysis works with patterns optimized for social media... too much pre=processing makes a tweet look less like a regular tweet and can hurt performance.
