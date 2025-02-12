# EntityFraming-Llama3-8b-Instruct
Fine-tuning process for the multi-class multi-label classification task on entities mentioned within news articles. This research was conducted for the SemEval 2025 campaign, specifically for Task 10: Multilingual Characterization and Extraction of Narratives from Online News. Specifically, the proposed entity framing task is as follows: given an article and a list of entities mentioned within it, assign each individual one or more roles, based on a predefined taxonomy. The task is considered as a textual classification problem at the level of specific span sentence fragments, and is both multi-class, due to the numerous possible entities defined, and multi-label, since more than one entity may be associated to each single instance.
For the realisation of the fine-tuning process, the basic scheme proposed within this article was used: https://www.datacamp.com/tutorial/fine-tuning-llama-3-1

## Descrizione dei file
- Pre-processing: 
- FineTuningLlama38b:
- DataAugmentation:
- ConfusionMatrix:

  
## License
This project is licensed under the MIT License
