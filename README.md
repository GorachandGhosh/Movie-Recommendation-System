# 🎬 Movie Recommendation System

A machine learning-based **Movie Recommendation System** that recommends movies based on the similarity between movies.

The project combines a **FastAPI backend**, **Streamlit frontend**, **Scikit-learn recommendation model**, and **TMDB API** to provide an interactive movie recommendation experience.

## 🌐 Live Demo

🚀 **Try the application:**  
https://movie-recommendation-system-ep29m7t22dttd2ggqjkavr.streamlit.app/

---

## 📌 Project Overview

Finding a good movie to watch can be difficult when there are thousands of options available.

This project provides a simple recommendation system where users can select a movie and receive a list of similar movies.

The recommendation engine uses **TF-IDF vectorization and cosine similarity** to identify movies with similar textual information.

---

## ✨ Features

- 🎬 Movie recommendation based on similarity
- 🔎 Interactive movie selection
- 🖼️ Movie posters using TMDB API
- ⚡ FastAPI backend
- 🎨 Interactive Streamlit frontend
- 🤖 Machine Learning-based recommendation
- ☁️ Deployed as a live web application
- 📱 Simple and user-friendly interface

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Machine Learning & Data Processing
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorization
- Cosine Similarity

### Backend
- FastAPI
- Uvicorn

### Frontend
- Streamlit

### API
- TMDB API

### Deployment
- Render – FastAPI Backend
- Streamlit Community Cloud – Frontend

### Development Tools
- VS Code
- Git
- GitHub

---

## 🏗️ Project Architecture

```text
                ┌──────────────────────┐
                │      User            │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │    Streamlit UI      │
                │     (Frontend)       │
                └──────────┬───────────┘
                           │
                           │ API Request
                           ▼
                ┌──────────────────────┐
                │      FastAPI         │
                │      Backend         │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │ Recommendation Model │
                │ TF-IDF + Similarity  │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │ Recommended Movies   │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │     TMDB API         │
                │  Movie Posters/Info  │
                └──────────────────────┘
