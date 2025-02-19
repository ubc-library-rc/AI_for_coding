---
title: 2. How to ask for help
layout: default
nav_order: 6
has_toc: T
---
## Topic Summary
We learn how to use ChatGPT to better understand exiting code and how to generate new code. 

## Learning Objectives


## Ask the AI for help
AI can help with a lot, but today we focus on coding. Specifically, how to ask questions to get good, complete, answers/code from the AI.
In "AI speak", a question/text input you ask/give the AI is called a prompt. 

### AI can explain code to you
Paste in some code in ChatGPT and ask it to explain what the code means. Let's try with this code:
```
library(tidyverse)

ggplot(mtcars, aes(x=cyl, y=mpg))+
  geom_point()

```
#### Note about LLM explanations
LLMs are text generators, so when you ask them to explain something, then generate text that explains the concepts you asked about. However, LLMs do not <em>understand</em> the output, this is a small but important distinction. This means that if the answer seems superficial and not fully satisfactory, that’s because it is. You can ask the LLM to re-phrase or re-explain, but at some point, it might be better to go look at content written by a human. 

### AI can write code for you
ChatGPT and other AI models are often text generators. Code is text, so it is well within their capabilities to code for you (most of the time). However, if we recall from last week, how questions are worded is very important as it affects the quality and completeness of the answer the AI generates. 
In this section, we learn how to talk to the AI to get the best possible answer. 

#### Breakdown the analysis into steps: Steps to make a sandwich
Let's ask ChatGPT how to make a sandwich. You can specify preferences, like we did (cheese!).

<div style="margin-left: 5%; margin-top: 20px; margin-bottom: 40px">
<img src="images/cheese_steps.png" alt="sandwich steps" width="50%"/>
</div>

#### Breakdown the analysis into steps: Steps to run an analysis of variance (ANOVA)
Something more serious, asking ChatGPT how to run an ANOVA in R.

<div style="margin-left: 5%; margin-top: 20px; margin-bottom: 40px">
<img src="images/ANOVA.png" alt="ANOVA steps" width="50%"/>
</div>

## Translate the steps into prompts
Each part of the response to the ANOVA prompt is numbered into steps. You can ask ChatGPT to help you with each part individually. 
Remember, asking multiple questions at once lead to the AI ignoring parts of the prompt, so asking for small parts of the end result is the best way to get a complete answer. 

## Notes about speaking to the AI
When you input data (usually text) in ChatGPT, the text is converted to a format the AI can understand. This sometimes leads to the AI not understanding the issue, because the issue gets formatted out. This seems to be getting rarer as the AI improves. 

Remember, the AI is not reasoning, so ask it for sources and evaluate if the output you get from the analysis makes sense with what you were expecting from your data. Having dummy (fake) datasets where you know the outcome are a great way to test if the code you got makes sense (next week's workshop).


## Glossary 
|Data types|Shapes/formats the data are in. These could be a dataframe, a matrix, a list, a vector to name a few. Statistical analyses and graph generation require data in a specific format.|
|Prompt|Text input you give the LLM.|



