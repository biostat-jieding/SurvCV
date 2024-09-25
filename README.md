# *survaux* *atransurv* R package
It focuses on enhancing **surv**ival analysis in target domain by transferring **aux**iliary information extracted from source domains. 
- allow for low and high dimensional covariates
- based on the Cox proportional hazards model
- key underlying technique is the control variate
- extension to include a cured fraction

Briefly speaking, this package can implement the following cases:
- **Low-dimensional** Cox proportional hazards model:
  - with **subgroup survival probabilities at multiple time points** as auxiliary information (SP-Low)
- **High-dimensional** Cox proportional hazards model:
  - with **subgroup group survival probabilities at multiple time points** as auxiliary information (SP-High)

Survival data analysis from various perspectives is also of interest: 
- **Estimation**: Estimation of relative risk - prognostic effects for interested risk factors
- **Inference**: Condcut statistical inference

We will add more details in the near future. Thank you for your attention!
