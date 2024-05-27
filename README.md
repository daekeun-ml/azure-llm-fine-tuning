# LLM Fine-tuning on Azure

This hands-on walks you through fine-tuning an open source LLM on Azure and serving the fine-tuned model on Azure. It is intended for Data Scientists and ML engineers who have experience with fine-tuning but are unfamiliar with Azure ML.
We are using the Microsoft `Phi-3-mini-4k-instruct`[https://huggingface.co/microsoft/Phi-3-mini-4k-instruct] model, but you can use it freely as long as it is a public liecnse LLM registered with Hugging Face.

## Contents

- [Dataset preparation](dataset-preparation)
- [Fine tuning](fine-tuning)

## Requirements

Before starting, you have met the following requirements:

- [Azure ML getting started](https://github.com/Azure/azureml-examples/tree/main/tutorials): Connect to Azure ML workspace and get your <WORKSPACE_NAME>, <RESOURCE_GROUP> and <SUBSCRIPTION_ID>.
- [Azure ML CLI v2](https://learn.microsoft.com/en-us/azure/machine-learning/concept-v2?view=azureml-api-2#azure-machine-learning-cli-v2)
- A single NVIDIA A100 GPU node (`Standard_NC24ads_A100_v4`) and a single NVIDIA V100 GPU node (`Standard_NC6s_v3`).

## References

- [Azure Machine Learning examples](https://github.com/Azure/azureml-examples)
- [Finetune Small Language Model (SLM) Phi-3 using Azure ML](https://techcommunity.microsoft.com/t5/ai-machine-learning-blog/finetune-small-language-model-slm-phi-3-using-azure-machine/ba-p/4130399)
- [microsoft/Phi-3-mini-4k-instruct](https://huggingface.co/microsoft/Phi-3-mini-4k-instruct): This is Microsoft's official Phi-3-mini-4k-instruct model.
- [daekeun-ml/Phi-3-medium-4k-instruct-ko-poc-v0.1](https://huggingface.co/daekeun-ml/Phi-3-medium-4k-instruct-ko-poc-v0.1)

## License Summary

This sample code is provided under the MIT-0 license. See the LICENSE file.
