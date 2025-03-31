# Rebuttal

Reviewer3 Q6:
Furthermore, the ablation studies in the Appendix are questionable. For instance, they ablate the effect of "high-order modeling" by replacing their attention-based blocks with ResNets. I don't see how this is a careful ablation study, why not replace it with regular attention without the proposed modeling trick?
此外，附录中的消融研究也值得商榷。例如，他们用ResNets替换了基于注意力的模块，从而消除了“高阶建模”的效果。我不认为这是一项仔细的消融研究，为什么不使用常规注意力替换它，而不用所提出的建模技巧呢？

| Modules        | PSNR ↑   | SSIM ↑   |
|----------------|----------|----------|
| ResNet         | 17.7953  | 0.5826   |
| Self-attention | —        | —        |   
| Ours           | **18.6708** | **0.6587** |

