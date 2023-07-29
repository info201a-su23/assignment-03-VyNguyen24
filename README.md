# A2: U.S. COVID Trends

## Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through data. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps.

This assignment is your opportunity to work directly with the same data used by the [New York Times](https://github.com/nytimes/covid-19-data/). While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

## Getting Started
You should start this assignment by opening up the `analysis.R` script. The script will guide you through an initial analysis of the data.

* **Coding prompts.** Complete the coding prompts in `analysis.R`. You MUST use the `dplyr` package.

* **Reflection prompts.** Throughout `analysis.R`, there are prompts labeled `"Reflection"`. Please write at least 1-3 sentences for each of these prompts below in this `README.md` file. As appropriate, provide evidence, give justification for your opinions, or genuinely reflect on your views. Please strive for concise, clear, and interesting writing.

## Reflection 1
Before actually calculating the total number of COVID cases and deaths, record your guesses for the following questions.

Guess: How many total COVID cases do you think there have been in the U.S.?  
I guess it could be around 13 million

Guess: How many total COVID-related deaths do you think there have been in the U.S.?
I think it could be around 5 million

Guess: Which state do you think has the highest number of COVID cases, and which state do you think has the lowest?
I think Texas could be the state that has the highest cases and HI could have the lowest

## Reflection 2
Did the number of COVID cases and deaths surprise you? Why or why not? What about the states with the highest and lowest number of cases? How did your guesses line up with the actual results? Answer in at least 1-3 sentences

The number of COVID cases shocked me. After examining the data, I learned there were 102,070,172 cases in the US as a whole, contrary to my initial estimation that there might only be 13 million cases or, at most, 20 million cases. This is a staggering sum that I never could have anticipated. My estimate of the number of deaths is 5 million, which is higher than the actual number of 1,115,001 because of all the information I've read about death and the overcrowded hospital. The data also shows that California has the most overall cases while Washington has the fewest, which goes against my prediction.

## Reflection 3
Which county has the highest number of cases in the state of Washington, and does it surprise you? Why or why not? (You may need to google this county to learn about it) Answer at least in 1-3 sentences

King county in Washington state has the most cases overall. Since I don't know much about King County, I am surprised by the outcome. Following some research, I discovered that King county is the most populous county in Washington state, therefore it also happens to has the most cases in the state. 

## Reflection 4
Why are there so many observations (counties) in the variable `lowest_deaths_in_each_state`? That is, wouldn't you expect the number to be around 50? Why is the number greater than 50? Answer in at least 1-3 sentences

There are a lot of observations in the "lowest_deaths_in_each_state" section because i think there are several counties in the same state have the same number of lowest deaths. 

## Reflection 5
What do you think about the number and scale of the inconsistencies in the data? Does the fact that there are inconsistencies mean that people should not use this data? Why or why not? Answer in at least 1-3 sentences

As far as I can tell, the data set contains some unknown and missing values. This frequently occurs in big data, so we must be cautious in how we handle the missing value in order to lessen the bias in the data set. Since this data set is large, I believe the inconsistencies are acceptable and the data is still useful for analyzing the trend in COVID, but we have to aware of dealing with the missing values. 

## Reflection 6
Why were you interested in this particular question? Were you able to answer your question with code? What did you learn? Answer in at least 1-3 sentences

AI want to see how the COVID growth changes one month before and after March 15, 2020, since that is when the US began to impose quarantine and restrictions. As a result, I try to write code to see if there is still a significant increase in cases one month after the restriction. They continue to grow rapidly, though, and I was unable identify their impact. Because I believe that more observations and other factors need to be looked at in order to determine whether or not the quarantine has an effect on the spread of COVID, I was unable to find the answer to my question using my code. 

## Reflection 7
What, if anything, made you curious about this COVID analysis? What, if anything, surprised you? What might you do the same or differently on your next data wrangling project? Answer in at least 1-3 sentences

I'm curious about how they verify the data they gather, and I'm taken surprise by the fact that Washington State has the fewest cases. Also, I initially didn't give the missing data much thought when working with big data, I now believe that I should exercise greater caution. 
