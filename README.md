# Automatic Text Summarization Algorithm (ATSA)

Análisis de texto para la generación de un resumen

## Description
Durante el proceso de selección de iniciativas para el proyecto de grado, nos enfocamos en idear proyectos con componentes innovadores acordes a las nuevas tecnologías emergentes. Por lo que durante nuestra investigación nos encontramos con el concepto de natural language processing (NLP), lo cual nos pareció interesante abundar sobre ello, en específico el análisis de textos. A raíz de esta investigación, se nos ocurrió realizar un algoritmo que sea capaz de analizar texto y realice un resumen, manteniendo el contexto e idea general de su versión original. 

Con la finalidad de que nuestra iniciativa sea de utilidad a contextos actuales, queremos aplicar nuestro algoritmo a la generación de una sinopsis para los discursos. La intención de esta es permitir al usuario utilizar nuestro algoritmo con el objetivo de que le indique las ideas generales del mismo y disminuir el tiempo de lectura del usuario

## Getting Started

### Dependencies

* Transformer Library (HuggingFace)
* Pipelines (Default BART Summarization)
* AutoTokenizer (Pre-Trained Model for Summarization)
* AutoModelForSeq2SeqLM (Pegasus Summarization)
* AutoModelWithLMHead (T5 Base Summarization)

### Installing
* Installing Transformers
```
!pip install transformers
```
* Importing Transformers
```
import transformers
```
* Importing Pipelines
```
from transformers import pipeline
```
* Importing Tokenizers and AutoModel
```
from transformers import AutoTokenizer, AutoModelForSeq2SeqLM
from transformers import AutoTokenizer, AutoModelWithLMHead
```
* Import Torch (PyTorch)
```
import torch
```

### Executing program

Open the *.ipynb algorithm with the Summarization method you desire and open it with Google Collab

## Version History

* 1.0
    * Initial Summarization Codes
    * See [commit change]() or See [release history]()
* 1.1
    * Initial Release and files renaming

## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details

## Acknowledgments


