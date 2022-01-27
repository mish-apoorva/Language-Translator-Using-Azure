## *Language Translation Using Azure*

Project URL: https://github.com/mish-apoorva/Language-Translator-Using-Azure

Demo URL: https://drive.google.com/drive/folders/1DH3yAcP4WrNFo5PLjC4VZiTKSgJJu18Q?usp=sharing

# Translator

Translator, part of Azure Cognitive Services, is a cloud-based machine translation service that can be used to build applications, websites, tools, or any solution requiring multi-language support.

Built for business, Translator is a proven, customizable, and scalable technology for machine translation. Translator technology powers translation features across Microsoft products, including Microsoft Translator app for Android and iOS, Microsoft Office, Edge, SharePoint, Yammer, Visual Studio, Bing, and Skype. Simply integrate translation into web, desktop, or mobile applications, using industry standard REST technology, Translator provides a rich functionality set for any developer. Learn more about machine translation and how Translator works.

Translator also comes equipped with additional features to provide increased value in multilingual apps and workflows: transliteration and bilingual dictionary.


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.12.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Key API Features

Natively Neural – Use modern neural machine translation (NMT) as default for all supported languages. NMT technology has transformed machine translation, providing major advances in translation quality over the existing industry-standard statistical machine translation (SMT) technology. NMT better captures the context of full sentences before translating them, providing much higher quality translation and more human-sounding output. Learn more about how NMT works.

Translate into multiple languages at once – Translate into multiple languages with a single request to the Translator cloud service. The translate feature automatically detects the language of the source content.

Detect – Automatically detect the language of the text sent to the API to help decide which content should be sent for translation or not.

Transliteration – Convert words and sentences from one script into another script. For instance, you can present Chinese characters in the Latin alphabet (PinYin) so they can be read by non-Chinese audiences.

Bilingual dictionary – Display alternative translations from or to English, examples of words in context to help you choose the perfect translation, and even examples of translated sentences using this word.


## About

This is demo for Azure text translator service with angular 8.
Please get a subscription key from azure   `https://docs.microsoft.com/en-us/azure/cognitive-services/cognitive-services-apis-create-account?tabs=multiservice%2Cwindows` and replace in TranslatorService below line.
.set('Ocp-Apim-Subscription-Key', '<AZURE_API_KEY>')


## Prerequisites
Azure subscription - Create one for free

Once you have an Azure subscription, create a Translator resource in the Azure portal to get your key and endpoint. After it deploys, select Go to resource.

You'll need the key and endpoint from the resource to connect your application to the Translator service. You'll paste your key and endpoint into the code below later in the quickstart. You can find these values on the Azure portal Keys and Endpoint page:


![image](https://user-images.githubusercontent.com/77064606/150807127-2761c0aa-585b-415b-b111-9e31e1c143e3.png)

Screenshot: Azure portal keys and endpoint page.

You can use the free pricing tier (F0) to try the service, and upgrade later to a paid tier for production.


## Text translation features
The following methods are supported by the Text Translation feature:

Languages. Returns a list of languages supported by Translate, Transliterate, and Dictionary Lookup operations. This request does not require authentication; just copy and paste the following GET request into Postman or your favorite API tool or browser:

HTTP

https://api.cognitive.microsofttranslator.com/languages?api-version=3.0
Translate. Renders single source-language text to multiple target-language texts with a single request.

Transliterate. Converts characters or letters of a source language to the corresponding characters or letters of a target language.

Detect. Returns the source code language code and a boolean variable denoting whether the detected language is supported for text translation and transliteration.

 Note

You can Translate, Transliterate, and Detect text with a single REST API call .

Dictionary lookup. Returns equivalent words for the source term in the target language.

Dictionary example Returns grammatical structure and context examples for the source term and target term pair.

![image](https://user-images.githubusercontent.com/77064606/150808720-11ee63a4-d289-4923-ba2b-151d95800628.png)


## Demo

![2020-08-03 (7)](https://user-images.githubusercontent.com/48589838/89154539-af335e00-d584-11ea-8398-7792510ce065.png)
![2020-08-03 (8)](https://user-images.githubusercontent.com/48589838/89154541-b0648b00-d584-11ea-8872-1ce63be70cdc.png)

