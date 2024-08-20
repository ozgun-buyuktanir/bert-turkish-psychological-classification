## NLP Model for Preliminary Psychological Diagnosis Using BERTurk

We finetuned [BERTurk](https://huggingface.co/dbmdz/bert-base-turkish-cased) NLP model to make preliminary psychological diagnoses. The model's purpose is to classify individuals who describe their problems in a few sentences into 16 different labels and then direct them to practitioners specialized in the relevant field for treatment.

The model was trained on a dataset of 1,444 samples, comprising:

- **49%** synthetic data
- **15%** translated [NLP Mental Health Conversations](https://www.kaggle.com/datasets/thedevastator/nlp-mental-health-conversations)
- **23%** unique user-generated data
- **13%** custom data created by us

## Labels


- **0** - Suicidal Thoughts
- **1** - Eating Disorders
- **2** - Sleep Disorders
- **3** - Sexual Disorders
- **4** - Addictions
- **5** - Anger Control Disorders
- **6** - Borderline
- **7** - Psychosomatic Disorders
- **8** - OCD (Obsessive-Compulsive Disorder)
- **9** - Behavioral Disorders in Children
- **10** - Depression and Related Disorders
- **11** - Family and Relationship Issues
- **12** - Sports Psychology
- **13** - Attention Deficit and Hyperactivity Disorder (ADHD)
- **14** - Trauma
- **15** - Paraphilic Disorders

## Dataset

[Turkish Psychological Classification](https://www.kaggle.com/datasets/zgnbyktanr/turkish-psychological-classification-for-nlp/data?select=dataset.csv)

## Finetuned Model

[BERT Turkish Psychological Classification](https://huggingface.co/atakanyilmaz/bert-turkish-psychological-classification)


## Contributors

 Özgün Büyüktanır \
 [Atakan Yılmaz](https://www.linkedin.com/in/atakan-yılmaz-0531b621b/)