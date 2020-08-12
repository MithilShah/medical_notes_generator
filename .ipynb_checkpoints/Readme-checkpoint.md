## About the medical notes generator

It is often difficult to find de-identified medical notes that can be used for product demonstration or for testing NLP algorithms. This library uses [GPT-2](https://huggingface.co/transformers/model_doc/gpt2.html) from the transformers package to generate medical text. It also randomly generates patient name, age and gender.

To use the generator run the cells in report.ipynb A good place to run the generator is [Amazon SageMaker](https://aws.amazon.com/sagemaker/) 