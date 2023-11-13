# Extract Anatomical Structures from Medical Text
[![Ranked-2 Shitcode](https://img.shields.io/badge/Ranked_2-Named_Entity_Recognition_(NER)_on_Anatem-blue)](https://paperswithcode.com/sota/named-entity-recognition-on-anatem)

## Model Checkpoints
<p><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><a href="https://huggingface.co/aimped/nlp-health-ner-anatem-anatomy-base-en">nlp-health-ner-anatem-anatomy-base-en</a></span></p>

## Short Description
<p style="text-align: justify; line-height: 1.3;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">By training <a href="https://github.com/cambridgeltl/MTL-Bioinformatics-2016/tree/master/data/AnatEM-IOB">AnatEM dataset</a> with <a href="https://github.com/dmis-lab/biobert">BioBERT</a> embeddings finetuned on PubMed data, we achieved 2nd SOTA results in predicting anatomy labels, merging domain-specific context for better results.</span></p>
<p style="text-align: justify; line-height: 1.3;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">This model is trained to help data scientists, medical doctors, healthcare professionals, researchers, universities and companies.</span></p>

## Dataset
<p><a href="https://github.com/cambridgeltl/MTL-Bioinformatics-2016/tree/master/data" style="font-size: 16px; font-family: &quot;IBM Plex Sans&quot;, sans-serif;">AnatEM Dataset</a><br><br></p>

## Model Performance Metrics
| Name         | precision | recall | f1-score |
|--------------|-----------|--------|----------|
| Anatomy      | 0.9177    | 0.9040 | 0.9108   |
| micro-avg    | 0.9177    | 0.9040 | 0.9108   |
| macro-avg    | 0.9177    | 0.9040 | 0.9108   |
| weighted-avg | 0.9177    | 0.9040 | 0.9108   |