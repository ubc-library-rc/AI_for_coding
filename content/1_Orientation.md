---
title: 1. How do LLMs work?
layout: default
nav_order: 5
has_toc: T
---
# How do LLMs work?
To best use a tool, it is critical to understand how it works. In this first workshop of the _ChatGPT and Data Analysis_ series we use non-technical language to explain how Large Language Models (LLMs) like ChatGPT work, so you can use them more effectively. 

By the end of this session we hope you will:

- have a conceptual understanding of how LLMs work
- know how to access and engage with ChatGPT

## Where is ChatGPT?
ChatGPT is a Large Language Model (LLM) that is <a href="https://chatgpt.com/" target="_blank">available online,/a>. Just like any website, you need to be connected to the internet to use it. 

## Overview of what it means to “train a model”
The library has a detailed <a href="https://ubc-library-rc.github.io/llm/" target="_blank">workshop about LLMs</a>, so for this workshop we are not going to get very technical. The very simplified version of training a model includes two steps:
<ol type="1">
  <li>"the computer" looks at a lot of data to learn the patterns that exist</li>
  <li>"the computer" takes new data that it has never seen before. Then, using what it learned in step 1, "the computer" sees if it can predict what comes next.</li>
</ol>
Because LLMs are always improving, "the computer" (the LLM) always goes back to step 1.
Your brain is a very fancy LLM in a lot of ways. For example:
<ol>
<li>Have you ever finished someone's sentence for them? Does this happen more often when you know the person better?</li>
<li>Can you tell how people are feeling? Are you much more accurate with people you know better?</li>
</ol>
That's right, you are predicting what is going to come next based on previous data (experience with that person). More and better data = better predictions. In addition, humans can rely on more than just "data", "patterns", and "predictions" to shape and adjust their behavior. We rely on countext around this information to inform our actions. 

<p>That's very cool! But, this should cause you to pause. You are also wrong sometimes, even with the people you know best (partners, best friends, kids,...). </p>
<p>LLMs can be wrong too. LLMs can be wrong because the model is wrong and/or because they are missing context. This is a major concern when using LLMs, or any AI tools for that matter.</p>

## How to get factually correct answers
<p>In LLM speak, <em>mistakes</em> are often called <em>hallucinations</em>. They occur because the LLM outputs the best answer possible, but has insufficient data to provide a correct answer. </p>

### Ask for sources
ChatGPT has a way to turn on sources. Click on the globe (circled in blue) before submitting your query.

<div style="margin-left: 5%; margin-top: 20px; margin-bottom: 40px">
<img src="images/turn_on_websearch.png" alt="globe location" width="50%"/>
</div>

Once ChatGPT is done answering the question, you can click on the sources button (circled in blue) and the source will pop up on the right hand side. 

<div style="margin-left: 5%; margin-top: 20px; margin-bottom: 40px">
<img src="images/answer_with_sources.png" alt="source button location" width="70%"/>
</div>

### Ask specific, small bits of the larger question
If you don’t know the steps to get to your end goal, ask ChatGPT to outline the steps for you. We go over this in our next workshop.

The more targeted your question, the better the answer. For example:

<div style="margin-left: 5%; margin-top: 20px; margin-bottom: 40px">
<img src="images/time_example.png" alt="chat gets comfused" width="100%"/>
</div>



## Drawbacks directly related to coding
Besides the mistakes LLM can make, there are also data privacy and environemental drawbacks. There are many other potential drawbacks that we don't touch on in this workshop series.

### Data Privacy
The LLM is always learning. How? By using user input. You can tell ChatGPT if it did a good job (thumbs up or thumbs down), but it also collects the information you feed it. This means that you probably shouldn't upload confidential or priviledged information to any LLM. We will learn how to deal with this constraint in the Dummy Data workshop.

### Environemental
<a href="https://www.mdpi.com/2071-1050/14/9/5172" target="_blank">LLMs are very resource-intensive to train and run</a>. Between the materials used to construct the big datacentres, the electricity to keep them running, and the fresh water needed to cool them, that's a lot of resource use! This does not mean that we should not use LLMs and other AIs, but it means we need to use them efficiently and with purpose. 

## Glossary
Here is a link to the <a href="https://ubc-library-rc.github.io/AI_for_coding/content/Glossary.html" target="_blank">full workshop glossary</a>, but we list a few key terms form this page below:
<ol type="1">
  <li><b>Hallucinations</b>: Mistakes made by the LLM. Factually incorrect answers.</li>
  <li><b>Large Language Model (LLM)</b>: A large computer model that outputs text (language) based on past experiences (training data).</li>
  <li><b>Training Data</b>: Data used to make the LLM. This is what ChatGPT crawls the web for.</li>
  <li><b>Testing Data</b>: Data that is used to test the accuracy of the LLM.</li>
</ol>


