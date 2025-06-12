under construction :)

# Reinforcement Learning 
(1) [Learning to Reason without External Rewards](https://arxiv.org/abs/2505.19590)  
> This paper introduces INTUITOR, a new method developed under the Reinforcement Learning from Internal Feedback (RLIF). It replaces traditional external rewards, such as human feedback or correct answers, by using the model’s own confidence, known as self-certainty, as the only reward signal. INTUITOR measures how confident a model is in its own answers by using a KL divergence-based formulation that favors internally consistent, low-entropy predictions. This approach allows the model to assess the quality of its outputs during training, encouraging detailed and coherent reasoning without needing explicit supervision. Unlike entropy-based methods that may favor shorter or less informative responses, self-certainty avoids such biases and guides the model toward generating answers it can justify internally.


# Whatever category this is
(1) [Why Gradients Rapidly Increase Near the End of Training](https://arxiv.org/abs/2506.02285)
> During long-duration Large Language Model (LLM) training runs the gradient norm increases rapidly near the end of training. In this paper, the authors show that this increase is due to an unintended interaction between weight decay, normalization layers, and the learning rate schedule. They also propose a simple correction that fixes this behavior while also resulting in lower loss values throughout training.
