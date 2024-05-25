# Extract Medical Entities to Figure Out the Genetic Underpinnings of Different Cancer Types
[![State-of-the-art Shitcode](https://img.shields.io/badge/State_of_the_Art-Named_Entity_Recognition_(NER)_on_CancerMine-blue)](https://huggingface.co/aimped/nlp-health-ner-cancer-genetics-base-en)

## Model Checkpoints
<p><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><a href="https://huggingface.co/aimped/nlp-health-ner-cancer-genetics-base-en">nlp-health-ner-cancer-genetics-base-en</a></span></p>

## Short Description
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">The study and analysis of medical texts have become an important tool for understanding the genetic basis of different types of cancer. To this end, the AI model we have meticulously <a href="https://huggingface.co/monologg/biobert_v1.1_pubmed">fine-tuned</a> can accurately extract critical medical entities such as cancer, genes, and mutations from texts using advanced natural language processing techniques.</span></p>
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><strong>Cancer:</strong>&nbsp; Cancer is a group of diseases where cells grow uncontrollably and spread to normal tissues in the body. It occurs due to genetic mutations that make normal cells become abnormal. Cancer types can vary greatly based on their genetic foundations, mutations, and influencing genes.<br><br><strong>Gene:</strong>&nbsp;A gene is a fundamental genetic unit in cells. Genes carry encoded information in DNA and provide instructions for producing a specific protein or regulating certain biological processes. Genes are essential components that control cellular functions, growth, development, and metabolism. Genes related to cancer, especially oncogenes and tumor suppressor genes, play a crucial role in cancer development.<br><br><strong>Mutation:&nbsp;</strong>A mutation is a change or disruption in the genetic material of an organism or cell. Mutations can manifest as alterations, insertions, or deletions in genes. Cancer arises as a result of genetic mutations that lead to abnormal cell growth. <br></span></p>
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"> This AI model plays an important role by assisting researchers in the development of cancer research and treatment methods. It helps researchers with the ability to analyze the genetic origins of cancer types more deeply and efficiently by scanning text data. This contributes to significant advances in the fight against cancer while facilitating patients' access to better diagnostics and treatment options. In conclusion, the extraction of medical entities from medical texts stands out as an important step forward in improving cancer research and treatments.</span></p>
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">Each process is limited to a maximum of <strong>128K</strong> characters both for user interface (UI) and API requests. Please note that exceeding these limits is not supported.<br></span></p>
## Dataset
<p><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;"><a href="https://biocreative.bioinformatics.udel.edu/resources/biocreative-iv/chemdner-corpus/">BC4CHEMD</a></span></p>

## Model Performance Metrics
| Name          | Precision | Recall | F1-Score | 
|---------------|-----------|--------|----------|
| cancer        | 0.9239    | 0.9594 | 0.9413   | 
| gene          | 0.8773    | 0.9069 | 0.8918   |
| mutation      | 0.9167    | 0.9533 | 0.9346   |
| micro-avg     | 0.8973    | 0.9295 | 0.9131   | 
| macro-avg     | 0.9060    | 0.9399 | 0.9226   |
| weighted-avg  | 0.8972    | 0.9295 | 0.9131   |