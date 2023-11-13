# Extract Diseases from Medical Texts
[![Ranked-#2 Shitcode](https://img.shields.io/badge/Ranked_#2-Named_Entity_Recognition_(NER)_on_NCBI-blue)](https://paperswithcode.com/sota/named-entity-recognition-ner-on-ncbi-disease)

## Model Checkpoints
<p><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><a href="https://huggingface.co/aimped/nlp-health-ner-ncbi-disease-base-en">nlp-health-ner-ncbi-disease-base-en</a></span></p>

## Short Description
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">This model has been developed to identify diseases within medical texts. </span></p>
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">In the training&nbsp;<a href="https://www.ncbi.nlm.nih.gov/CBBresearch/Dogan/DISEASE/disclaimer.html">NCBI Disease corpus</a> and&nbsp; <a href="https://github.com/dmis-lab/biobert">biobert-pubmed</a> embeddings are used and this model achieves state-of-the-art (SOTA) results in disease recognition. </span></p>
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">By harnessing the power of advanced language processing techniques, it offers an unparalleled capability to accurately detect and categorize diseases mentioned in a wide range of medical literature. This achievement marks a significant advancement in the field of medical text analysis and holds the potential to enhance medical research, diagnosis, and patient care.</span></p>

## Dataset
<p><a href="https://www.ncbi.nlm.nih.gov/CBBresearch/Dogan/DISEASE/disclaimer.html" style="font-size: 16px; font-family: &quot;IBM Plex Sans&quot;, sans-serif;">NCBI Dsease Corpus</a></p>

## Model Performance Metrics
| Name         | precision | recall | f1-score | support |
|--------------|-----------|--------|----------|---------|
| Disease      | 0.8924    | 0.9156 | 0.9039   | 960     |
| micro-avg    | 0.8924    | 0.9156 | 0.9039   | 960     |
| macro-avg    | 0.8924    | 0.9156 | 0.9039   | 960     |
| weighted-avg | 0.8924    | 0.9156 | 0.9039   | 960     |