# 🌍 AI Earth Observation Intelligence Platform

## 🚀 AI-powered satellite imagery analysis for urban growth, environmental monitoring, and disaster management.

![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)
![FastAPI](https://img.shields.io/badge/FastAPI-0.104.0-green.svg)
![React](https://img.shields.io/badge/React-18.2.0-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-2.1.0-red.svg)

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview
This platform leverages Deep Learning (Vision Transformer & SegFormer) to analyze satellite imagery for:
- Urban growth monitoring
- Environmental change detection
- Natural disaster assessment

## ✨ Features
- 🏙️ Urban Growth Analysis & Prediction
- 🌿 Environmental Monitoring & Assessment
- 🌊 Natural Disaster Detection & Response
- 📊 Real-time Geospatial Analytics
- 🤖 AI-Powered Image Segmentation
- 🗺️ Interactive Map Visualizations
- 📄 Automated Report Generation

## 🛠️ Tech Stack
### Backend
- Python 3.11+ / FastAPI
- PostgreSQL with PostGIS
- PyTorch & Transformers
- Google Gemini API

### Frontend
- React 18+
- TailwindCSS
- Leaflet/Mapbox
- Recharts

## 📁 Project Structure


## 🚀 Quick Start

### Prerequisites
- Python 3.11+
- Node.js 18+
- PostgreSQL
- Docker (Optional)

### Installation
```bash
# Clone repository
git clone https://github.com/vishakha2121/AI-Earth-Observation-Intelligence-Platform.git

# Backend setup
cd backend
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt

# Frontend setup
cd ../frontend
npm install

# Database setup
cd ../database
psql -U postgres -f init.sql

# Environment variables
cp .env.example .env
# Edit .env with your configurations

# Backend
uvicorn main:app --reload

# Frontend
npm start

# Docker (All services)
docker-compose up -d