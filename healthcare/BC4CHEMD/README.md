# Extract Chemical Entities from Medical Texts
[![Ranked-3 Shitcode](https://img.shields.io/badge/Ranked_3-Named_Entity_Recognition_(NER)_on_BC4CHEMD-blue)](https://paperswithcode.com/sota/named-entity-recognition-on-bc4chemd)

## Model Checkpoints
<p><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><a href="https://huggingface.co/aimped/nlp-health-ner-bc4chemd-chemical-base-en">nlp-health-ner-bc4chemd-chemical-base-en</a></span></p>

## Short Description
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">This model has been developed to identify chemical entities within medical texts. Leveraging the <a href="https://github.com/cambridgeltl/MTL-Bioinformatics-2016/tree/master/data">BC4CHEMD</a> corpus and trained using <a href="https://github.com/dmis-lab/biobert">biobert-pubmed</a> embeddings. </span></p>
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">By harnessing the power of advanced language processing techniques, it offers an unparalleled capability to accurately detect and categorize entities mentioned in a wide range of medical literature. It has the 3rd State-of-the-Result (SOTA) result. This achievement marks a significant advancement in the field of medical text analysis and holds the potential to enhance medical research.</span></p>
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">This model is trained to help data scientists, medical doctors, healthcare professionals, researchers, universities and companies.<br><br></span></p>

## Dataset
<p><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><a href="https://biocreative.bioinformatics.udel.edu/resources/biocreative-iv/chemdner-corpus/">BC4CHEMD</a></span></p>

## Model Performance Metrics
| Name         | precision | recall | f1-score |
|--------------|-----------|--------|----------|
| Chemical     | 0.9298    | 0.9192 | 0.9245   |
| micro-avg    | 0.9298    | 0.9192 | 0.9245   |
| macro-avg    | 0.9298    | 0.9192 | 0.9245   |
| weighted-avg | 0.9298    | 0.9192 | 0.9245   |