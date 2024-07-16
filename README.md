# Self-consistency

Perhaps one of the more advanced techniques out there for prompt engineering is self-consistency. Proposed by Wang et al. (2022), self-consistency aims "to replace the naive greedy decoding used in chain-of-thought prompting". The idea is to sample multiple, diverse reasoning paths through few-shot CoT, and use the generations to select the most consistent answer. This helps to boost the performance of CoT prompting on tasks involving arithmetic and commonsense reasoning.

With self-consistency prompting, the model generates multiple candidate answers to a question. 
These are then compared against each other, and the most consistent or frequent answer is selected 
as the final output. A good example of self-consistency prompting with LLMs is in the context of 
fact verification or information synthesis, where accuracy is paramount.

![image](https://github.com/Jeevan672/Self-consistency/assets/88030873/f897931f-118b-42e9-9d11-8f99fc700877)

Research Paper # https://arxiv.org/pdf/2203.11171

