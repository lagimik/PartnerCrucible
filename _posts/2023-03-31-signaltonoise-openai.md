---
title: "Signal:Noise - Generative AI with Azure OpenAI Service"
date: 2023-04-18
---

![Signal to Noise](/PartnerCrucible/Library/signaltonoise-generativeai.png)


[< Back to Signal:Noise index](/PartnerCrucible/SignaltoNoise)

# Generative AI with Azure Open OpenAI Service

This post aims to provide  signal to partners around generative AI by exploring the elements of the solutions and elements of a practice and a starting points for the journey.

## TL;DR

* A *human-in-the-loop / Copilot* approach is used to structure interactions to guide the generative AI capabilities.
* It is essential to follow responsible AI principles when working with generative AI.
* To begin exploring what the potential of *Azure OpenAI Service* could be for your company, and your customers, a first step could be be to leverage *GitHub Copilot* first-hand.
* Azure OpenAI Services consists of the following models: *GPT-3 (soon GPT-4), ChatGPT, DALL-E, and Codex*
* Through *human-in-the-loop* interactions a new family of patterns is emerging including: *Retrieve-then-read, Plan-then-write, and Learn-then-generate*
* A Generative AI practice will involve some customer discovery and exploration that can be facilitated through design thinking techniques such as: *empathy mapping, how might we? questions, rapid prototyping, and experimentation*.
* A Generative AI practice will require expertise around *data sources, data processing, generative models, and output channels*

## Human-in-the-loop

Generative AI is an emerging capability that can be injected into a creative process. This includes development, writing, and visual arts. A *human-in-the-loop / Copilot*  approach is used to structure interactions to guide the generative AI capabilities. This can provide step-wise gains in productivity across a wide range of tasks. At the same time, tapping into these augmentation use-cases will take some exploration and discovery to pace customers through the journey in a responsible manner.

## Responsible AI

Generative AI is a powerful technology that can create novel and realistic content such as text, images, audio and video. However, it can also pose ethical and social challenges, such as the potential for misuse, deception, bias and harm. Therefore, it is essential to follow *responsible AI* principles when working with generative AI. 

The following is an example set of responsible AI principles:

- **Fairness**: The generative AI should respect the diversity and dignity of all people and avoid creating or amplifying any unfair or discriminatory outcomes.
- **Transparency**: The source, purpose and limitations of generative AI should be clearly communicated to the users and stakeholders.
- **Accountability**: The developers and users of generative AI should be accountable for the outcomes and impacts of their applications and take appropriate measures to prevent and mitigate any negative consequences.
- **Reliability & Safety**: The generative AI should be designed and tested to ensure its reliability, security and robustness against errors, attacks and adversarial inputs.
- **Privacy & Security**: The generative AI should respect the privacy and consent of the data subjects and protect the confidentiality and integrity of the data used or generated.
- **Human-centeredness**: The generative AI should augment rather than replace human intelligence and creativity and promote human values and well-being.

By following principles, tailored to your context, generative AI can be used in a responsible, ethical and beneficial way.

## GitHub Copilot - Experiential Discovery of Generative AI

To gain an appreciation of the potential of *Azure OpenAI Service* could be for your company, and your customers, a first step could be be to leverage *GitHub Copilot* first-hand. *Codex*, one of the models in the OpenAI Service, provides a great example of how augmentation with AI can amplify the developer.

GitHub Copilot is a powerful tool that can help independent software vendors (ISVs) and professional services companies to develop high-quality code faster and easier. It acts as a code assistant that can suggest code completions, snippets, tests, and documentation based on the context of your code and the best practices of the GitHub community. GitHub Copilot can help you to:

- Save time and effort by generating code for common tasks and scenarios, such as data processing, web development, machine learning, and more.
- Improve your code quality and reliability by following the standards and conventions of the GitHub community, as well as catching errors and bugs before they cause problems.
- Learn new skills and technologies by exploring different ways of solving problems and discovering new frameworks, libraries, and APIs that you may not be familiar with.
- Enhance your creativity and productivity by getting inspired by the suggestions of GitHub Copilot and experimenting with different solutions and approaches.

GitHub Copilot is designed to work with any programming language and any code editor that supports the Language Server Protocol (LSP) and can be used withing Visual Studio Code, GitHub Codespaces, or any other compatible editor. 

## Models 

Azure OpenAI Services consists of the following models (as of April 2023):


| Model Name | Description | Use-Cases | Success Story |
| ---: | :--- | :--- | :--- |
| **GPT-3** | Large, pretrained AI language model for generating and understanding text. | Copywriting, summarization, parsing unstructured text, classification, and translation. | Sogeti used GPT-3 to develop an AI-powered chatbot for a retail client, which was able to understand and respond to customer queries in a natural language. |
| **DALL·E** | AI model that can generate images from text prompts. | Generating images for e-commerce product catalogs, automating graphic design. | Wipro used DALL·E to create a virtual trial room for a fashion client, enabling customers to see how an outfit would look on them before purchasing. |
| **ChatGPT** | AI model that can generate and understand conversations. | Creating chatbots, improving customer service. | HSBC used ChatGPT to create a virtual assistant for its website, which was able to answer customer queries in a natural language. |
| **Codex** | AI model that can generate and understand code. | Automating programming tasks, improving developer productivity. | Soul Machines used Codex to develop an AI-powered assistant for software developers, which was able to write code and provide guidance on programming tasks. |

## Explore Generative AI Patterns

Through human-in-the-loop interactions with the above models new family of patterns is emerging including: *Retrieve-then-read, Plan-then-write, and Learn-then-generate*

Pattern | Description | Advantages | Challenges
-----: | :----------- | ---------- | -----------
**Retrieve-then-read**| This is a common approach to generative AI, where a system first retrieves relevant information from a large corpus of text and then reads and synthesizes it to produce a coherent output. A sample implementation of the *retrieve-then-read* pattern can be found here: [ChatGPT + Enterprise data with Azure OpenAI and Cognitive Search](https://github.com/Azure-Samples/azure-search-openai-demo)| One of the advantages of the *retrieve-then-read* pattern is that it can leverage both structured and unstructured data sources, and combine factual knowledge with linguistic skills. Another advantage is that it can reduce the computational cost and memory requirements of the generative model, since it only needs to process a subset of the available information. |However, some of the challenges of this pattern are how to select the most relevant documents for a given input, how to handle noisy or contradictory information, and how to ensure the consistency and coherence of the generated text. Other limitations include  the need for a high-quality retrieval system, the dependence on the quality and coverage of the corpus, and the difficulty of handling complex or open-ended queries.
**Plan-then-write** |This approach involves creating a high-level plan or outline of the text to be generated, and then writing the text based on the plan. |This approach can help structure the text and ensure coherence and cohesion. The plan can be generated using various methods, such as rule-based systems, hierarchical models, or graph-based representations. |However, this approach also has some drawbacks, such as the difficulty of generating flexible and creative plans, the complexity of mapping the plan to natural language, and the trade-off between planning quality and efficiency.
**Learn-then-generate** | This approach involves training a system on a large corpus of text to learn general linguistic and domain-specific knowledge, and then generating text based on a given input or prompt. |This approach can leverage pre-trained language models, such as GPT-3, that can generate fluent and diverse text across various domains and tasks. | However, this approach also has some challenges, such as the need for large amounts of data and computational resources, the risk of generating inaccurate or biased text, and the lack of interpretability and controllability of the system.

## Elements of a Practice

### Customer Ideation and Proof of Concepts

In these early stages of Generative AI there is no shortage of opportunity. By the same token, there is to specific set of use-cases that will define success in every case. A more iterative and design driven approach will be required to bring customer from the initial idea to a proof of concept.

Design thinking is a human-centered approach to problem-solving that involves empathy, ideation, prototyping and testing. Some design thinking approaches that can help identify generative AI use-cases are:

Approach | Description 
:----- | :---------- 
**Empathy mapping**| This is a technique to understand the needs, pains and goals of the users or stakeholders of a potential solution. It involves creating a visual representation of what the users say, do, think and feel in relation to a problem or opportunity.
**How might we (HMW) questions** | These are open-ended questions that frame the problem or opportunity in a positive and actionable way. They help to generate ideas for possible solutions that address the users' needs and goals. For example, HMW use generative AI to create personalized learning experiences for students?
**Rapid prototyping** | This is a technique to quickly create and test low-fidelity versions of potential solutions using simple and inexpensive materials. It helps to validate the assumptions and hypotheses behind the ideas and get feedback from the users or stakeholders. For example, using paper sketches or mockups to demonstrate how generative AI can produce different types of content or data.
**Experimentation** | This is a technique to test and measure the impact and feasibility of potential solutions using real-world scenarios and data. It helps to evaluate the effectiveness and viability of the ideas and iterate based on the results. For example, using online platforms or tools to generate and deploy generative AI models and collect data on their performance and user satisfaction.

### Implementation

A generative AI solution based on Microsoft technologies consists of several high-level technology architecture components that work together to create and deliver synthetic data or content. Consider the following as you build your practice.

Component | Description | Solutions
-----: | :---------- | :-------------
**Data sources** |These are the original datasets or inputs that provide the raw material for the generative AI solution. They can be structured or unstructured, and can come from various domains such as text, images, audio, video, etc. | Data sources can be stored in Azure Data Lake Storage, Azure Blob Storage, Azure SQL Database, or other data services.
**Data processing** | This is the stage where the data sources are cleaned, transformed, augmented, labeled, and prepared for the generative AI solution. Data processing can involve various tasks such as data validation, data normalization, data augmentation, data annotation, data splitting, etc. | Data processing can be done using Azure Databricks, Azure Machine Learning, Azure Synapse Analytics, or other data tools.
**Generative models** |These are the core of the generative AI solution. They are the machine learning models that learn from the data sources and generate synthetic data or content. Generative models can use various techniques such as variational autoencoders (VAEs), generative adversarial networks (GANs), transformers, etc. | Generative models can be trained and deployed using OpenAI Services Azure Machine Learning, Azure Cognitive Services, or other AI frameworks.
**Output channels** | These are the ways that the synthetic data or content generated by the generative models are delivered to the end users or applications. Output channels can be various formats such as text files, images, audio files, video files, etc. Output channels can also be various platforms such as web apps, mobile apps, chatbots, etc. | Output channels can be built and hosted using Azure App Service, Azure Functions, Power Virtual Agents, or other web services.

## Way forward - *Mainstream* path to Azure OpenAI Service

- Explore [Responsible AI resources](https://www.microsoft.com/en-us/ai/responsible-ai-resources?activetab=pivot1%3aprimaryr4) designed to help you responsibly use AI at every stage of innovation - from concept to development, deployment, and beyond. 
- Use Github copilot to write the code and experience generative AI [Onboard to GitHub Copilot](https://github.com/login?return_to=%2Fgithub-copilot%2Fsignup)
- Leverage resources on the Partner Crucible [OpenAI on the Partner Crucible](https://lagimik.github.io/PartnerCrucible/DataAISolutionArea)


## Way forward - *Insiders* path to Azure OpenAI Service

- Tune into the [AI Show](https://learn.microsoft.com/en-ca/shows/ai-show/?ocid=aid2463683&wt.mc_id=aiml-17954-sejuare)
- Onboard to the Azure OpenAI Service: [Request Access to Azure OpenAI Service](https://customervoice.microsoft.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR7en2Ais5pxKtso_Pz4b1_xUOFA5Qk1UWDRBMjg0WFhPMkIzTzhKQ1dWNyQlQCN0PWcu)
- Use GitHub as a launch pad [Azure OpenAI Samples](https://github.com/Azure/openai-samples)
- Explore the OpenAI Cookbook [OpenAI Cookbook](https://github.com/openai/openai-cookbook)
 

[< Back to Signal:Noise index](/PartnerCrucibSignaltoNoise)