# *survaux* R package
It focuses on enhancing **surv**ival analysis in target domains by transferring **aux**iliary information extracted from external source domains. 
- allow for low and high dimensional covariates
- based on the Cox proportional hazards model
- key underlying technique is the control variate
- extension to include a cured fraction
- Here are some papers that can help you understand the underlying method:
  - Ding, J., Li, J., & Wang, X. (2024). **Efficient auxiliary information synthesis for cure rate model**. *Journal of the Royal Statistical Society Series C: Applied Statistics*, 73(2), 497-521.
  - Ding, J., Li, J., Zhang, M., & Wang, X. (2024). **CureAuxSP: An R package for estimating mixture cure models with auxiliary survival probabilities**. *Computer Methods and Programs in Biomedicine*, 251, 108212. 


## Package description

Briefly speaking, this package can implement the following cases:
- **Low-dimensional** Cox proportional hazards model:
  - with **subgroup survival probabilities at multiple time points** as auxiliary information (SP-Low)
- **High-dimensional** Cox proportional hazards model:
  - with **subgroup group survival probabilities at multiple time points** as auxiliary information (SP-High)

Survival data analysis from various perspectives is also of interest: 
- **Estimation**: Estimation of relative risk - prognostic effects for interested risk factors
- **Inference**: Condcut statistical inference

We will add more details in the near future. Thank you for your attention!
