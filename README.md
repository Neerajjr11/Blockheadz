[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-blue)](https://developer.ibm.com/callforcode/solutions/projects/get-started/)

# Blockheadz

- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM AI service(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)
  - [Live demo](#live-demo)

_INSTRUCTIONS: Complete all required deliverable sections below._

## Project summary

### The issue we are hoping to solve

Our approach will directly deal with environmental sustainability in a shared manner. It aims to create a collaborative culture to solve the problem of unsustainability in a transparent yet feasible way. The idea aims to create an environment of shared efforts to drive all the stakeholders involved in the supply chain process to monitor the factors involved from manufacture to delivery of the product at the retail level so that certain level of sustainability criteria are met.

### How our technology solution can help

The Product lays down a whole new paradigm for a sustainable supply chain.

### Our idea

As sustainability becomes increasingly important to consumers and investors, companies are seeking innovative ways to create more sustainable supply chains. Blockchain technology provides a promising solution to help companies achieve this goal by increasing transparency, accountability, and efficiency in the supply chain.

Blockchain technology is a secure, tamper-proof digital ledger that records transactions in a transparent manner. By leveraging blockchain technology, companies can create a sustainable supply chain that is transparent, secure, and efficient. This can help reduce the environmental impact of their operations, improve their reputation, and attract investors. We, therefore, are leveraging Hyperledger to create a collaborative system to address the environmental issues caused in the supply chain, whereby the use of ethical practices companies, retailers and transportation stake holders can meet sustainability demands with AI-enabled smart contracts to track whether the required criteria from right the process of production of resource to completion of the product are maintained or not.

Through the use of blockchain technology, companies can track the origin of their raw materials and ensure that they are sourced from sustainable and ethical sources and have complied with the mandatory rules posed in the smart contract. This can help reduce waste and improve efficiency in the supply chain. Additionally, blockchain technology can enable companies to collaborate more effectively with their suppliers, customers, and other stakeholders in the supply chain, leading to improved communication, reduced delays, and increased efficiency. The authenticity of the smart contract will be automatically generated from filled parameters and use of AI methodoly to verify the same.

However, to fully realize the benefits of blockchain technology, companies must address challenges such as the need for collaboration and standardization across the industry and data privacy and security concerns. Nevertheless, the potential benefits of blockchain technology for creating sustainable supply chains make it a technology worth exploring for companies looking to improve their sustainability and profitability in the long term. As sustainability becomes increasingly important to consumers and investors, companies are seeking innovative ways to create more sustainable supply chains. Blockchain technology provides a promising solution to help companies achieve this goal by increasing transparency, accountability, and efficiency in the supply chain. 
Carbon footprint tracking: Blockchain technology can be used to track and verify the carbon emissions associated with the transportation of products, enabling companies to monitor their carbon footprint and identify areas for improvement.

- Green logistics: Blockchain technology can help companies optimize logistics to reduce energy consumption and emissions. For example, by optimizing routes, reducing empty miles, and using more efficient transportation modes, companies can reduce their environmental impact.

- Sustainable sourcing: Blockchain technology can be used to track the sustainability of raw materials, such as the origin of minerals, lumber, or agricultural products. This can help companies ensure they are using sustainable and ethical sources.

- Circular economy: Blockchain technology can support the transition towards a circular economy by tracking and verifying the origin, ownership, and condition of products and materials. This can facilitate the reuse, refurbishment, and recycling of products, reducing waste and promoting resource efficiency.

- Eco-labeling: Blockchain technology can enable companies to create eco-labels that provide transparent and verified information on the environmental impact of their products, enabling consumers to make more informed purchasing decisions.

- Traceability and accountability: By providing an immutable and transparent record of transactions, blockchain technology can increase traceability and accountability in the supply chain, enabling companies to identify and address sustainability issues more effectively.


## Technology implementation

### IBM AI service(s) used

- [IBM Natural Language Understanding](https://cloud.ibm.com/catalog/services/natural-language-understanding) - Used to make the application multilingual and understand scraped documents for fetching information for smart contract generation
- [Watson Assistant](https://cloud.ibm.com/catalog/services/watson-assistant) - Used to create a personalized chatbot and to serve retailer layer with services
- [Watson Discovery](https://cloud.ibm.com/catalog/services/watson-discovery) - Used to get required information required to generate smart contracts and create analytics report and estimation for retailer layer
- [Watson Speech to Text](https://cloud.ibm.com/catalog/services/speech-to-text) - Used in chatbot and search fields
- [Watson Text to Speech](https://cloud.ibm.com/catalog/services/text-to-speech) - Used in chatbots
- List any additional [IBM AI services](https://cloud.ibm.com/catalog?category=ai#services) used or remove this line

### Other IBM technology used

- [IBM Coverlistics]() - Used to create personalized chat bot and integrate it with mobile applications at all levels
- [IBM Watson Knowledge Catalog]()  - Used to generate data for analytics and feed them to AI model for analytics purposes.

### Solution architecture

Diagram and step-by-step description of the flow of our solution:

![Video transcription/translaftion app](https://developer.ibm.com/developer/tutorials/cfc-starter-kit-speech-to-text-app-example/images/cfc-covid19-remote-education-diagram-2.png)

1. The user navigates to the site and uploads a video file.
2. Watson Speech to Text processes the audio and extracts the text.
3. Watson Translation (optionally) can translate the text to the desired language.
4. The app stores the translated text as a document within Object Storage.

## Presentation materials

### Solution demo video

[![Watch the video](https://raw.githubusercontent.com/Liquid-Prep/Liquid-Prep/main/images/readme/IBM-interview-video-image.png)](https://youtu.be/vOgCOoy_Bx0)

### Project development roadmap

The project currently has completed following phases.

- Planning
- Research and Exploration
- Mobile application design

In the future we plan to...

See below for our proposed schedule on next steps after Call for Code 2023 submission.

![Roadmap](./images/Roadmap.jpg)

## Additional details

_INSTRUCTIONS: The following deliverables are suggested, but **optional**. Additional details like this can help the judges better review your solution. Remove any sections you are not using._

### How to run the project

INSTRUCTIONS: In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.

### Live demo

You can find a running system to test at...

See our [description document](./docs/DESCRIPTION.md) for log in credentials.

---

