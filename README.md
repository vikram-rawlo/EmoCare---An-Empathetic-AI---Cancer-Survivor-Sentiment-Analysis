# EmoCare---An-Empathetic-AI---Cancer-Survivor-Sentiment-Analysis
EmoCare, is centered around developing and understanding empathetic AI. The primary focus is on fine-tuning NLP model for sentiment analysis, particularly for the emotions of cancer survivors and their caregivers.

**Empathetic AI**: Suggests that the AI system being discussed or developed is designed to understand and respond to human emotions, providing a more compassionate and human-like interaction.

**Sentiment Analysis:** Refers to the task of determining the sentiment or emotional tone expressed in a piece of text. In this case, the sentiment analysis is focused on understanding the emotions of cancer survivors and their caregivers.

# Dataset
**Title:** Mental Health Insights: Vulnerable Cancer Survivors & Caregivers Data
Link to the dataset: https://data.mendeley.com/datasets/69dcnv2gzd/1

**Contributors:**
- Irin Hoque Orchi
- Nafisa Tabassum
- Jaeemul Hossain
- Sabrina Tajrin
- Iftekhar Alam

**Description:**
The dataset is named "Mental Health Insights: Vulnerable Cancer Survivors & Caregivers Data" and was published on November 21, 2023. It provides valuable insights into the mental health aspects of cancer patients and their caregivers. The dataset was collected from various platforms such as Reddit, Daily Strength, and the Health Board, comprising a total of over 10,087 posts. The posts are related to five types of cancer: brain, colon, liver, leukemia, and lung cancer.
The dataset was analyzed by two team members who scored each post based on the emotions expressed, utilizing a scale from -2 to 1. The scoring system is designed to capture a spectrum of emotions. Negative scores (-1 or -2) were assigned to posts expressing grief or suffering, positive scores (1) were given for posts with happy emotions like relief or accomplishment, and posts with no discernible emotion received a score of 0, categorizing them as neutral.
The primary objective of this analysis is to understand the emotional aspects conveyed in the posts of cancer patients, contributing to a mental health study. The dataset is provided in CSV format and can be downloaded for further research and analysis.

**Categories:**
- Natural Language Processing

The dataset is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). Users are encouraged to learn more about the license for proper usage.
The provided information about the dataset doesn't explicitly specify the features, but based on the context, it seems like there are three main features:
1. **Posts:**
   - This feature represents the textual content of the posts made by cancer patients and their caregivers.
   - Each entry in this feature contains the actual text of the posts where individuals share their experiences, emotions, or information related to cancer.
2. **Predicted:**
   - This feature likely contains the predicted sentiment or emotion labels assigned to each post.
   - The predictions could be based on a model or human annotators who have assessed the emotional tone or sentiment expressed in the posts.
   - Possible values might include categories such as 'positive', 'neutral', 'negative', or others that reflect the emotional state of the individuals in the posts.
3. **Intensity:**
   - This feature seems to represent the intensity or strength of the predicted sentiment or emotion in each post.
   - It could be a numerical value indicating the degree of positivity, neutrality, or negativity in the posts.
   - Higher intensity values might suggest stronger emotions or sentiments expressed in the corresponding posts.

## Methodology:

**Algorithm Selection**: The project utilizes straightforward algorithms including XGBoost, Random Forest, and MLP (Multi-Layer Perceptron). These were chosen for their simplicity and effectiveness in handling NLP tasks, especially given the initial complexity typically associated with more advanced models like LSTMs or transformers.

**Performance**: The model achieved around 72% accuracy on the test set, demonstrating its capability to discern sentiment across a range of reviews.

**Objective**: By categorizing sentiments expressed in these reviews, the project aims to provide insights that could potentially aid in understanding the emotional well-being and needs of cancer patients and their caregivers.

**Accessibility**: The model and associated code are open-source and available on GitHub, allowing for transparency, collaboration, and further development within the community interested in healthcare-focused NLP applications.

# Future Directions:

Future iterations of the project may explore more sophisticated NLP models to improve accuracy and nuance in sentiment analysis. Additionally, expanding the dataset and incorporating domain-specific knowledge could further enhance the model's effectiveness and relevance.


## Installation

Clone Repository
```
git clone https://github.com/vikram-rawlo/EmoCare---An-Empathetic-AI---Cancer-Survivor-Sentiment-Analysis.git

```
Install Requirements
```
pip install -r requirements.txt
```
