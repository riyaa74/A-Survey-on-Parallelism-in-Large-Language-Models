# A Survey on Parallelism in Large Language Models

The aim of the literature survey is to go through the myriad techniques that are used during the training and the inference of large language models (LLM). We aim to find the similarities and differences between these methods whiletraining LLMs. Some of the parallelism techniques that wehave come across so far [2] are listed below:

• Data Parallelism

• Tensor Parallelism

• Pipeline Parallelism

• 3D Parallelism

• Sequence Parallelism

We further aim to analyze the difference between parallelism techniques used during the training and the inference of large language models, if there are any. If there are differences between training and inference, we would like to look at why there is a divergence in parallelism between these two stages of a Large language Model (LLM). We would also like to look at the different parallelism techniques that are used in some of the more popular large language models, and why these techniques were used in the design of the LLMs, i.e. is there an inherent link between the design of a large language model and how such design designs can impact the parallelization during training and inference of these LLMs. This also answers the question of whether these techniques are model dependent or model independent.
