# Extract Living Species from Medical Texts
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/biomedical-named-entity-recognition-at-scale/named-entity-recognition-on-linnaeus)](https://paperswithcode.com/sota/named-entity-recognition-on-linnaeus?p=biomedical-named-entity-recognition-at-scale)

## Model Checkpoints

<p><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><a href="https://huggingface.co/aimped/nlp-health-ner-linnaeus-species-base-en">nlp-health-ner-linnaeus-species-base-en</a></span></p>

## Short Description

<p style="text-align: justify; line-height: 1.3;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">This particular model has been trained using <a href="https://linnaeus.sourceforge.net/">Linnaeus Data</a> in conjunction with embeddings from <a href="https://github.com/dmis-lab/biobert">BioBERT</a> that have been fine-tuned using PubMed data. </span></p>
<p style="text-align: justify; line-height: 1.3;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">The primary purpose of this model is to identify and extract species information within medical texts. </span></p>
<p style="text-align: justify; line-height: 1.3;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">Notably, this model has demonstrated exceptional performance, achieving a state-of-the-art (SOTA) F1 score of 89.72 in its ability to accurately identify and classify species mentions in medical contexts.</span></p>

## Dataset

<p><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><a href="https://github.com/cambridgeltl/MTL-Bioinformatics-2016/tree/master/data">Linnaeus Data</a></span></p>

## Model Performance Metrics

| Name         | precision | recall | f1-score | support |
|--------------|-----------|--------|----------|---------|
| Species      | 0.9356    | 0.8618 | 0.8972   | 1433    |
| micro-avg    | 0.9356    | 0.8618 | 0.8972   | 1433    |
| macro-avg    | 0.9356    | 0.8618 | 0.8972   | 1433    |
| weighted-avg | 0.9356    | 0.8618 | 0.8972   | 1433    |

 