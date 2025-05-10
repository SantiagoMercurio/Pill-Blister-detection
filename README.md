# 💊 Pill Blister Detector

A full-stack application for detecting individual pills in pharmaceutical blister packs using a YOLOv8 deep learning model and a modern frontend built with Vite + React.

---

## 🚀 Project Overview

This project aims to:
- Train a YOLOv8 model to detect pills in blister packs.
- Provide a RESTful API for image inference using FastAPI.
- Present an intuitive frontend where users can upload images and visualize detected pills.

---

## 🗂️ Project Structure

```bash
pill-blister-detector/
├── backend/      # FastAPI app serving the trained model
├── dataset/      # Images and annotations (if public)
├── frontend/     # Vite + React web interface
├── training/     # YOLOv8 training scripts and configs
├── README.md
├── .gitignore
└── requirements.txt

