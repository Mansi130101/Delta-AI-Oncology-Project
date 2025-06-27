# Previous blockers/updates:
- overview of the project

# Topics Discussed:
- Scoping problem statement:
    - scope out problem and solution from the challenge
    - create an overview flowchart of what is input to project model, what is the expected output, what happens behind the scene in the model

- Deliverables of the project:
    - code
    - report: with details
    - presentation: overview
    - video: demo showcase [optional]

- Github codebase:
    - running code
    - pulling/pushing changes from PR and branches
    - versioning code for each accesibility and transpirancy

# Next Steps:
- select category of problem (scope any one: lung, breast, skin, brain, colon)
- download training dataset opensource/kaggle
- identify models to finetune on from huggingface
- working on baseline code base:
    - data folder: takes dataset
    - process.py: breaks into train and test split (80:20)
    - finetune.py: train dataset finetune pretrained model for classification
    - infer.py: inference results using the test set
    - suggestion.py: llm call to provide guidance on the result
    - prompt.md: prompt instruction for suggestion.py
        - health, exercise, medication, treatment... 
    - main.py: chatbot/website (streamlit library)


# Resources:
- https://www.cancerimagingarchive.net/access-data/
- https://www.kaggle.com/datasets/obulisainaren/multi-cancer
- https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset
- https://data.poltekkes-smg.ac.id/dataset/skin-cancer-detection
- https://universe.roboflow.com/search?q=class%3Acancer
- https://mathematical-oncology.org/resources/datasets.html
- https://www.cancerimagingarchive.net/collection/lung-pet-ct-dx/


