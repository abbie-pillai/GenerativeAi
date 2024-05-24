Summarize & highlight podcast episodes for busy listeners
Welcome to the project that is part of the course - Building AI products with OpenAI. In this project, we have built an LLM app that summarizes a podcast episode, identifies podcast guests, identifies key highlights and more!

The Problem
I'm a huge fan of podcasts and love the format as a way to gain deep insights into different industries & technologies and learn from the lived experience of people all over the world. I'm subscribed to several interesting podcasts that release 1-2 episodes a week and the problem is that it's hard to identify an episode that would appeal to me. While many episodes provide show notes, additional links and timestamps, I don't find them very helpful in truly understanding the unique aspects and making me want to listen to it! How can I make this discovery process more interesting and efficient?

Solution
We would like to generate a personalized newsletter every week that summarizes each podcast episode released in that week. It would include information about the guest on the episode, the main topics discussed as well as some highlights. It would work by collecting a list of RSS feeds from the user and on a periodic basis, process the latest episodes and generate the newsletter. This acts as a round-up of the week, provides the user with the right level of detail that allows them to decide which of the episodes are appealing and must be listened to.

Approach
We will divide the approach to building this product into three parts -

Part 1: use a Speech to Text model from OpenAI called Whisper to transcribe the podcast.
Part 2: use a Large Language Model from OpenAI to build the information extraction functionality to get insights from the podcast.
Part 3: use chatGPT from OpenAI as your coding assistant to create and deploy a front-end that allows users to experience the end to end functionality
Through this project our aim is to understand how we can approach building and deploying LLM apps that add value to users. We will also provide ideas for interesting extensions and additional functionality at several parts in the project. These are optional but we are excited to see what you might build and showcase in the Demo-Day!

Project Approach
Breaking down the development of this product into three key phases:

Part 1: Implement the use of OpenAI's Whisper, a Speech to Text model, for accurate podcast transcriptions.
Part 2: Leverage a Large Language Model (LLM) from OpenAI to establish the information extraction functionality, enabling insightful content from the transcribed podcasts.
Part 3: Employ OpenAI's chatGPT as a coding assistant to create and deploy a user-friendly front-end, allowing seamless interaction with the end-to-end functionality.
This project is designed to explore the process of building and deploying applications using Large Language Models, aiming to provide value to users.

Dependencies

typing-extensions (uninstall and reinstall): This package provides tools for working with types in Python. The commands you've used here are uninstalling the current version and reinstalling version 4.7.1.

gradio (uninstall and reinstall): Gradio is a Python library that allows you to rapidly create UIs for machine learning models. The commands you've used here are uninstalling the current version and reinstalling it.

feedparser: feedparser is a library for parsing RSS and Atom feeds. It allows you to easily extract information from syndicated web content like blogs and news articles.

transformers and accelerate: These are components of the Hugging Face Transformers library. transformers provides pre-trained models and various tools for working with natural language processing tasks, while accelerate is a library for distributed training.

openai: The OpenAI Python package allows you to interact with OpenAI's APIs, including models like GPT-3.

tiktoken: tiktoken is a Python library developed by OpenAI for counting the number of tokens in a text string without making an API call. It can be useful for managing token limits when working with OpenAI models.

wikipedia: The wikipedia package provides a simple and easy-to-use interface for interacting with Wikipedia. It allows you to retrieve information from Wikipedia pages programmatically.
