---
title: 2. Breaking down analyses
layout: default
nav_order: 6
has_toc: T
---
## Ask the AI for help
AI can help with a lot, but today we focus on coding. Specifically, how to ask questions to get good, complete, answers/code from the AI.

### AI can explain code to you
Paste in some code in ChatGPT and ask it to explain what the code means. Let's try with this code:
```
library(tidyverse)

ggplot(mtcars, aes(x=cyl, y=mpg))+
  geom_point()

```
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





