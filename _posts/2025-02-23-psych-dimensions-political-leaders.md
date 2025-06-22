---
layout: post
title: "Psychological assessments as a form of checks and balances"
date: 2025-02-23
tags: [political-science, international-relations, psychology, leadership]
---

*They're performed for high-responsibility civilian and military roles - why not for heads of state?*

## A starting point for assessment

Psychological assessments are routinely used in high-responsibility, high-stress civilian and military contexts such as aviation, nuclear safety, and national security to safeguard against harmful decision-making. This analysis explores the feasibility of using publicly available tools to develop psychological assessments of political leaders.
The motivation is that such assessments can offer valuable insight into the likelihood of violence or harmful governance. 

A gap in high quality information exists for a few reasons:
- Existing assessments are often speculative accounts by political pundits
- People who may be most suitable to offer informed opinions, such as psychiatrists or other mental health professionals, are prohibited or discouraged from doing so
- Evaluating vast amounts of data, including speeches, articles, historical accounts, and other media, requires both data processing and analysis that was challenging until recent years

To overcome these barriers, this analysis uses ChatGPT as an exploratory, low-barrier starting point. Limitations and how to address them - such as more transparent methods of text analysis - are discussed in the final section.

Briefly, the steps are:

1. Develop a list of potential psychological characteristics and how to rate them
2. Come up with a list of historical figures
3. Use Chat or another LLM to assess available information about each individual prior to office

### 1. Psychological characteristics

A list of psychological characteristics was developed based on a literature review of available psychological assessments, including from fields like political psychology (e.g. Margaret Hermann) as well as public CIA analyses of world leaders (e.g. work by Jerrold Post and colleagues.) The final list for this analysis is meant to cast a fairly wide net and includes DSM-5 diagnose and features, and other factors established to predispose or correlate with destructive leadership.

**List of psychological characteristics:**

1. Pathological narcissism (grandiosity, excessive need for admiration, inability to tolerate criticism)
2. Paranoia
3. Machiavellianism
4. Sadism
5. History of violence/aggression
6. Drive for dominance
7. Authoritarianism
8. Aversion/hatred (intolerance, out-group hostility, us vs. them struggle, polarized thinking)
9. Grievances
10. Greed/craving (for material, e.g. wealth, natural resources, territorial expansion or intangible, e.g. status)
11. Nostalgia
12. Cognitive rigidity
13. Low empathy
14. Impulsivity

Each characteristic is rated from 1 to 5. A higher total score indicates higher risk.

### 2. Historical figures and modern leaders

The list of 40 global leaders below was chosen to include all US presidents since World War II and select historical and modern leaders. While it has representation from different geographic regions, in its current form, the list is skewed toward the west and toward a more recent time period.

**List of global leaders:**

- Bashar al-Assad
- Jacinda Ardern
- Joe Biden
- George H. W. Bush
- George W. Bush
- Jimmy Carter
- Bill Clinton
- The Dalai Lama (14th)
- Dwight D. Eisenhower
- Recep Tayyip Erdoğan
- Gerald Ford
- Adolf Hitler
- Lyndon B. Johnson
- John F. Kennedy
- Paul Kagame
- Sanna Marin
- Javier Milei
- Narendra Modi
- Giorgia Meloni
- Angela Merkel
- Nelson Mandela
- Benjamin Netanyahu
- Richard Nixon
- Viktor Orban
- Barack Obama
- Vladimir Putin
- Cyril Ramaphosa
- Ronald Reagan
- Idi Amin
- Ellen Johnson Sirleaf
- Joseph Stalin
- Aung San Suu Kyi
- Margaret Thatcher
- Donald Trump
- Harry S. Truman
- Saddam Hussein
- Emmanuel Macron
- Justin Trudeau
- Xi Jinping
- Volodymyr Zelenskyy

### 3. AI tools for text analysis

An example prompt can look like the following:

> I am conducting an exploratory analysis to assess whether psychological profiles of world leaders—constructed based on publicly available information about them before they assumed power—can predict their likelihood of initiating conflict later. Please do the following:
>
> - Compile a list of global leaders that includes the following: [insert list of global leaders here.]
> - Create a table where: each row is a world leader, and each column represents a score for each psychological trait. The list of psychological characteristics must include: [insert list of psychological characteristics here.] Rely on the best available validated definitions of those traits, where possible.
> - Scoring: To create a score, rate each psychological trait on a scale of 1-5 or N/A, based on what was known about the individual *prior to assuming power.*
> - Rank the table from highest to lowest, based on total score (sum), and include brief notes about the individuals' subsequent actions regarding initiation of conflict after assuming power.

The results below were generated using ChatGPT in February 2025.

## Results

<iframe title="Pre-Power Psychological Profiles of Global Leaders: Historical Figures, US Presidents, and Current World Leaders" aria-label="Table" id="datawrapper-chart-6SNwZ" src="https://datawrapper.dwcdn.net/6SNwZ/3/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="1260" data-external="1"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"]){var e=document.querySelectorAll("iframe");for(var t in a.data["datawrapper-height"])for(var r,i=0;r=e[i];i++)if(r.contentWindow===a.source){var d=a.data["datawrapper-height"][t]+"px";r.style.height=d}}}))}();
</script>


The results reveal moderate-high relationship between pre-power psychological traits and later conflict initiation, albeit with limitations.

- **Adolph Hitler, Joseph Stalin, and Idi Amin** all rank at the top and demonstrated pre-power tendencies toward paranoia, dominance, and hostility toward opposition. This translated into highly repressive regimes.

- **A number of leaders** on the list have been elected, assumed power under a system with institutional checks and balances, then proceeded to successfully erode them. Hitler's dismantling of the Weimar Republic is one notable example. More recently, a pattern of erosion of institutional safeguards and a rise in authoritarianism has been experienced in Turkey under Erdoğan, Hungary under Orban, and the US under Trump. Erosion of safeguards is noteworthy because unchecked leaders are more likely to initiate conflict and be relatively more isolated from the negative consequences.

- **Leaders with the lowest scores** include US presidents Joe Biden, Jimmy Carter, and Barack Obama, and global leaders including South Africa's Nelson Mandela, Volodymyr Zelenskyy of Ukraine, Finland's Sanna Marin, and the 14th Dalai Lama of Tibet.

- **False negatives** such as Bashar al-Assad, who did not score very highly but went on to commit devastating violence in Syria - suggest limitations in the model's usefulness to predict behavior once in power.

## Limitations

#### Replication
- LLM generated results are opaque, in that it's unclear how AI tools define and rate psychological traits, even when some instruction is provided. Additionally, LLMs get updated and retraied over time. This affects stability and replication of results. 
- Conflict definition: results may not distinguish between initiating unprovoked conflict vs. what some view as motivated by defensive/security concerns.

#### Availability of information
- There is variation in available information. Older records may be limited to journalistic accounts and speeches, while recent information can draw on a wealth of online information and analysis.
- Available information is limited to observable behavior, including a person's history, their professional activities, and public statements. It is not a clinical diagnosis.

#### Prediction
- If the purpose of a psychological assessment is not just to evaluate, but also to act on the information by screening out potential harm - then false negatives (e.g. Assad) remain problematic.
- The list of psychological traits is a bucket of items with some empirical basis, but this is something that would need iterative refinement and testing of predictive value.

#### Ethical concerns
- Psychological assessments may be weaponized to screen out individuals or groups who are viewed unfavorably. This is a real concern, which is why mechanisms of oversight must be developed if this is to be deployed ethically.
- Even well-designed and validated models may still result in false positives some proportion of the time.  
- The [2017 debate about the Goldwater Rule](https://www.npr.org/2017/05/15/528502969/psychiatrists-divided-over-the-goldwater-rule-in-the-age-of-trump), though limited to psychiatry, exposed divisions about the longstanding practice of discouraging professionals from attempting to diagnose or make statements about the mental fitness of presidential candidates.

## Next steps

What to make of these limitations? Many can be overcome with a more systematic approach, including the development and validation of definitions, inclusion of more comprehensive list of world leaders, and adjusting for factors like governance system and time period. **Computational social science advancements**, including analysis of vast amounts of text, social media, and other online content - can be used for things like sentiment analysis and emotion detection, in order to [assess](https://direct.mit.edu/coli/article/50/1/237/118498/) relevant characteristics.

Once a more rigorous, validated assessment is developed with reasonably high accuracy - what do we do with this information?

- One option is to look to existing precedents where psychological evaluations are already used in civilian and military roles. This usually involves some action and enforcement, given the associated risks (e.g. defense and national security, operating critical infrastructure or nuclear... anything.)
- At the minimum, it can be used as an early warning mechanism.

While this post focuses on the use of public information about candidates, some like Dr. Bandy Lee and colleages [cite risks to democracy](https://www.scientificamerican.com/article/the-shared-psychosis-of-donald-trump-and-his-loyalists/) and call for formal mental health assessments.
