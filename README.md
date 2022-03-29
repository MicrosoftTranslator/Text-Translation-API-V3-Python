---
page_type: sample
name: Microsoft Translator Python samples (v3)
description: This repository includes Python code samples for Microsoft Translator. 
urlFragment: translator-python-v3
languages:
- python
products:
- azure
- azure-cognitive-services
- azure-translator
---

# Translator API V3 - Python Samples

This repository includes Python code samples for Microsoft Translator. The samples are designed to run on Python 2.7.x and Python 3.x. Each sample corresponds to a [Quickstart](https://docs.microsoft.com/azure/cognitive-services/translator/quickstart-translator) activity on doc.microsoft.com, including:

* Translating text
* Transliterating text 
* Identifying the language of source text
* Getting alternate translations
* Getting a complete list of supported languages
* Determining sentence length

[Get started with the Translator quickstart](https://docs.microsoft.com/azure/cognitive-services/translator/quickstart-translator).

## Prerequisites

Here's what you'll need before you use these samples:

* Your favorite IDE or text editor
* Python 2.7.x or 3.x
* An Azure subscription - [Sign-up for a free account](https://docs.microsoft.com/azure/cognitive-services/translator/translator-text-how-to-signup)!
* A Translator resource - [Create a Translator resource](https://ms.portal.azure.com/#create/Microsoft.CognitiveServicesTextTranslation)

## Code samples

This repository includes a sample for each of the methods made available by the Microsoft Translator API v3. To use each of the samples, follow these instructions:

* Create a new project in your favorite IDE or editor.
* Copy the code from one of the samples into your project.
* Set your subscription key, the Azure region of your resource and the Text Translation endpoint as environment variables
`TRANSLATOR_TEXT_SUBSCRIPTION_KEY`
`TRANSLATOR_TEXT_REGION`
`TRANSLATOR_TEXT_ENDPOINT`

* Run the program. For example: `python Translate.py`.

## Resources

* [What is Translator?](https://docs.microsoft.com/azure/cognitive-services/translator/translator-info-overview)
* [v3 Translator API Reference](https://docs.microsoft.com/azure/cognitive-services/translator/)
* [Supported languages](https://docs.microsoft.com/azure/cognitive-services/translator/language-support)
