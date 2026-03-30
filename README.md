# ICML Rebuttal Figures

## Figure 1: Comparison of training performance among LLaMA2-7B, LLaMA2-7B with QKNorm, LLaMA2-7B with SandwichNorm, and SimpleGPT-7B.
![Sandwich](images/Llama2-7B_20K_compareSandwich_smooth.png)

## Figure 2: Ablation study of SimpleNorm. The blue curve corresponds to the model with SimpleNorm applied only to the FFN, the red curve corresponds to the model with SimpleNorm applied only to self-attention, and the black curve corresponds to SimpleGPT-7B.
![Ablation](images/Llama2-7B_lr1e-3_wd0.05_20K_ablation_smooth.png)

## Figure 3: Distribution statistics of the RMSNorm gain parameter $\gamma$ for LLaMA2-7B, LLaMA2-7B with QKNorm, and SimpleGPT-7B.
![RMSNorm](images/rmsnorm_gamma_7b_compare.png)
