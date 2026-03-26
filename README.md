# Skin-Lesion-Detection-Streamlit

A streamlined web application for the real-time detection and classification of skin diseases. Built with Streamlit and powered by deep learning, this tool provides a fast and accessible way for users to analyze dermatological images.

## ┬┐ Project Overview
This repository focuses on providing a lightweight, easy-to-deploy interface for skin lesion analysis. It complement larger research projects by offering a simplified user experience for quick screening and demonstration.

## ┬┐ Features
- **User-friendly Interface**: Drag-and-drop image upload for instant analysis.
- **Deep Learning Core**: Utilizes pre-trained CNN models for high-accuracy classification.
- **Exportable Results**: Option to download analysis reports for further clinical review.

## ┬┐ Project Structure
- `src/`: Core Streamlit application and inference logic.
- `data/`: Storage for sample images and local datasets.
- `docs/`: Guides and technical documentation.

## ┬┐ Getting Started
```bash
# Clone the repository
git clone https://github.com/DinhLucent/Skin-Lesion-Detection-Streamlit.git

# Install dependencies (ensure streamlit is installed)
pip install streamlit opencv-python tensorflow
```

### Running the App
```bash
streamlit run src/app.py
```

---
*Created by DinhLucent - 2022 (Initial Scaffolding 2026)*