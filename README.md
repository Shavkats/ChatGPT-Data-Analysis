# 📊 ChatGPT Conversation Analysis

An exploratory data analysis project based on **52,000+ ChatGPT conversations**, designed to uncover patterns in user prompts and generated responses.

This project investigates how people interact with ChatGPT, what types of prompts are most common, and how prompt characteristics influence response quality, readability, and verbosity.

---

## 🎯 Project Objectives

The analysis focuses on five key areas:

### 1. Most Common Words Used in ChatGPT Prompts

Discover the words that appear most frequently in user prompts to better understand user intent and communication patterns.

The goals is to generate word cloud using the WordCloud package and visualize it as an image using the Matplotlib library.

---

### 2. Classification of ChatGPT Prompt Types

Prompts are categorized into major intent groups such as:

* Questions
* Content Generation
* Explanation
* Problem Solving
* Listing Tasks
* Advice
* Editing/Rewriting
* Classification
* Other

The goal is to understand how users leverage ChatGPT across different categories.

---

### 3. Readability Levels of ChatGPT Responses

Response readability is evaluated using the Stats library that calculates statistics from text.

The goals to measures the readability and comprehension difficulty of responses and categorize them into six levels from very easy to extremely difficult.

---

### 4. Prompt Length vs. Readability

Analyze the relationship between:

* Prompt length
* Readability scores

The goal is to find out how length of prompts can affect the readability of responses.

---

### 5. The verbosity of ChatGPT responses

Analyze response verbosity through:

* Average words per sentence
* Sentence length distribution
* Response length patterns
* Variation across prompt categories

This helps quantify how concise or detailed ChatGPT responses tend to be.

---

### 6. Effect of Extra Context on Responses

Measure how additional context influences:

* Response quality
* Response detail
* Readability
* Overall usefulness

---

## 📈 Analysis Outputs

The project includes visualizations and statistical analyses such as:

* Word frequency distributions
* Prompt type distributions
* Readability score comparisons
* Correlation analysis
* Histograms and density plots
* Boxplots and scatter plots
* Response length distributions

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* NumPy
* NLTK
* TextStat

---

## 🔍 Key Questions

1. What words are most frequently used in ChatGPT prompts?
2. What are the dominant prompt categories?
3. How readable are ChatGPT responses?
4. Does prompt length affect response readability?
5. Does additional context improve response quality?
6. How verbose are ChatGPT responses?
7. Are there observable patterns between prompt structure and generated output?
