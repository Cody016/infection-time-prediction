# infection-time-prediction

Fleming and Harrington (1991) present the results of a randomized clinical trial of the effects of gamma interferon versus placebo on the incidence of serious infections among children with chronic granulotomous disease (CGD). For each subject the number of infections experienced and the total duration of follow-up are presented . . . the data set includes the patient id, number of severe infections experienced (nevents), the number of days of follow-up (futime) and the following covariates:

* z1: treatment group: interferon (1) versus placebo (2);
* z2: Inheritance pattern: X-linked (1) versus autosomal recessive (2);
* z3: Age (years);
* z4: Height (cm);
* z5: Weight (kg);
* z6: Corticosteroid use on entry: yes (1) versus no (2);
* z7: Antibiotic use on entry: yes (1) versus no (2);
* z8: Gender: male (1) versus female (2); and
* z9: Type of hospital: NIH (1), other US (2), Amsterdam (3), other European (4).

Use these data to conduct the following analyses.

(a) Assume the infection counts follow a time homogeneous Poisson process. Fit the main
effects Poisson GLM to the data. Be sure to declare covariates as factors, where necessary, and use an appropriate offset term. Print the R summary object for your fitted model.

(b) Conduct a residual analysis of the model from part (a). Include at least one scatterplot
and one quantile-quantile plot. Investigate and explain any patterns you see in these plots. Are you satisfied with the fit of the model?
Regardless of your conclusion in (b), use the model from (a) to answer the following parts.

(c) Is treatment with interferon effective in reducing serious infections among children with
CGD? Justify your response with an appropriate estimate, its precise interpretation, and 95% confidence interval.

(d) Estimate the relative rate of serious infections for children treated at a hospital in Amsterdam versus those treated at other European hospitals. Include a 95% confidence interval with your estimate.

(e) Estimate the number of infections that a 12 year old male child, 142 cm tall, 34 kg in weight, with X-linked inheritance who was on corticosteroids but not antibiotics at entry, and was randomized the the treatment group at a non-NIH US hospital would expect to experience over one year.

(f) Write one paragraph summarizing the results and highlighting the important associations
identified by this log linear model.
