# AI Research Projects

A collection of exploratory research projects investigating artificial intelligence through experimental design, data collection, statistical analysis, and qualitative evaluation.

The projects explore a range of AI systems and topics, including early conversational AI, game-playing systems, information retrieval, and large language models.

## Projects

### 1. Early Conversational AI: An Experimental Study of ELIZA and Jabberwacky

**Research Question:**
How do ELIZA and Jabberwacky differ in conversational stability, response behavior, and termination patterns when interacting under standardized conditions?

**Overview:**
This study examines chatbot-to-chatbot interactions between ELIZA and Jabberwacky, two early conversational AI systems. Five controlled conversation trials were conducted using standardized starting conditions, turn-based exchanges, and predefined termination criteria. Conversation length and termination reasons were analyzed using descriptive statistics and confidence intervals, while the conversation transcripts were examined for qualitative differences in response behavior.

**Key Findings:**

* All five trials exceeded the minimum threshold of 10 exchanges.
* Conversation length ranged from 14 to 60 exchanges, with a mean of 42.6 exchanges.
* 40% of trials reached the maximum exchange limit, while another 40% ended due to unrelated or generic responses.
* ELIZA exhibited more repetitive and constrained response patterns, while Jabberwacky produced more varied and unpredictable responses.
* The results demonstrate that longer chatbot interactions do not necessarily indicate conversational coherence or stability.

**Methods & Tools:**

* Experimental design
* Controlled AI evaluation
* Data collection
* Descriptive statistics
* Confidence intervals
* Qualitative analysis

---

### 2. Connect 4 Against AI: The Effect of Human Strategy on Gameplay

**Research Question:**
How does a human player's strategy influence game outcomes and game length when competing against an AI opponent in Connect 4?

**Overview:**
This study examines whether different human gameplay strategies affect outcomes when playing Connect 4 against an AI opponent. Forty games were conducted under standardized conditions, comparing a normal strategy that balanced offensive and defensive moves with a defensive strategy focused on blocking the opponent. Game outcomes and the number of human moves were analyzed using Fisher's exact test and one-way ANOVA.

**Key Findings:**

* The human player won 5 of 38 non-draw games, while the AI won the majority of games.
* Fisher's exact test found no statistically significant association between gameplay strategy and game outcome ($p = 1.00$).
* Defensive gameplay resulted in longer games on average, with 15.95 human moves compared with 13.00 under the normal strategy.
* One-way ANOVA found a statistically significant difference in the number of human moves between strategies ($p = 0.0252$).
* The findings suggest that defensive strategy influenced game duration but did not significantly improve the likelihood of winning.

**Methods & Tools:**

* Experimental design
* Data collection
* R
* Statistical analysis
* Fisher's exact test
* One-way ANOVA
* Data visualization

---

### 3. Multilingual LLM Evaluation: Idiom Interpretation and Translation

**Research Question:**
How does LLM performance in interpreting and translating idioms differ across languages and across different large language models?

**Overview:**
This study evaluates four large language models—ChatGPT, Gemini, Claude, and DuckAI:GPT5—on their ability to interpret three common English idioms across English, Arabic, and Chinese. Responses were evaluated by Microsoft Copilot and Meta AI using separate 1–5 scores for translation/meaning accuracy and idiom-origin accuracy. Overall scores were analyzed using one-way ANOVA to examine differences across languages and LLMs.

**Key Findings:**

* 72 scored observations were collected across four LLMs, three idioms, three languages, and two LLM-based evaluators.
* No statistically significant difference in overall scores was detected across English, Arabic, and Chinese ($p = 0.94$).
* No statistically significant difference in overall scores was detected among the four LLMs tested ($p = 0.114$).
* Overall scores were generally high, although origin scores showed more variation than translation scores.
* The results suggest that substantial differences in evaluated performance were not detected within the specific conditions of this experiment.

**Methods & Tools:**

* LLM evaluation
* Multilingual data collection
* Experimental design
* R
* Tidyverse
* Data visualization
* One-way ANOVA
* Statistical hypothesis testing
* Comparative model evaluation


---

### 4. LLM Perception and Storytelling

*Coming soon.*

## Research Themes

Across the projects, the research explores:

* Conversational AI
* Artificial intelligence and human interaction
* Expert systems
* Information retrieval
* Large language models
* Experimental design
* Statistical analysis
* Qualitative evaluation of AI behavior

## Tools & Methods

* R
* RStudio
* Quarto
* Statistical analysis
* Data visualization
* Experimental design
* Data collection
* Qualitative analysis
* AI system evaluation

## About

These projects were originally developed as a series of short research investigations in an artificial intelligence course. They are presented here as a collection of independent explorations into the behavior, capabilities, and limitations of AI systems.
