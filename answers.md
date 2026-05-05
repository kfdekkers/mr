## 1. What is the causal question, and is MR appropriate?

The causal question is: **does age at natural menopause affect lung function and risk of airflow obstruction?** The main comparison is early menopause versus normal menopause, and late menopause versus normal menopause.

MR is appropriate because observational studies suggested that early menopause is associated with lower FEV1/FVC and lower FVC, but this could be confounded by lifestyle, early-life factors, socioeconomic factors, smoking, BMI, or other reproductive factors. Davies et al. explain that MR is useful when observational associations may be confounded or affected by reverse causation. 

In this paper, the authors use genetic variants associated with age at menopause as instruments to test whether the association with lung function is likely to be causal. 

---

## 2. Do the genetic instruments satisfy the relevance assumption?

Mostly yes. The relevance assumption means the SNPs must be associated with the exposure, here **age at menopause**.

The authors selected SNPs from published GWASs at genome-wide significance, then removed weak instruments with F-statistic ≤10 and removed highly correlated SNPs. They ended with **63 SNPs**, explaining about **6% of the variance** in age at menopause. 

That is a fairly strong instrument set for a complex trait. Davies et al. say that F-statistics above 10 are commonly used as evidence against serious weak instrument bias. 

**Simple conclusion:** relevance is one of the better-supported assumptions in this study.

---

## 3. Is the independence assumption likely to hold?

The independence assumption means the genetic variants should not be associated with confounders of menopause age and lung function.

The authors tried to reduce this problem by studying naturally post-menopausal **white women from UK Biobank** and adjusting genetic associations for ancestry principal components, centre, and genotyping batch.  

This is important because Davies et al. specifically warn that population stratification can confound genetic associations, and that adjusting for genetic principal components can help. 

However, the assumption cannot be proven. Some SNPs were associated with traits like height, BMI, and age at menarche, which could also relate to lung function. The authors therefore tested sensitivity analyses excluding those SNPs. 

**Simple conclusion:** the authors address independence reasonably well, but it remains partly uncertain.

---

## 4. How do the authors assess and address pleiotropy?

Pleiotropy is probably the main concern. In Davies et al.’s terms, **horizontal pleiotropy** would occur if menopause-related SNPs affected lung function through another pathway, not through menopause age. 

van der Plaat et al. used several approaches:

They tested heterogeneity using I² and Q tests. They also used MR methods more robust to pleiotropy: IVW random effects, weighted median, MR-Egger, and MR-PRESSO. They additionally removed SNPs associated with height, BMI, and age at menarche. 

There was some evidence of pleiotropy, especially for continuous lung function outcomes, but the key finding for airflow obstruction was fairly consistent across methods. 

**Simple conclusion:** pleiotropy is present or at least possible, but the main airflow obstruction result seems reasonably robust.

---

## 5. How should we interpret the effect estimates?

The main MR result suggests that **early menopause is associated with a lower risk of airflow obstruction**. Specifically, early menopause was associated with higher FEV1/FVC and about **15% lower risk of airflow obstruction** compared with normal menopause. 

But this should not be interpreted as saying “early menopause is good” or that anyone should try to induce early menopause. Davies et al. emphasize that MR estimates often reflect **lifelong differences** in an exposure, not the effect of a short-term clinical intervention. 

Here, early menopause may be acting as a proxy for **shorter lifetime exposure to female sex hormones**. The authors themselves discuss this interpretation. 

**Simple conclusion:** this is evidence about possible biology, not a clinical recommendation.

---

## 6. Using the Davies checklist, which assumptions are well supported and which remain uncertain?

Using Davies et al.’s checklist:

**Well supported:**
The relevance assumption is fairly strong: SNPs were genome-wide significant, weak SNPs were removed, and the final SNP set explained 6% of variance in age at menopause. 

**Partly supported:**
The independence assumption is addressed by ancestry restriction and adjustment for principal components, but cannot be fully proven. 

**Most uncertain:**
The exclusion restriction is the main concern because there is evidence of pleiotropy. However, the authors use several sensitivity analyses, and the airflow obstruction result is consistent across methods. 

**Simple conclusion:** this is a reasonably well-conducted MR study, but not assumption-free.

---

## 7. What would be a useful negative control?

A useful negative control would be an outcome that should not plausibly be affected by age at menopause or lifetime sex hormone exposure. If the menopause SNPs were also associated with that outcome, it would suggest confounding or pleiotropy.

Another possibility would be a subgroup or context where the biological pathway should be weaker. The paper does not use formal negative controls, but the subgroup analyses by MHT use and BMI act a bit like biological plausibility checks: if hormones matter, the effect might differ in women with higher hormone exposure after menopause. That is what they found. 

**Simple conclusion:** no formal negative control is used, but subgroup analyses partly test whether the proposed hormone mechanism makes sense.

---

## 8. Could weak instrument bias or sample overlap affect results?

Weak instrument bias is probably not a major problem because the authors removed SNPs with F-statistic ≤10, and the instruments explained 6% of the variance. 

The main analysis is a **one-sample MR** using UK Biobank, because SNP-exposure and SNP-outcome associations are estimated in the same dataset. In one-sample MR, weak instrument bias can move results toward the observational association. Davies et al. explain this distinction between one-sample and two-sample MR. 

The authors also did a sensitivity analysis using external GX estimates from Day et al. and UK Biobank GY estimates, which is closer to a two-sample MR check. Results were consistent. 

**Simple conclusion:** weak instrument bias is addressed, and the two-sample-style sensitivity analysis is reassuring.

---

## 9. How do the MR results compare with the observational findings?

They differ substantially.

The observational analysis found that early menopause was associated with **lower FEV1, lower FVC, and higher risk of spirometric restriction**. 

The MR analysis did **not** find strong evidence for an effect on FVC or spirometric restriction. Instead, it found that early menopause was associated with **higher FEV1/FVC and lower risk of airflow obstruction**. 

This is exactly the type of comparison Davies et al. encourage: MR results should be interpreted alongside observational evidence, and disagreement may suggest confounding, pleiotropy, or that the two methods estimate different things. 

**Simple conclusion:** the observational and MR analyses point to different respiratory patterns.

---

## 10. If MR and observational results differ, how should we interpret this discrepancy?

The discrepancy does not automatically mean the MR result is “true” and the observational result is “wrong.” But it does suggest that the observational association may be confounded.

The authors argue that factors increasing the chance of early menopause may also reduce lung function, such as early-life factors, diet, occupational exposures, or other unmeasured confounders. This could explain why early menopause looked harmful for FVC in observational analyses but not in MR. 

Another possibility is that MR is estimating the effect of lifelong biological differences related to reproductive ageing, while observational analysis reflects measured menopause timing plus many social, behavioural, and health-related factors.

**Simple conclusion:** the difference is the main teaching point. It shows why MR can be useful, but also why MR must be interpreted carefully.
