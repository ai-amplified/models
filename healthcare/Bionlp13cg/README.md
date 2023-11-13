# Extract Cancer Genetics Information from Medical Texts
[![State-of-the-art Shitcode](https://img.shields.io/badge/State_of_the_Art-Named_Entity_Recognition_(NER)_on_Bionlp13cg-blue)](https://paperswithcode.com/sota/named-entity-recognition-on-bionlp13-cg)

## Model Checkpoints
<p><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><a href="https://huggingface.co/aimped/nlp-health-ner-cancer-genetics-large-en">nlp-health-ner-cancer-genetics-large-en</a></span></p>

## Short Description
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">This model has been developed to identify 16 entities within medical texts. Leveraging the <a href="https://github.com/cambridgeltl/MTL-Bioinformatics-2016/tree/master/data">BioNLP13CG</a> corpus and trained using <a href="https://github.com/dmis-lab/biobert">biobert-pubmed</a> embeddings, this innovative model achieves State-of-the-Art (SOTA) results in 16 entities recognition. It accurately detects and categorizes entities mentioned in a wide range of medical literature. This achievement marks a significant advancement in the field of medical text analysis and holds the potential to enhance medical research.</span></p>
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">This model is trained to help data scientists, medical doctors, healthcare professionals, researchers, universities and companies.</span></p>

## Dataset
<p><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><a href="https://2013.bionlp-st.org/tasks/cancer-genetics-cg-task#BAD_URL">BioNLP2013CG</a></span></p>

## Model Performance Metrics
| Name                            | precision | recall | f1-score |
|---------------------------------|-----------|--------|----------|
| Organ                           | 0.7857    | 0.7756 | 0.7806   |
| Organism                        | 0.8967    | 0.8880 | 0.8923   |
| Organism_subdivision            | 0.6667    | 0.5128 | 0.5797   |
| Organism_substance              | 0.9022    | 0.8137 | 0.8557   |
| Amino_acid                      | 0.7812    | 0.4032 | 0.5319   |
| Anatomical_system               | 0.5556    | 0.2941 | 0.3846   |
| Cancer                          | 0.9111    | 0.8983 | 0.9046   |
| Cell                            | 0.9272    | 0.8806 | 0.9033   |
| Cellular_component              | 0.8085    | 0.8444 | 0.8261   |
| Developing_anatomical_structure | 0.8333    | 0.5882 | 0.6897   |
| Gene_or_gene_product            | 0.9111    | 0.9190 | 0.9151   |
| Immaterial_anatomical_entity    | 0.6111    | 0.7097 | 0.6567   |
| Multi_tissue_structure          | 0.7596    | 0.7822 | 0.7707   |
| Pathological_formation          | 0.6465    | 0.7273 | 0.6845   |
| Simple_chemical                 | 0.9035    | 0.8501 | 0.8760   |
| Tissue                          | 0.6941    | 0.8261 | 0.7543   |
| micro_avg                       | 0.8840    | 0.8730 | 0.8785   |
| macro_avg                       | 0.7871    | 0.7321 | 0.7504   |
| weighted_avg                    | 0.8851    | 0.8730 | 0.8778   |

 