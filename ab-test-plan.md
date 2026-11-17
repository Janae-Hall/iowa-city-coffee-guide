# A/B Testing Plan — The Daily Pour

**Original Plan: November 8, 2026, 6:43 PM**  
**Revised: November 17, 2026**

### 1. Page and Element Being Tested

This experiment will test the homepage headline of The Daily Pour, a fictional coffee guide for Iowa City college students.

**Version A:** Find Your Cup. Find Your Corner.

**Version B:** Find Your Perfect Coffee Spot in Iowa City.

Only the headline will change. All other homepage content and design elements will remain identical.

### 2. Hypothesis and Reasoning

I predict Version B will encourage more visitors to explore the coffee guide because it clearly communicates the website's purpose and location. While Version A is more creative and welcoming, Version B may better appeal to students actively searching for coffee shops in Iowa City.

### 3. AI Visitors and Method

I will use GPT-6 with the same settings for 100 independent trials, each in a fresh conversation with memory off. I will randomly assign and shuffle 50 trials per version before testing.

**Revised Exact Prompt:**

"You are a college student in Iowa City looking for a coffee shop to study, relax, or meet friends. Review this fictional coffee guide homepage, paying attention to its headline and overall content. On a scale of 1 to 7, how likely would you be to click the main button to explore coffee shops, where 1 means extremely unlikely and 7 means extremely likely? Answer with a number from 1 to 7, followed by one sentence explaining why. URL PROVIDED"

**Link A:** https://janae-hall.github.io/iowa-city-coffee-guide/

**Link B:** https://janae-hall.github.io/iowa-city-coffee-guide/homepage-b.html

The same prompt will be used for both versions, with only the assigned URL changing.

### 4. Primary Outcome

I will measure visitors' likelihood of clicking the main button using a scale of 1 to 7, where 1 represents extremely unlikely and 7 represents extremely likely.

Each response will receive a numerical score from 1 to 7. Every response and its corresponding score will be recorded in Excel.

### 5. Sample Size and Timeline

I will complete 100 trials (50 per version), launch by November 17, and finish by November 24. I will not stop early based on results.

### 6. Comparison and Expected Results

I will compare the average click-likelihood ratings between Versions A and B and use a two-sample t-test at the 5% significance level.

A higher average rating for Version B will support my prediction, while statistical significance will indicate whether the difference provides stronger evidence. All results will be reported, regardless of the outcome.

### 7. Revision Log — November 17, 2026

After beginning preliminary testing, I noticed that GPT-6 repeatedly answered Yes and focused primarily on the homepage button rather than the headline.

Following professor approval to revise the prompt, I updated the instructions to direct attention toward the headline and overall homepage content.

I also changed the primary outcome from a binary Yes/No response to a 1–7 click-likelihood rating to allow for more variation in responses.

The original preliminary trials will be excluded from the revised experiment, and all 100 trials will be conducted using the updated prompt and measurement scale.

The original hypothesis, homepage versions, randomized assignments, and sample size remain unchanged.
