# Healthcare Assistant Chatbot — Azure AI

AI-powered healthcare FAQ chatbot built using Azure AI Language, Microsoft Foundry & Azure Bot with Telegram integration for answering routine patient-support queries.

The chatbot handles administrative questions such as clinic hours, appointment booking, insurance acceptance, telehealth availability, doctor availability & required documents.

## Project Overview

This project demonstrates a healthcare administrative support chatbot developed using Azure AI Language & Microsoft Foundry. A structured knowledge base was created with multiple question variations so the bot could recognise different user phrasings & return consistent answers to common patient-support queries.

The solution was tested in Microsoft Foundry, deployed as a knowledge base, connected with an Azure Bot resource & demonstrated through Telegram-based interaction.

## Tools & Technologies

`Azure AI Language` · `Microsoft Foundry` · `Custom Question Answering` · `Azure AI Search` · `Azure Bot Service` · `Telegram Bot` · `Language Understanding` · `Knowledge Base`

## Knowledge Base Coverage

- Clinic hours & working days
- Online appointment booking
- Health insurance acceptance
- Telehealth availability
- Doctor availability
- Required documents for appointments
- Clinic location & directions

## Testing & Deployment

- Tested the knowledge base with multiple user-query variations
- Validated response relevance for clinic hours, appointment booking & telehealth queries
- Deployed the Custom Question Answering knowledge base in Microsoft Foundry
- Created & configured an Azure Bot resource
- Demonstrated successful patient-support interactions through Telegram

## How It Works

1. A user submits a healthcare administrative query through Telegram.
2. The query is processed by the deployed Azure Bot & Custom Question Answering solution.
3. Azure AI Language matches the query with the most relevant answer in the structured knowledge base.
4. The response is returned to the user through Telegram.
