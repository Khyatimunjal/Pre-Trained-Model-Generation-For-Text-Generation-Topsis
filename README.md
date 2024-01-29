# **Pre-Trained-Model-Generation-For-Text-Generation-Topsis**

Overview
Text generation stands as an AI-driven process, crafting written content with an adept mimicry of human language patterns and styles. This endeavor revolves around the art of conjuring coherent and meaningful text that mirrors the nuances of natural human communication. The focal point of this undertaking is to scrutinize and contrast the efficacy of diverse text summarization models, empowering users to discern and opt for the model that aligns seamlessly with their distinct requirements.

Approach - TOPSIS Technique:
The selection of the Technique for Order of Preference by Similarity to Ideal Solution (TOPSIS) amplifies the depth of this comparison. This method elegantly balances the quest for similarity to the ideal solution and the divergence from the negative ideal solution, culminating in a nuanced and holistic ranking.

Models Under Scrutiny:
The evaluation canvas includes real-world pretrained models like T5-base, GPT-2, BLOOM, Bart Large, and Jurassic-1 Jumbo. These models have established prominence in various text generation tasks, constituting a robust cohort for this comprehensive comparison.

Project Structure:
data.csv: CA repository of evaluation metrics corresponding to each model.
result.csv: A formatted CSV document housing the ranked outcomes.
graph.py: A python file encapsulating the data used in creating the bar chart.
barchart.png: A bar chart delineating the performance metrics, rendering the comparison.

Results and Analysis:
1. Ranking Table:
For an in-depth exploration of ranked results, peruse the table_result.csv:

| Model            | Model_size_GB | Inference_Time_ms | BLEU_Score | Fact_Checking_Score_(0-100) | TOPSIS_Score | Rank |
| ---------------- | ------------- | ----------------- | ---------- | --------------------------- | ------------ | ---- |
| T5-base          | 0.7           | 1.5               | 37.4       | 85                          | 0.920279     | 1    |
| GPT-2            | 1.5           | 0.8               | 35.8       | 75                          | 0.458519     | 2    |
| BLOOM            | 3.9           | 2.1               | 42.1       | 82                          | 0.149159     | 4    |
| Bart Large       | 3             | 2.5               | 40.3       | 83                          | 0.202173     | 3    |
| Jurassic-1 Jumbo | 18.6          | 3.8               | 44.2       | 88                          | 0.006171     | 5    |

3. Bar Chart:
Dive into the visual representation of model performance through the insightful bar chart. This graphical marvel encapsulates the essence of each model's prowess, making the comparative analysis both accessible and enlightening.
![BarChart](https://github.com/Khyatimunjal/Pre-Trained-Model-Generation-For-Text-Generation-Topsis/assets/98097634/ec638386-d51a-4e91-975d-30430ed14521)
