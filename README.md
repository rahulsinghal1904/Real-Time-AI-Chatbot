# Building a Fullstack AI Chatbot with Redis, React, FastAPI, and GPT

![Fullstack AI Chatbot](https://github.com/vikasharma005/Fullstack-AI-Chatbot/blob/main/docs/full-stack-chatbot-architecture.png)

## Introduction

The application utilizes the power of GPT-J-6B, a generative language model, to provide intelligent responses to user queries in real-time. I used Redis to store and retrieve chat data efficiently, React for building the user interface, and FastAPI with WebSockets to handle the backend chat server.

**Important Note:**
This project requires some basic knowledge of Python and JavaScript.

## Tools and Technologies Used

- **Language and Frameworks:**
  - Python: We will use Python as the primary language for our backend development.
  - FastAPI: A modern and fast Python web framework, ideal for building APIs and WebSockets.
  - React: Version 18 will be used to create an interactive and user-friendly chat interface.

- **AI Model:**
  - GPT-J-6B: A powerful open-source language model with 6 billion parameters, offering GPT-3 level performance on some tasks.

- **Storage:**
  - Redis: An in-memory key-value store for fast data retrieval and storage.

## Application Architecture Overview

The architecture of our AI chatbot involves multiple components working together to provide a seamless user experience. Let's take a closer look at each part:

1. **Client/User Interface**
   - We will use React v18 to create an engaging and intuitive chat user interface.
   - The chat UI will communicate with the backend through WebSockets for real-time interactions.

2. **GPT-J-6B and Huggingface Inference API**
   - GPT-J-6B is an open-source generative language model with 6 billion parameters, capable of providing advanced responses to user queries.
   - Huggingface Inference API connects with GPT-J-6B, enabling us to leverage its capabilities efficiently.

3. **Redis**
   - Redis will serve as our in-memory key-value store for storing chat data, making data retrieval and storage super-fast.
   - We will use Redis JSON to store the chat data and Redis Streams for handling real-time communication with the Huggingface Inference API.
   - For testing purposes, we will utilize a managed free Redis storage provided by Redis Enterprise.

4. **Web Sockets and the Chat API**
   - To enable real-time bi-directional communication between the client and the server, we will use WebSockets.
   - FastAPI will be used as the chat server, as it offers a fast and modern Python server for WebSockets.

## Project Phases

This intermediate full-stack software development project will guide you through the entire development process. If you prefer, you can choose specific phases based on your interests and expertise. Here's an overview of the project phases:

1. **Building APIs with Python, FastAPI, and WebSockets**
   - Learn to set up FastAPI and implement WebSockets for real-time communication.

2. **Utilizing GPT-J-6B and Huggingface Inference API**
   - Understand how to integrate GPT-J-6B and Huggingface Inference API to enable advanced language processing.

3. **Implementing Redis for Efficient Data Storage**
   - Set up Redis and leverage its powerful features for storing chat data effectively.

4. **Creating the Chat User Interface with React**
   - Develop an interactive chat interface using React v18.

5. **Bringing It All Together**
   - Integrate the frontend and backend components to create a fully functional AI chatbot.



Author: Rahul Singhal
