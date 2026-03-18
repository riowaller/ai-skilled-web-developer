# CIT 94: Course Revision Tracker

## Course Title & Description Revision

| **Section** | **Current Text** | **Proposed Text** | **Rationale for Change** |
| :--- | :--- | :--- | :--- |
| **Course Title** | Node.js | **AI Web Workflows** | Reflects a shift from a specific runtime (Node) to a broader architectural competency in AI integration and automation. |
| **Catalog Description** | This course covers server-side JavaScript using Node.js... focusing on Express, APIs, and asynchronous programming. | This course provides hands-on instruction in building AI-integrated web applications. Students will learn to build backends that communicate with Large Language Models (LLMs) via APIs, implement RAG (Retrieval-Augmented Generation), and deploy automated AI workflows. | Modernizes the backend focus to include "Agentic" workflows and API-driven AI features. |
| **Units/Hours** | 3.0 Units | **4.0 Units** (Lecture: 3.0 / Lab: 1.0) | Increased units to account for the technical complexity of API orchestration, vector databases, and security. |
| **Prerequisite** | CIT 93 (JavaScript) | **CIT 93 (JavaScript)** | Ensures students have the asynchronous programming foundation required to handle streaming API responses. |

## Course Objectives Revision

| **Obj #** | **Proposed Text** | **Rationale for Change** |
| :--- | :--- | :--- |
| **1** | **Design and implement a secure server-side environment to handle AI API requests.** | Establishes the "Backend" foundation needed for AI communication. |
| **2** | **Utilize Asynchronous Programming to manage streaming responses from LLMs.** | Essential for modern AI user experiences (real-time text generation). |
| **3** | **Implement RAG (Retrieval-Augmented Generation) using vector databases.** | Teaches students how to connect AI models to custom, private datasets. |
| **4** | **Orchestrate Multi-step AI Workflows using function calling and tool-use.** | Moves beyond simple "Chat" into "Agentic" tasks and automation. |
| **5** | **Implement validation layers to audit AI output for reliability and security.** | Focuses on the engineer's responsibility for safety and accuracy. |

## Lecture & Lab Content Revision



| **Topic Area** | **Proposed Sub-topics** | **Rationale for Change** |
| :--- | :--- | :--- |
| **Backend Architecture** | RESTful APIs, Environment Variables, and API Security (CORS/JWT). | The "Mechanical Shop" of secure server setup. |
| **API Orchestration** | OpenAI/Anthropic SDKs, Prompt Templates, and Structured JSON Output. | Programmatically communicating with AI models. |
| **Memory & Context** | Embeddings, Semantic Search, and Vector Databases (Pinecone/Supabase). | Giving AI the ability to "remember" and query specific documents. |
| **Agentic Logic** | Function Calling, Tool Use, and Recursive Logic loops. | Building apps that "decide" which code to execute based on AI logic. |
| **Final Project** | **The AI System Defense:** Students build an AI-powered app and verbally explain the data flow in a technical interview. | Validates that the student understands the "black box" of their AI integration. |

## Assignments & Methods of Evaluation Revision

| **Section** | **Current Text** | **Proposed Text** | **Rationale for Change** |
| :--- | :--- | :--- | :--- |
| **Skill Demonstration** | Creating server-side scripts and API endpoints. | **Technical Interview (Capstone):** Students must explain the lifecycle of an AI request, from prompt to vector search to final response. | Ensures the student can navigate complex backend data flows without relying on AI-generated "black boxes." |
| **Project Work** | Building a basic Node.js application. | **AI Integration Log:** Students must document the prompting strategies used to build their API logic and how they validated the AI output. | Emphasizes the "Human-in-the-Loop" engineering mindset. |