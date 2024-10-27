# CTIBENCH Research Validation and Model Fine-Tuning Project

This project aims to analyze and validate the findings of the CTIBENCH research paper. By replicating and extending the study, we test the robustness of the results using both the original CTIBENCH dataset and a custom dataset created using methods described in the paper. The project ultimately involves fine-tuning an open-source large language model (LLM), such as LLaMA 3, and evaluating its performance on both datasets.

## Project Steps

### Step 1: Review and Understand Research Paper (CTIBENCH)
- **Objective**: Carefully read and understand the CTIBENCH research paper.
- **Outcome**: Establish a clear understanding of the research methods, data handling, and analytical processes detailed in the paper.

### Step 2: Retrieve and Validate CTIBENCH Dataset
- **Objective**: Retrieve the CTIBENCH dataset from GitHub, as referenced in the research paper.
- **Task**: Perform statistical tests on the dataset to validate (or not validate) the results presented in the article.
- **Outcome**: Initial validation of the research findings using the original dataset.

### Step 3: Construct Custom Dataset
- **Objective**: Build a custom dataset following the methodology outlined in the CTIBENCH paper.
- **Task**: Adhere to the data collection and preprocessing techniques specified in the article to create a dataset with additional data points while retaining the original structure.
- **Outcome**: A custom dataset that reflects the structure of the CTIBENCH dataset but includes more data for extended analysis.

### Step 4: Validate Custom Dataset
- **Objective**: Re-run the statistical tests from Step 2 on the custom dataset.
- **Outcome**: Comparison of the custom dataset to the CTIBENCH dataset, based on similar statistical validation.

### Step 5: Fine-Tune LLM on CTIBENCH Dataset
- **Objective**: Fine-tune an open-source LLM (such as LLaMA 3) using the CTIBENCH dataset.
- **Task**: Load the CTIBENCH dataset, configure the model, and fine-tune it based on the research data.
- **Outcome**: A domain-specific LLM fine-tuned on the CTIBENCH dataset.

### Step 6: Validate Fine-Tuned Model with Custom Dataset
- **Objective**: Test the performance of the fine-tuned model using the custom dataset.
- **Outcome**: Performance metrics assessing the model’s adaptability and accuracy on a dataset created through alternative data collection.

### Step 7: Fine-Tune LLM on Custom Dataset
- **Objective**: Repeat the fine-tuning process using the custom dataset.
- **Outcome**: A model fine-tuned on the custom dataset, providing insights on the effect of alternative data on model fine-tuning.

### Step 8: Validate Fine-Tuned Model on Original CTIBENCH Dataset
- **Objective**: Test the model fine-tuned on the custom dataset with the original CTIBENCH dataset.
- **Outcome**: Cross-validation performance, indicating how well the model generalizes across both datasets.

## Conclusion
This project’s step-by-step methodology demonstrates the reproducibility of the CTIBENCH research findings and explores the impact of alternative data on model fine-tuning. By performing these steps, we gain insights into model performance, robustness, and the implications of fine-tuning LLMs with diverse datasets.
