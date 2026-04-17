# 🌈✨ MARIA — Video-Powered AI Learning for Kids

MARIA is a magical AI teaching assistant built for children aged 6-12. It combines conversational learning, curriculum-aware tutoring, retrieval-augmented generation (RAG), and short AI-generated educational videos to make lessons more visual, interactive, and memorable.

Instead of only giving text answers, MARIA creates colourful animated learning clips using ZeroScope V2 so children can see concepts in action.

## 🎬 What Makes MARIA Special?

* Generates short educational videos for every lesson or question
* Uses ZeroScope V2 to create bright, kid-friendly animations
* Gives visual explanations with stories, analogies, and simple language
* Supports curriculum-based learning by board, class, and subject
* Uses RAG with FAISS and embeddings for more accurate lesson support
* Includes teacher personas for different learning styles
* Built with Gradio for a fun and colourful interface
* Designed for Google Colab with T4 GPU support

## 🧠 How Video Learning Works

When a child asks a question, MARIA:

1. Understands whether the question matches the current lesson
2. Retrieves relevant knowledge from the curriculum
3. Generates a simple child-friendly explanation
4. Creates a matching animated video prompt
5. Uses ZeroScope V2 to render a short visual learning clip
6. Displays the explanation and video together

This helps children understand topics faster because they can both read and watch the concept.

## 🚀 Features

* Qwen3-4B INT4 for lightweight AI responses
* ZeroScope V2 text-to-video generation
* Sentence-transformers for semantic search
* FAISS-powered knowledge retrieval
* Curriculum preload and caching
* Multi-topic lesson progression
* Interactive Gradio chatbot
* Kid-friendly animations, colours, and UI
* Safe and simple educational responses

## 📦 Tech Stack

* Python
* Gradio
* Transformers
* Qwen3-4B
* Diffusers
* ZeroScope V2
* Sentence Transformers
* FAISS
* Pandas
* PyTorch

## ▶️ How To Run

1. Open the notebook in Google Colab
2. Switch runtime to GPU (T4 recommended)
3. Run all setup cells
4. Wait for MARIA and ZeroScope V2 to load
5. Launch the Gradio app
6. Start learning with animated video explanations

## 🔗 Open in Colab

https://colab.research.google.com/github/buildwithsupratim/videolearning/blob/main/video_learning.ipynb

## 🎯 Ideal For

* Kids aged 6-12
* Visual learners
* Interactive education projects
* AI tutoring demos
* EdTech experiments
* Curriculum-based classroom support

MARIA transforms traditional text-based tutoring into a colourful visual learning adventure for children.
