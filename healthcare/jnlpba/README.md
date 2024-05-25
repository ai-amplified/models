# Extract Biomedical Entities from Scientific Texts
[![Ranked-12 Shitcode](https://img.shields.io/badge/Ranked_12-Named_Entity_Recognition_(NER)_on_JNLPBA-blue)](https://paperswithcode.com/sota/named-entity-recognition-ner-on-jnlpba)

## Short Description
<p style="line-height: 1.3; text-align: justify;"><span style="font-family: &quot;IBM Plex Sans&quot;, sans-serif; font-size: 16px;">The NER model for the JNLPBA dataset is designed to identify and classify named entities in biomedical texts. The dataset comprises annotated scientific abstracts, focusing on five entity types: DNA, RNA, cell line, cell type, and protein. The model utilizes transformer-based architectures like BERT, to effectively capture the context and semantic meaning of biomedical terms. It aims to enhance the accuracy of entity recognition in specialized biomedical literature, aiding in information extraction and knowledge discovery in the field of biomedicine.</span></p>

## Dataset
<p style="line-height: 1.3;"><span style="font-size: 16px;"><a href="https://github.com/cambridgeltl/MTL-Bioinformatics-2016/tree/master/data">JNLPBA</a></span></p>

## Model Performance Metrics
| Category      | Precision | Recall  | F1-Score | Support |
|---------------|-----------|---------|----------|---------|
| DNA           | 0.7950    | 0.7235  | 0.7576   | 1056    |
| RNA           | 0.6842    | 0.7712  | 0.7251   | 118     |
| cell_line     | 0.6779    | 0.6820  | 0.6800   | 500     |
| cell_type     | 0.8050    | 0.7652  | 0.7846   | 1921    |
| protein       | 0.7259    | 0.8620  | 0.7882   | 5067    |
| micro-avg     | 0.7451    | 0.8121  | 0.7772   | 8662    |
| macro-avg     | 0.7376    | 0.7608  | 0.7471   | 8662    |
| weighted-avg  | 0.7486    | 0.8121  | 0.7765   | 8662    |