# Extract Chemical and Disease Entities from Medical Text
[![Ranked-4 Shitcode](https://img.shields.io/badge/Ranked_4-Named_Entity_Recognition_(NER)_on_BC5CDR-blue)](https://paperswithcode.com/sota/named-entity-recognition-ner-on-bc5cdr)

## Model Checkpoints
<p><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><a href="https://huggingface.co/aimped/nlp-health-ner-bc5cdr-chemical-disease-base-en">nlp-health-ner-bc5cdr-chemical-disease-base-en</a></span></p>

## Short Description
<p style="text-align: justify; line-height: 1.3;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">By training <a href="https://github.com/cambridgeltl/MTL-Bioinformatics-2016/tree/master/data">BC5CDR dataset</a> with <a href="https://github.com/dmis-lab/biobert">BioBERT</a> embeddings finetuned on PubMed data, we achieved improved accuracy in predicting Cehmical and Disease labels, merging domain-specific context for better results.</span></p>
<p style="text-align: justify; line-height: 1.3;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">We have the 4th State-of-the-Result (SOTA) in the world.</span><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><br></span></p>
<p style="text-align: justify; line-height: 1.3;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">This model is trained to help data scientists, medical doctors, healthcare professionals, researchers, universities and companies.</span></p>

## Dataset
<p><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><a href="https://github.com/cambridgeltl/MTL-Bioinformatics-2016/tree/master/data">BC5CDR Data</a></span></p>

## Model Performance Metrics
| Name         | precision | recall | f1-score |
|--------------|-----------|--------|----------|
| Chemical     | 0.9366    | 0.9439 | 0.9403   |
| Disease      | 0.8649    | 0.8795 | 0.8721   |
| micro-avg    | 0.9041    | 0.9149 | 0.9095   |
| macro-avg    | 0.9007    | 0.9117 | 0.9062   |
| weighted-avg | 0.9043    | 0.9149 | 0.9095   |