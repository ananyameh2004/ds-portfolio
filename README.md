# ds-portfolio
# Data Science Portfolio

Hi! This is my portfolio for my data science class. I will be updating 
this page throughout the semester as I work on my final project.

## Final Project Ideas

### Idea 1: Housing Affordability in the US
I want to look at how housing prices have changed over time compared to 
average incomes, and whether its getting harder for people to afford homes 
in certain cities vs others.

Questions I want to explore:
- Which US cities have seen the biggest gap grow between home prices and 
  average household income over the last 10 years?
- Has remote work after COVID caused housing prices to spike more in 
  mid sized cities compared to big coastal ones?

### Idea 2: College Tuition and Student Debt Trends
Tuition keeps going up and I want to understand how much it has actually 
increased over time and whether certain types of schools are worse than others.

Questions I want to explore:
- How has average tuition at public vs private universities changed 
  over the last 20 years adjusted for inflation?
- Is there a relationship between a schools tuition cost and the average 
  student debt of its graduates?

### Idea 3: Fast Food Nutrition and Pricing
I think it would be interesting to look at whether cheaper fast food options 
are actually worse for you nutritionally or if thats just an assumption people make.

Questions I want to explore:
- Is there a relationship between the price of a menu item and its 
  calorie or sodium content across major fast food chains?
- Which fast food chains have the biggest gap between their healthiest 
  and least healthy menu options?
 ## Week 10 Update

I am doing this project on my own.

For my final project I decided to go with the housing affordability topic. 
I think its one of the most relevant economic issues right now especially 
for people my age who are about to enter the workforce and start thinking 
about where to live, so I thought it would be interesting to actually dig 
into the data behind it.

### Data Sources I'm Considering

**Zillow Research Data** (CSV downloads from zillow.com/research/data)
Pros: really detailed, goes down to the city and zip code level, well known 
and widely cited source, has a long historical record
Cons: not a live API so I have to download it manually, and theres some 
restrictions on redistributing it

**FRED API** (Federal Reserve Economic Data)
Pros: free API with a key, super well documented, has tons of housing and 
income related indicators, reliable government source
Cons: mostly national or state level data so it wont give me city level 
granularity which is what I really want

**Census Bureau API** (American Community Survey)
Pros: official data, very detailed geographic breakdowns, free to use
Cons: the query syntax is kind of complicated and the response times 
are slow, took me a while to figure out how to use it

My plan is to combine FRED for things like mortgage rates and median income 
over time with Zillow data for city level home prices, and maybe pull in 
Census data for income by metro area.

### Questions I Want to Explore

1. In which US cities has the gap between median home prices and median 
household income grown the fastest over the last 10 years?

2. How closely do 30 year mortgage rates track changes in home sale prices 
across major cities, and is there a lag between when rates change and when 
prices respond?

3. Did the COVID period cause a lasting shift in home prices in mid sized 
cities compared to large coastal ones, and have those differences started 
to reverse or are they sticking around?
