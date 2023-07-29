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

I was shocked by the number of COVID cases. I originally believed there might only be 13 million cases or, at most, 20 million cases, but after analyzing the data, I discovered there were 102070172 cases in the US as a whole. This is a staggering number that I could never have imagined. Because of all the information I've read about death and the overcrowded hospital, my estimate of the number of deaths is 5 million, which is higher than the actual number of 1115001. However, the data indicate that our delivery of healthcare and immunizations was effective. Additionally, the data contradicts my prediction, showing that California has the most cases overall while Washington has the fewest.

## Reflection 3
Which county has the highest number of cases in the state of Washington, and does it surprise you? Why or why not? (You may need to google this county to learn about it) Answer at least in 1-3 sentences

In Washington state, King county has the highest number of cases. I don't know much about King county so the result does surprise me. After searching, I found that King county is the most populous county in Washington state, which lead it to be the county that has highest cases in WA. 

## Reflection 4
Why are there so many observations (counties) in the variable `lowest_deaths_in_each_state`? That is, wouldn't you expect the number to be around 50? Why is the number greater than 50? Answer in at least 1-3 sentences

There are so many observations because there are several counties in the same state that share the same amount of lowest death. 

## Reflection 5
What do you think about the number and scale of the inconsistencies in the data? Does the fact that there are inconsistencies mean that people should not use this data? Why or why not? Answer in at least 1-3 sentences



## Reflection 6
Why were you interested in this particular question? Were you able to answer your question with code? What did you learn? Answer in at least 1-3 sentences

## Reflection 7
What, if anything, made you curious about this COVID analysis? What, if anything, surprised you? What might you do the same or differently on your next data wrangling project? Answer in at least 1-3 sentences
