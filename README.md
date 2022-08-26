# AB_Testing_Library_Website


This exploration project is to carryout A/B testing on real data. The project worked with part of the [data](https://scholarworks.montana.edu/xmlui/handle/1/3507) from ["Improving Library User Experience with A/B Testing: Principles and Process"](https://quod.lib.umich.edu/w/weave/12535642.0001.101?view=text;rgn=main) by Young (2014). This paper presents a case study where A/B testing is applied with different webpage designs. The primary aim is to compare user interactions to determine which one statistically improves the navigation experience by increasing the homepage CTR.


The project followed the six steps of hypothesis testing:
1. Define your null and alternative hypotheses.
2. Compute the **observed** test statistic $\delta^*$ coming from your original sample.
3. Use the null model to generate $r$ **random permuted** samples from the original sample and calculate their corresponding $r$ test statistics.
4. Generate the null distribution using these $r$ test statistics.
5. Check where your **observed** test statistic $\delta^*$ falls on this distribution.
6. If $\delta^*$ is near the extremes past some threshold defined with a significance level $\alpha$, we reject the null hypothesis. Otherwise, we fail to reject the null hypothesis.
