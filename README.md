# arXiv classifier

This is a project to scrape arXiv papers and classify them using a state of the art classifiers **BERT** and **SciBERT**. 

Scraper used for this project is present in https://github.com/cellcomplexitylab/gufi . Feel free to use it and create issues for me 
if it doesn't perform as per your need or for any customization.

## Raw and preprocessed Data

All the raw and preprocessed data is present in [OneDrive](https://utoronto-my.sharepoint.com/personal/m_alexopoulos_utoronto_ca/_layouts/15/onedrive.aspx?ct=1622420717026&or=OWA%2DNT&cid=b61b51bf%2Da6d6%2D0169%2D7600%2D49e4c16ef20f&originalPath=aHR0cHM6Ly91dG9yb250by1teS5zaGFyZXBvaW50LmNvbS86ZjovZy9wZXJzb25hbC9tX2FsZXhvcG91bG9zX3V0b3JvbnRvX2NhL0VzbkpWdmY3X1lSRnJveXlMdTVPcVpjQk0tR24zMV9FNEltbFZsMGd4cm5EaVE%5FcnRpbWU9T05DQWtNb2oyVWc&id=%2Fpersonal%2Fm%5Falexopoulos%5Futoronto%5Fca%2FDocuments%2FA%5FVerma%5Fwork%2Fexp%5F01%28arXiv%29)
 feel free to ask [Professor Michelle](https://github.com/malexopoulos) for its access.

## exp-01 (classifying using the Title only)

This was an attempt to just use the Title of the papers and attempt to classify them using different transformer models.

### exp-01-01 (Using BERT with its pre-trained tokenizer)

the notebook `BERT_exp_01_01.ipynb` implements the model using **PyTorch** and **HuggingFace**, the model is build using PyTorch Lightning because it make the GPU usage and parallelization easier.

### exp-02-01 (Using SciBERT with its pre-trained tokenizer)

the notebook `Sci_BERT_exp_02_01.ipynb` implements the model using **PyTorch** and **HuggingFace**, the model is build using PyTorch Lightning because it make the GPU usage and parallelization easier.

## Results and models

All the models are again present in [OneDrive](https://utoronto-my.sharepoint.com/personal/m_alexopoulos_utoronto_ca/_layouts/15/onedrive.aspx?ct=1622420717026&or=OWA%2DNT&cid=b61b51bf%2Da6d6%2D0169%2D7600%2D49e4c16ef20f&originalPath=aHR0cHM6Ly91dG9yb250by1teS5zaGFyZXBvaW50LmNvbS86ZjovZy9wZXJzb25hbC9tX2FsZXhvcG91bG9zX3V0b3JvbnRvX2NhL0VzbkpWdmY3X1lSRnJveXlMdTVPcVpjQk0tR24zMV9FNEltbFZsMGd4cm5EaVE%5FcnRpbWU9T05DQWtNb2oyVWc&id=%2Fpersonal%2Fm%5Falexopoulos%5Futoronto%5Fca%2FDocuments%2FA%5FVerma%5Fwork%2Fexp%5F01%28arXiv%29) 
and the results are summarized in the `arXiv_Classifier.pdf`
