# GSoC-2026-End-Term-Report
<p align="center">
  <img src="assets/gsoc-logo.png" alt="Google Summer of Code" width="1000">
</p>

<p align="center">
  <img src="assets/drupal-logo.png" alt="Google Summer of Code" width="500">
</p>

## INTRO

I got the opportunity to work on **AI-Powered Knowledge Assistant for Drupal** during Google Summer of Code 2026.

From exploring Drupal's AI ecosystem for the first time to building a knowledge assistant integrated for Drupal, these few months have been an incredible learning experience. This report summarizes my GSoC journey, the work I completed, and what I learned along the way.

## Project Details & Goals

<strong>Project:</strong> <a href="https://summerofcode.withgoogle.com/programs/2026/projects/8G1nYIR8">AI Knowledge Assistant</a> <br>
<strong>Organization:</strong> <a href="https://www.drupal.org">Drupal Association</a> <br>
<strong>Mentor:</strong> <a href="https://www.drupal.org/u/azizos">Ahmed Aziz Abbassi</a> <br>
<strong>Contributor:</strong> <a href="https://www.drupal.org/u/sujal-kshatri">Sujal Kshatri</a> <br>

The goal of this project was to build an **AI-Powered Knowledge Assistant for Drupal** that can understand and retrieve information from a Drupal website and provide contextual answers using AI. The assistant is designed to make information available across a Drupal site easier to discover through natural language conversations.

The project integrates with **Drupal AI** and **AI Search** to index website content, retrieve relevant information, and provide that information to an AI model as context. This allows the assistant to generate answers based on the content available on the Drupal website.

Users can configure AI providers, models, search settings, and other components according to their requirements, while keeping the implementation aligned with Drupal's existing architecture.

<img width="1410" height="155" alt="image" src="https://github.com/user-attachments/assets/49e065cd-8bda-46c5-9e63-6d47df3dd0d5" />


## Helpful Links

* **Project Page on Drupal.org:** [AI Knowledge Assistant](https://www.drupal.org/project/ai_knowledge_assistant)
* **Project Releases:** 
* **Project Repository on GitLab:** 

## Work Done

* **Chat Interface :**
  Built the user-facing chat experience where users can ask questions and receive answers based on their Drupal content.

* **Knowledge Base & Content Indexing :**
  Implemented the workflow for indexing Drupal content so that website information can be processed and made available to the assistant.

* **AI Integration :**
  Integrated the assistant with Drupal's AI framework, allowing it to use the configured AI provider and model for generating responses.

* **Search & Vector Database Integration :**
  Connected the search and vector database components required for storing embeddings and performing similarity-based retrieval.

* **Conversation History :**
  Added support for maintaining previous messages so that the assistant can understand the context of an ongoing conversation.

* **Prompt & Context Handling :**
  Implemented the logic for combining the user's question with retrieved content and conversation history before sending it to the AI model.

## Demo
- Chat System

https://github.com/user-attachments/assets/e642ac09-36d7-4872-a0bc-77b0966dbf77

This video shows the working **Knowledge Assistant chat system** inside Drupal. It shows how a user can ask questions and get answers from the assistant based on the Drupal content. It shows the basic chat flow and how the assistant responds.

- Building the Knowledge System

https://github.com/user-attachments/assets/b57428af-eba4-4e30-ad25-fbd03436018b

This video shows the **Build and Index** feature of the Knowledge Assistant. At the beginning, there is no server or index available, and after clicking the button, they are automatically created and configured for indexing then we can see the assistant accessing my Drupal site and answering questions using the information from the site.

## Future Work

* **Performance Improvements :**
  Optimize indexing, retrieval, and response generation to make the assistant faster and more efficient.

* **User Privacy & Data Security :**
  Improve how Drupal site content and user data are handled to ensure sensitive information remains protected throughout the retrieval and AI workflow.

* **Permission-Aware Retrieval :**
  Ensure users can only retrieve information from Drupal content they are authorized to access.

* **Improved Error Handling :**
  Provide clearer error messages and better recovery when providers, models, indexing, or external services are unavailable.

* **Testing & Reliability :**
  Add more automated tests and improve coverage for different configurations and edge cases.

* **User Experience Improvements :**
  Continue improving the chat interface, conversation handling, and overall usability of the assistant.

## Acknowledgment for my Mentor

I would like to give a **special thanks to my mentor, Aziz**, for mentoring me throughout this journey and always being there whenever I needed help. He gave me the freedom to work at my own pace while making sure I always had the right guidance whenever I got stuck.

He has helped me a lot in building this module, from clearing my doubts and helping me understand the Drupal ecosystem to giving me some of the **best advice throughout the project**. I really appreciate the patience, support, and trust he showed in my work and the way he encouraged me to explore and solve problems on my own.

I am truly grateful for everything I learned from him during GSoC. This project would have been a much more difficult journey without his constant support and guidance.

## Acknowledgment for Drupal and GSOC 

I would also like to sincerely thank the Drupal community, the Drupal GSoC team, and the GSoC committee for giving me this incredible opportunity to be a part of Google Summer of Code 2026. Being able to work on a real open-source project like Drupal and contribute to such a large and welcoming community has been a great experience for me.

I am especially grateful for the support, guidance, and encouragement provided throughout the program. GSoC gave me the opportunity to learn from experienced developers, explore new areas, and work on something that can continue to be useful to the Drupal community. I am really thankful to everyone who made this journey possible and helped make my GSoC experience so memorable.

## What I Learned

GSoC 2026 has been a really big learning experience for me, both technically and personally.It gave me the freedom to experiment with my ideas and try different approaches, which I really enjoyed. Not everything worked on the first try, but experimenting with different solutions taught me a lot and helped me become more comfortable with making decisions on my own.In the beginning, I had to learn a lot about **Drupal**, its structure, development workflow, and how things are managed in a large open-source project. Working in a proper development environment also helped me understand how professional developers write, organize, and maintain their code.

One of the biggest things I learned was **debugging**. Earlier, whenever I got an error, I would sometimes just try different fixes until something worked. During this project, I learned to actually understand the error, check logs, follow the code flow, and find the real reason behind the problem.

I also learned how important **documentation** is, especially in open source. Writing things down properly makes it much easier for someone else to understand the work and continue it in the future. I also got to interact with my mentor and other Drupal contributors, which helped me improve my communication and learn how to collaborate with people working on the same project.

I would also like to thank my mentor **Aziz** once again. His guidance, patience, and feedback helped me a lot throughout the project. Whenever I was stuck or unsure about something, having someone experienced to discuss it with made things much easier.

Overall, GSoC taught me much more than just how to build a Drupal module. I learned how to work on a real open-source project, collaborate with others, debug properly, write better code, manage my time, take responsibility for my work, and most importantly, keep learning from my mistakes.


## Conclusion

I am really enjoying working on the **AI Knowledge Assistant for Drupal** during GSoC 2026. This project gave me the opportunity to explore a completely new area, work with a large open-source codebase, and turn my ideas into a working Drupal module. Understanding the requirements, debugging issues and improving the assistant, every stage taught me something new.

GSoC 2026 has been a really memorable experience for me, and I hope to continue learning, contributing, and staying connected with the open-source community.

**Thanks and Regards,**

**Sujal Kshatri**

