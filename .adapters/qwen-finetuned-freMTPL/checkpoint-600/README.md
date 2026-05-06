---
tags:
- sentence-transformers
- sentence-similarity
- feature-extraction
- generated_from_trainer
- dataset_size:120000
- loss:MatryoshkaLoss
- loss:CoSENTLoss
base_model: Qwen/Qwen3-Embedding-0.6B
widget:
- source_sentence: 'You are an auto insurance underwriter. Evaluate the risk level
    of a policyholder based strictly on the following insurance-related information:

    - Policyholder Age: 68 years old (in France people can drive starting at age 18)

    - Land Type: rural area

    - Region: Centre, France

    - Population density: 13 people/km2 (average density is 1792 people/km2)

    - Vehicle: Renault, Nissan, or Citroen

    - Vehicle Age: 1 years old

    - Fuel type: Diesel (either Diesel or Regular Gasoline)

    - Power class: 5 (min = 4, max = 15)

    - Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  sentences:
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 31 years old (in France people can drive starting at age 18)

    - Land Type: urban area

    - Region: Midi–Pyrénées, France

    - Population density: 3301 people/km2 (average density is 1792 people/km2)

    - Vehicle: Japanese (except Nissan) or Korean

    - Vehicle Age: 2 years old

    - Fuel type: Diesel (either Diesel or Regular Gasoline)

    - Power class: 5 (min = 4, max = 15)

    - Bonus-Malus score: 76 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 70 years old (in France people can drive starting at age 18)

    - Land Type: suburban-fringe area

    - Region: Rhône–Alpes, France

    - Population density: 133 people/km2 (average density is 1792 people/km2)

    - Vehicle: Renault, Nissan, or Citroen

    - Vehicle Age: 4 years old

    - Fuel type: Diesel (either Diesel or Regular Gasoline)

    - Power class: 4 (min = 4, max = 15)

    - Bonus-Malus score: 52 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 79 years old (in France people can drive starting at age 18)

    - Land Type: semi-rural area

    - Region: Basse-Normandie, France

    - Population density: 59 people/km2 (average density is 1792 people/km2)

    - Vehicle: Japanese (except Nissan) or Korean

    - Vehicle Age: 0 years old

    - Fuel type: Regular (either Diesel or Regular Gasoline)

    - Power class: 6 (min = 4, max = 15)

    - Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
- source_sentence: 'You are an auto insurance underwriter. Evaluate the risk level
    of a policyholder based strictly on the following insurance-related information:

    - Policyholder Age: 53 years old (in France people can drive starting at age 18)

    - Land Type: suburban-fringe area

    - Region: Rhône–Alpes, France

    - Population density: 210 people/km2 (average density is 1792 people/km2)

    - Vehicle: Renault, Nissan, or Citroen

    - Vehicle Age: 3 years old

    - Fuel type: Regular (either Diesel or Regular Gasoline)

    - Power class: 5 (min = 4, max = 15)

    - Bonus-Malus score: 68 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  sentences:
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 35 years old (in France people can drive starting at age 18)

    - Land Type: urban area

    - Region: Île-de-France, France

    - Population density: 2569 people/km2 (average density is 1792 people/km2)

    - Vehicle: Japanese (except Nissan) or Korean

    - Vehicle Age: 0 years old

    - Fuel type: Regular (either Diesel or Regular Gasoline)

    - Power class: 10 (min = 4, max = 15)

    - Bonus-Malus score: 58 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 31 years old (in France people can drive starting at age 18)

    - Land Type: suburban-fringe area

    - Region: Centre, France

    - Population density: 137 people/km2 (average density is 1792 people/km2)

    - Vehicle: Renault, Nissan, or Citroen

    - Vehicle Age: 10 years old

    - Fuel type: Diesel (either Diesel or Regular Gasoline)

    - Power class: 5 (min = 4, max = 15)

    - Bonus-Malus score: 80 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 56 years old (in France people can drive starting at age 18)

    - Land Type: urban center

    - Region: Île-de-France, France

    - Population density: 27000 people/km2 (average density is 1792 people/km2)

    - Vehicle: Renault, Nissan, or Citroen

    - Vehicle Age: 9 years old

    - Fuel type: Regular (either Diesel or Regular Gasoline)

    - Power class: 5 (min = 4, max = 15)

    - Bonus-Malus score: 77 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
- source_sentence: 'You are an auto insurance underwriter. Evaluate the risk level
    of a policyholder based strictly on the following insurance-related information:

    - Policyholder Age: 28 years old (in France people can drive starting at age 18)

    - Land Type: semi-rural area

    - Region: Basse-Normandie, France

    - Population density: 64 people/km2 (average density is 1792 people/km2)

    - Vehicle: Renault, Nissan, or Citroen

    - Vehicle Age: 10 years old

    - Fuel type: Regular (either Diesel or Regular Gasoline)

    - Power class: 7 (min = 4, max = 15)

    - Bonus-Malus score: 76 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  sentences:
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 33 years old (in France people can drive starting at age 18)

    - Land Type: suburban-fringe area

    - Region: Centre, France

    - Population density: 298 people/km2 (average density is 1792 people/km2)

    - Vehicle: Renault, Nissan, or Citroen

    - Vehicle Age: 8 years old

    - Fuel type: Regular (either Diesel or Regular Gasoline)

    - Power class: 7 (min = 4, max = 15)

    - Bonus-Malus score: 101 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 40 years old (in France people can drive starting at age 18)

    - Land Type: suburban area

    - Region: Bretagne, France

    - Population density: 1579 people/km2 (average density is 1792 people/km2)

    - Vehicle: Renault, Nissan, or Citroen

    - Vehicle Age: 16 years old

    - Fuel type: Regular (either Diesel or Regular Gasoline)

    - Power class: 5 (min = 4, max = 15)

    - Bonus-Malus score: 100 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 36 years old (in France people can drive starting at age 18)

    - Land Type: urban center

    - Region: Île-de-France, France

    - Population density: 22669 people/km2 (average density is 1792 people/km2)

    - Vehicle: Renault, Nissan, or Citroen

    - Vehicle Age: 1 years old

    - Fuel type: Regular (either Diesel or Regular Gasoline)

    - Power class: 6 (min = 4, max = 15)

    - Bonus-Malus score: 57 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
- source_sentence: 'You are an auto insurance underwriter. Evaluate the risk level
    of a policyholder based strictly on the following insurance-related information:

    - Policyholder Age: 23 years old (in France people can drive starting at age 18)

    - Land Type: rural area

    - Region: Bourgogne, France

    - Population density: 38 people/km2 (average density is 1792 people/km2)

    - Vehicle: Opel, General Motors, or Ford

    - Vehicle Age: 16 years old

    - Fuel type: Diesel (either Diesel or Regular Gasoline)

    - Power class: 7 (min = 4, max = 15)

    - Bonus-Malus score: 76 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  sentences:
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 23 years old (in France people can drive starting at age 18)

    - Land Type: suburban area

    - Region: Centre, France

    - Population density: 1313 people/km2 (average density is 1792 people/km2)

    - Vehicle: Japanese (except Nissan) or Korean

    - Vehicle Age: 15 years old

    - Fuel type: Regular (either Diesel or Regular Gasoline)

    - Power class: 9 (min = 4, max = 15)

    - Bonus-Malus score: 90 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 48 years old (in France people can drive starting at age 18)

    - Land Type: urban area

    - Region: Provence–Alpes–Côte d’Azur, France

    - Population density: 4762 people/km2 (average density is 1792 people/km2)

    - Vehicle: Mercedes, Chrysler, or BMW

    - Vehicle Age: 13 years old

    - Fuel type: Regular (either Diesel or Regular Gasoline)

    - Power class: 11 (min = 4, max = 15)

    - Bonus-Malus score: 69 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 50 years old (in France people can drive starting at age 18)

    - Land Type: rural area

    - Region: Basse-Normandie, France

    - Population density: 48 people/km2 (average density is 1792 people/km2)

    - Vehicle: Renault, Nissan, or Citroen

    - Vehicle Age: 13 years old

    - Fuel type: Regular (either Diesel or Regular Gasoline)

    - Power class: 7 (min = 4, max = 15)

    - Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
- source_sentence: 'You are an auto insurance underwriter. Evaluate the risk level
    of a policyholder based strictly on the following insurance-related information:

    - Policyholder Age: 51 years old (in France people can drive starting at age 18)

    - Land Type: suburban-fringe area

    - Region: Rhône–Alpes, France

    - Population density: 289 people/km2 (average density is 1792 people/km2)

    - Vehicle: Fiat

    - Vehicle Age: 12 years old

    - Fuel type: Regular (either Diesel or Regular Gasoline)

    - Power class: 14 (min = 4, max = 15)

    - Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  sentences:
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 56 years old (in France people can drive starting at age 18)

    - Land Type: suburban-fringe area

    - Region: Rhône–Alpes, France

    - Population density: 276 people/km2 (average density is 1792 people/km2)

    - Vehicle: Mercedes, Chrysler, or BMW

    - Vehicle Age: 1 years old

    - Fuel type: Diesel (either Diesel or Regular Gasoline)

    - Power class: 12 (min = 4, max = 15)

    - Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 24 years old (in France people can drive starting at age 18)

    - Land Type: suburban-fringe area

    - Region: Centre, France

    - Population density: 115 people/km2 (average density is 1792 people/km2)

    - Vehicle: Volkswagen, Audi, Skoda, or Seat

    - Vehicle Age: 9 years old

    - Fuel type: Diesel (either Diesel or Regular Gasoline)

    - Power class: 5 (min = 4, max = 15)

    - Bonus-Malus score: 112 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
  - 'You are an auto insurance underwriter. Evaluate the risk level of a policyholder
    based strictly on the following insurance-related information:

    - Policyholder Age: 38 years old (in France people can drive starting at age 18)

    - Land Type: suburban-fringe area

    - Region: Île-de-France, France

    - Population density: 269 people/km2 (average density is 1792 people/km2)

    - Vehicle: Japanese (except Nissan) or Korean

    - Vehicle Age: 8 years old

    - Fuel type: Diesel (either Diesel or Regular Gasoline)

    - Power class: 6 (min = 4, max = 15)

    - Bonus-Malus score: 57 (scored between 50 and 230 with entrance level 100, <100
    means bonus, >100 means malus)'
pipeline_tag: sentence-similarity
library_name: sentence-transformers
---

# SentenceTransformer based on Qwen/Qwen3-Embedding-0.6B

This is a [sentence-transformers](https://www.SBERT.net) model finetuned from [Qwen/Qwen3-Embedding-0.6B](https://huggingface.co/Qwen/Qwen3-Embedding-0.6B). It maps sentences & paragraphs to a 1024-dimensional dense vector space and can be used for retrieval.

## Model Details

### Model Description
- **Model Type:** Sentence Transformer
- **Base model:** [Qwen/Qwen3-Embedding-0.6B](https://huggingface.co/Qwen/Qwen3-Embedding-0.6B) <!-- at revision 97b0c614be4d77ee51c0cef4e5f07c00f9eb65b3 -->
- **Maximum Sequence Length:** 32768 tokens
- **Output Dimensionality:** 1024 dimensions
- **Similarity Function:** Cosine Similarity
- **Supported Modality:** Text
<!-- - **Training Dataset:** Unknown -->
<!-- - **Language:** Unknown -->
<!-- - **License:** Unknown -->

### Model Sources

- **Documentation:** [Sentence Transformers Documentation](https://sbert.net)
- **Repository:** [Sentence Transformers on GitHub](https://github.com/huggingface/sentence-transformers)
- **Hugging Face:** [Sentence Transformers on Hugging Face](https://huggingface.co/models?library=sentence-transformers)

### Full Model Architecture

```
SentenceTransformer(
  (0): Transformer({'transformer_task': 'feature-extraction', 'modality_config': {'text': {'method': 'forward', 'method_output_name': 'last_hidden_state'}}, 'module_output_name': 'token_embeddings', 'architecture': 'Qwen3Model'})
  (1): Pooling({'embedding_dimension': 1024, 'pooling_mode': 'lasttoken', 'include_prompt': True})
  (2): Normalize({})
)
```

## Usage

### Direct Usage (Sentence Transformers)

First install the Sentence Transformers library:

```bash
pip install -U sentence-transformers
```
Then you can load this model and run inference.
```python
from sentence_transformers import SentenceTransformer

# Download from the 🤗 Hub
model = SentenceTransformer("sentence_transformers_model_id")
# Run inference
queries = [
    'You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:\n- Policyholder Age: 51 years old (in France people can drive starting at age 18)\n- Land Type: suburban-fringe area\n- Region: Rhône–Alpes, France\n- Population density: 289 people/km2 (average density is 1792 people/km2)\n- Vehicle: Fiat\n- Vehicle Age: 12 years old\n- Fuel type: Regular (either Diesel or Regular Gasoline)\n- Power class: 14 (min = 4, max = 15)\n- Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)',
]
documents = [
    'You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:\n- Policyholder Age: 38 years old (in France people can drive starting at age 18)\n- Land Type: suburban-fringe area\n- Region: Île-de-France, France\n- Population density: 269 people/km2 (average density is 1792 people/km2)\n- Vehicle: Japanese (except Nissan) or Korean\n- Vehicle Age: 8 years old\n- Fuel type: Diesel (either Diesel or Regular Gasoline)\n- Power class: 6 (min = 4, max = 15)\n- Bonus-Malus score: 57 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)',
    'You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:\n- Policyholder Age: 56 years old (in France people can drive starting at age 18)\n- Land Type: suburban-fringe area\n- Region: Rhône–Alpes, France\n- Population density: 276 people/km2 (average density is 1792 people/km2)\n- Vehicle: Mercedes, Chrysler, or BMW\n- Vehicle Age: 1 years old\n- Fuel type: Diesel (either Diesel or Regular Gasoline)\n- Power class: 12 (min = 4, max = 15)\n- Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)',
    'You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:\n- Policyholder Age: 24 years old (in France people can drive starting at age 18)\n- Land Type: suburban-fringe area\n- Region: Centre, France\n- Population density: 115 people/km2 (average density is 1792 people/km2)\n- Vehicle: Volkswagen, Audi, Skoda, or Seat\n- Vehicle Age: 9 years old\n- Fuel type: Diesel (either Diesel or Regular Gasoline)\n- Power class: 5 (min = 4, max = 15)\n- Bonus-Malus score: 112 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)',
]
query_embeddings = model.encode_query(queries)
document_embeddings = model.encode_document(documents)
print(query_embeddings.shape, document_embeddings.shape)
# [1, 1024] [3, 1024]

# Get the similarity scores for the embeddings
similarities = model.similarity(query_embeddings, document_embeddings)
print(similarities)
# tensor([[0.9771, 0.9785, 0.9605]])
```
<!--
### Direct Usage (Transformers)

<details><summary>Click to see the direct usage in Transformers</summary>

</details>
-->

<!--
### Downstream Usage (Sentence Transformers)

You can finetune this model on your own dataset.

<details><summary>Click to expand</summary>

</details>
-->

<!--
### Out-of-Scope Use

*List how the model may foreseeably be misused and address what users ought not to do with the model.*
-->

<!--
## Bias, Risks and Limitations

*What are the known or foreseeable issues stemming from this model? You could also flag here known failure cases or weaknesses of the model.*
-->

<!--
### Recommendations

*What are recommendations with respect to the foreseeable issues? For example, filtering explicit content.*
-->

## Training Details

### Training Dataset

#### Unnamed Dataset

* Size: 120,000 training samples
* Columns: <code>sentence1</code>, <code>sentence2</code>, and <code>score</code>
* Approximate statistics based on the first 1000 samples:
  |         | sentence1                                                                             | sentence2                                                                             | score                                                           |
  |:--------|:--------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------|:----------------------------------------------------------------|
  | type    | string                                                                                | string                                                                                | float                                                           |
  | details | <ul><li>min: 177 tokens</li><li>mean: 189.52 tokens</li><li>max: 199 tokens</li></ul> | <ul><li>min: 177 tokens</li><li>mean: 189.04 tokens</li><li>max: 199 tokens</li></ul> | <ul><li>min: 0.02</li><li>mean: 0.59</li><li>max: 1.0</li></ul> |
* Samples:
  | sentence1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | sentence2                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | score                            |
  |:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------|
  | <code>You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:<br>- Policyholder Age: 33 years old (in France people can drive starting at age 18)<br>- Land Type: suburban area<br>- Region: Centre, France<br>- Population density: 856 people/km2 (average density is 1792 people/km2)<br>- Vehicle: Volkswagen, Audi, Skoda, or Seat<br>- Vehicle Age: 6 years old<br>- Fuel type: Regular (either Diesel or Regular Gasoline)<br>- Power class: 7 (min = 4, max = 15)<br>- Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)</code>                       | <code>You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:<br>- Policyholder Age: 52 years old (in France people can drive starting at age 18)<br>- Land Type: suburban-fringe area<br>- Region: Bretagne, France<br>- Population density: 461 people/km2 (average density is 1792 people/km2)<br>- Vehicle: Renault, Nissan, or Citroen<br>- Vehicle Age: 13 years old<br>- Fuel type: Diesel (either Diesel or Regular Gasoline)<br>- Power class: 5 (min = 4, max = 15)<br>- Bonus-Malus score: 55 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)</code>  | <code>0.3333333333333333</code>  |
  | <code>You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:<br>- Policyholder Age: 69 years old (in France people can drive starting at age 18)<br>- Land Type: suburban-fringe area<br>- Region: Bretagne, France<br>- Population density: 300 people/km2 (average density is 1792 people/km2)<br>- Vehicle: Renault, Nissan, or Citroen<br>- Vehicle Age: 5 years old<br>- Fuel type: Regular (either Diesel or Regular Gasoline)<br>- Power class: 6 (min = 4, max = 15)<br>- Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)</code>                   | <code>You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:<br>- Policyholder Age: 75 years old (in France people can drive starting at age 18)<br>- Land Type: suburban area<br>- Region: Centre, France<br>- Population density: 614 people/km2 (average density is 1792 people/km2)<br>- Vehicle: Opel, General Motors, or Ford<br>- Vehicle Age: 6 years old<br>- Fuel type: Regular (either Diesel or Regular Gasoline)<br>- Power class: 11 (min = 4, max = 15)<br>- Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)</code>        | <code>0.19517102615694162</code> |
  | <code>You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:<br>- Policyholder Age: 58 years old (in France people can drive starting at age 18)<br>- Land Type: suburban area<br>- Region: Provence–Alpes–Côte d’Azur, France<br>- Population density: 1326 people/km2 (average density is 1792 people/km2)<br>- Vehicle: Japanese (except Nissan) or Korean<br>- Vehicle Age: 3 years old<br>- Fuel type: Diesel (either Diesel or Regular Gasoline)<br>- Power class: 7 (min = 4, max = 15)<br>- Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)</code> | <code>You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:<br>- Policyholder Age: 41 years old (in France people can drive starting at age 18)<br>- Land Type: suburban area<br>- Region: Poitou–Charentes, France<br>- Population density: 1265 people/km2 (average density is 1792 people/km2)<br>- Vehicle: Mercedes, Chrysler, or BMW<br>- Vehicle Age: 6 years old<br>- Fuel type: Regular (either Diesel or Regular Gasoline)<br>- Power class: 9 (min = 4, max = 15)<br>- Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)</code> | <code>1.0</code>                 |
* Loss: [<code>MatryoshkaLoss</code>](https://sbert.net/docs/package_reference/sentence_transformer/losses.html#matryoshkaloss) with these parameters:
  ```json
  {
      "loss": "CoSENTLoss",
      "matryoshka_dims": [
          1024,
          64,
          48
      ],
      "matryoshka_weights": [
          1,
          1,
          1
      ],
      "n_dims_per_step": -1
  }
  ```

### Evaluation Dataset

#### Unnamed Dataset

* Size: 30,000 evaluation samples
* Columns: <code>sentence1</code>, <code>sentence2</code>, and <code>score</code>
* Approximate statistics based on the first 1000 samples:
  |         | sentence1                                                                             | sentence2                                                                             | score                                                           |
  |:--------|:--------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------|:----------------------------------------------------------------|
  | type    | string                                                                                | string                                                                                | float                                                           |
  | details | <ul><li>min: 177 tokens</li><li>mean: 189.19 tokens</li><li>max: 200 tokens</li></ul> | <ul><li>min: 178 tokens</li><li>mean: 189.59 tokens</li><li>max: 199 tokens</li></ul> | <ul><li>min: 0.03</li><li>mean: 0.57</li><li>max: 1.0</li></ul> |
* Samples:
  | sentence1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | sentence2                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | score                            |
  |:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------|
  | <code>You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:<br>- Policyholder Age: 41 years old (in France people can drive starting at age 18)<br>- Land Type: suburban area<br>- Region: Île-de-France, France<br>- Population density: 763 people/km2 (average density is 1792 people/km2)<br>- Vehicle: Renault, Nissan, or Citroen<br>- Vehicle Age: 18 years old<br>- Fuel type: Regular (either Diesel or Regular Gasoline)<br>- Power class: 7 (min = 4, max = 15)<br>- Bonus-Malus score: 64 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)</code>   | <code>You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:<br>- Policyholder Age: 47 years old (in France people can drive starting at age 18)<br>- Land Type: suburban area<br>- Region: Rhône–Alpes, France<br>- Population density: 1110 people/km2 (average density is 1792 people/km2)<br>- Vehicle: Japanese (except Nissan) or Korean<br>- Vehicle Age: 2 years old<br>- Fuel type: Regular (either Diesel or Regular Gasoline)<br>- Power class: 6 (min = 4, max = 15)<br>- Bonus-Malus score: 62 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)</code> | <code>1.0</code>                 |
  | <code>You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:<br>- Policyholder Age: 42 years old (in France people can drive starting at age 18)<br>- Land Type: semi-rural area<br>- Region: Poitou–Charentes, France<br>- Population density: 76 people/km2 (average density is 1792 people/km2)<br>- Vehicle: Renault, Nissan, or Citroen<br>- Vehicle Age: 3 years old<br>- Fuel type: Diesel (either Diesel or Regular Gasoline)<br>- Power class: 6 (min = 4, max = 15)<br>- Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)</code> | <code>You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:<br>- Policyholder Age: 35 years old (in France people can drive starting at age 18)<br>- Land Type: urban area<br>- Region: Rhône–Alpes, France<br>- Population density: 9307 people/km2 (average density is 1792 people/km2)<br>- Vehicle: Renault, Nissan, or Citroen<br>- Vehicle Age: 8 years old<br>- Fuel type: Regular (either Diesel or Regular Gasoline)<br>- Power class: 6 (min = 4, max = 15)<br>- Bonus-Malus score: 64 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)</code>           | <code>0.2779783393501805</code>  |
  | <code>You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:<br>- Policyholder Age: 46 years old (in France people can drive starting at age 18)<br>- Land Type: semi-rural area<br>- Region: Centre, France<br>- Population density: 57 people/km2 (average density is 1792 people/km2)<br>- Vehicle: Opel, General Motors, or Ford<br>- Vehicle Age: 1 years old<br>- Fuel type: Diesel (either Diesel or Regular Gasoline)<br>- Power class: 4 (min = 4, max = 15)<br>- Bonus-Malus score: 50 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)</code>         | <code>You are an auto insurance underwriter. Evaluate the risk level of a policyholder based strictly on the following insurance-related information:<br>- Policyholder Age: 44 years old (in France people can drive starting at age 18)<br>- Land Type: suburban area<br>- Region: Rhône–Alpes, France<br>- Population density: 745 people/km2 (average density is 1792 people/km2)<br>- Vehicle: Mercedes, Chrysler, or BMW<br>- Vehicle Age: 12 years old<br>- Fuel type: Diesel (either Diesel or Regular Gasoline)<br>- Power class: 7 (min = 4, max = 15)<br>- Bonus-Malus score: 60 (scored between 50 and 230 with entrance level 100, <100 means bonus, >100 means malus)</code>          | <code>0.17355371900826447</code> |
* Loss: [<code>MatryoshkaLoss</code>](https://sbert.net/docs/package_reference/sentence_transformer/losses.html#matryoshkaloss) with these parameters:
  ```json
  {
      "loss": "CoSENTLoss",
      "matryoshka_dims": [
          1024,
          64,
          48
      ],
      "matryoshka_weights": [
          1,
          1,
          1
      ],
      "n_dims_per_step": -1
  }
  ```

### Training Hyperparameters
#### Non-Default Hyperparameters

- `per_device_train_batch_size`: 64
- `gradient_accumulation_steps`: 4
- `learning_rate`: 0.0002
- `num_train_epochs`: 2
- `fp16`: True
- `load_best_model_at_end`: True
- `optim`: adamw_8bit
- `gradient_checkpointing`: True

#### All Hyperparameters
<details><summary>Click to expand</summary>

- `overwrite_output_dir`: False
- `do_predict`: False
- `prediction_loss_only`: True
- `per_device_train_batch_size`: 64
- `per_device_eval_batch_size`: 8
- `per_gpu_train_batch_size`: None
- `per_gpu_eval_batch_size`: None
- `gradient_accumulation_steps`: 4
- `eval_accumulation_steps`: None
- `torch_empty_cache_steps`: None
- `learning_rate`: 0.0002
- `weight_decay`: 0.0
- `adam_beta1`: 0.9
- `adam_beta2`: 0.999
- `adam_epsilon`: 1e-08
- `max_grad_norm`: 1.0
- `num_train_epochs`: 2
- `max_steps`: -1
- `lr_scheduler_type`: linear
- `lr_scheduler_kwargs`: {}
- `warmup_ratio`: 0.0
- `warmup_steps`: 0
- `log_level`: passive
- `log_level_replica`: warning
- `log_on_each_node`: True
- `logging_nan_inf_filter`: True
- `save_safetensors`: True
- `save_on_each_node`: False
- `save_only_model`: False
- `restore_callback_states_from_checkpoint`: False
- `no_cuda`: False
- `use_cpu`: False
- `use_mps_device`: False
- `seed`: 42
- `data_seed`: None
- `jit_mode_eval`: False
- `bf16`: False
- `fp16`: True
- `fp16_opt_level`: O1
- `half_precision_backend`: auto
- `bf16_full_eval`: False
- `fp16_full_eval`: False
- `tf32`: None
- `local_rank`: 0
- `ddp_backend`: None
- `tpu_num_cores`: None
- `tpu_metrics_debug`: False
- `debug`: []
- `dataloader_drop_last`: False
- `dataloader_num_workers`: 0
- `dataloader_prefetch_factor`: None
- `past_index`: -1
- `disable_tqdm`: False
- `remove_unused_columns`: True
- `label_names`: None
- `load_best_model_at_end`: True
- `ignore_data_skip`: False
- `fsdp`: []
- `fsdp_min_num_params`: 0
- `fsdp_config`: {'min_num_params': 0, 'xla': False, 'xla_fsdp_v2': False, 'xla_fsdp_grad_ckpt': False}
- `fsdp_transformer_layer_cls_to_wrap`: None
- `accelerator_config`: {'split_batches': False, 'dispatch_batches': None, 'even_batches': True, 'use_seedable_sampler': True, 'non_blocking': False, 'gradient_accumulation_kwargs': None}
- `parallelism_config`: None
- `deepspeed`: None
- `label_smoothing_factor`: 0.0
- `optim`: adamw_8bit
- `optim_args`: None
- `adafactor`: False
- `group_by_length`: False
- `length_column_name`: length
- `project`: huggingface
- `trackio_space_id`: trackio
- `ddp_find_unused_parameters`: None
- `ddp_bucket_cap_mb`: None
- `ddp_broadcast_buffers`: False
- `dataloader_pin_memory`: True
- `dataloader_persistent_workers`: False
- `skip_memory_metrics`: True
- `use_legacy_prediction_loop`: False
- `push_to_hub`: False
- `resume_from_checkpoint`: None
- `hub_model_id`: None
- `hub_strategy`: every_save
- `hub_private_repo`: None
- `hub_always_push`: False
- `hub_revision`: None
- `gradient_checkpointing`: True
- `gradient_checkpointing_kwargs`: None
- `include_inputs_for_metrics`: False
- `include_for_metrics`: []
- `eval_do_concat_batches`: True
- `fp16_backend`: auto
- `push_to_hub_model_id`: None
- `push_to_hub_organization`: None
- `mp_parameters`: 
- `auto_find_batch_size`: False
- `full_determinism`: False
- `torchdynamo`: None
- `ray_scope`: last
- `ddp_timeout`: 1800
- `torch_compile`: False
- `torch_compile_backend`: None
- `torch_compile_mode`: None
- `include_tokens_per_second`: False
- `include_num_input_tokens_seen`: no
- `neftune_noise_alpha`: None
- `optim_target_modules`: None
- `batch_eval_metrics`: False
- `eval_on_start`: False
- `use_liger_kernel`: False
- `liger_kernel_config`: None
- `eval_use_gather_object`: False
- `average_tokens_across_devices`: True
- `prompts`: None
- `batch_sampler`: batch_sampler
- `multi_dataset_batch_sampler`: proportional
- `router_mapping`: {}
- `learning_rate_mapping`: {}

</details>

### Training Logs
| Epoch  | Step | Training Loss | Validation Loss |
|:------:|:----:|:-------------:|:---------------:|
| 0.4267 | 200  | 21.9835       | 9.1769          |
| 0.8533 | 400  | 21.941        | 9.1587          |
| 1.2795 | 600  | 21.9174       | 9.1421          |


### Training Time
- **Training**: 5.5 hours

### Framework Versions
- Python: 3.10.12
- Sentence Transformers: 5.4.1
- Transformers: 4.57.1
- PyTorch: 2.6.0+rocm6.4.2.git76481f7c
- Accelerate: 1.11.0
- Datasets: 4.5.0
- Tokenizers: 0.22.1

## Citation

### BibTeX

#### Sentence Transformers
```bibtex
@inproceedings{reimers-2019-sentence-bert,
    title = "Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks",
    author = "Reimers, Nils and Gurevych, Iryna",
    booktitle = "Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing",
    month = "11",
    year = "2019",
    publisher = "Association for Computational Linguistics",
    url = "https://arxiv.org/abs/1908.10084",
}
```

#### MatryoshkaLoss
```bibtex
@misc{kusupati2024matryoshka,
    title={Matryoshka Representation Learning},
    author={Aditya Kusupati and Gantavya Bhatt and Aniket Rege and Matthew Wallingford and Aditya Sinha and Vivek Ramanujan and William Howard-Snyder and Kaifeng Chen and Sham Kakade and Prateek Jain and Ali Farhadi},
    year={2024},
    eprint={2205.13147},
    archivePrefix={arXiv},
    primaryClass={cs.LG}
}
```

#### CoSENTLoss
```bibtex
@article{10531646,
    author={Huang, Xiang and Peng, Hao and Zou, Dongcheng and Liu, Zhiwei and Li, Jianxin and Liu, Kay and Wu, Jia and Su, Jianlin and Yu, Philip S.},
    journal={IEEE/ACM Transactions on Audio, Speech, and Language Processing},
    title={CoSENT: Consistent Sentence Embedding via Similarity Ranking},
    year={2024},
    doi={10.1109/TASLP.2024.3402087}
}
```

<!--
## Glossary

*Clearly define terms in order to be accessible across audiences.*
-->

<!--
## Model Card Authors

*Lists the people who create the model card, providing recognition and accountability for the detailed work that goes into its construction.*
-->

<!--
## Model Card Contact

*Provides a way for people who have updates to the Model Card, suggestions, or questions, to contact the Model Card authors.*
-->