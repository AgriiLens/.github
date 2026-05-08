# AgriLens - AI-Powered Agricultural Decision Support System

<div align="center">
  <img src="https://raw.githubusercontent.com/AgriLens/agrilens-mobile-app/main/assets/logo.png" alt="AgriLens Logo" width="180"/>

  [![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
  [![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
  [![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
  [![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://tensorflow.org)
  [![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)

  **Hybrid AI Architecture for Plant Disease Detection & Advisory**

  [📱 Mobile App](https://github.com/AgriLens/agrilens-mobile-app) • [🖥️ Backend API](https://github.com/AgriLens/agrilens-backend-api) • [📄 SRS Document](./srs.pdf)
</div>

---

## Project Overview

AgriLens is a mobile-based agricultural decision support application that detects and analyzes plant diseases in strategically important crops using real-time field imagery. The system employs a hybrid artificial intelligence architecture combining Convolutional Neural Networks (CNN) for image classification and Large Language Models (LLM) for contextual advisory generation.

**Supported Crops:** Tomato | Wheat | Maize

## Key Achievements

- CNN-based disease classification with F1-Score >= 0.85
- Gemini API integration for intelligent agricultural advisory
- Offline historical data access with local storage
- Optimized UI for real-world field conditions
- Multi-language support (Turkish/English)
- Real-time weather integration and regional disease alerts

## Team

| Name | Role | GitHub |
|------|------|--------|
| Akın Mert Ak | Mobile Developer | [@username](https://github.com/username) |
| Mehmet Yasin Buğdaycı | Backend Developer | [@username](https://github.com/username) |
| Muhammed Şükrü Çiçek | AI/ML Engineer | [@username](https://github.com/username) |
| Emin Osman Atcı | Database & API Specialist | [@username](https://github.com/username) |
| Fatıma İnan | UI/UX Designer | [@username](https://github.com/username) |

**Advisor:** Prof. Dr. Meltem Huri Baturay

## Institution

**Konya Food and Agriculture University**
Faculty of Architecture and Engineering
Department of Computer Engineering
Konya, Turkey

## Technology Stack

### Mobile Application
- **Flutter** - Cross-platform UI framework
- **Dart** - Programming language
- **Hive/SQLite** - Local database for offline access
- **Firebase SDK** - Authentication & cloud storage

### Backend Services
- **FastAPI** - High-performance Python web framework
- **TensorFlow/Keras** - CNN model training & inference
- **Google Gemini API** - LLM-powered advisory generation
- **Firebase Admin SDK** - Auth & Firestore integration

### Infrastructure
- **Docker** - Containerization
- **GitHub Actions** - CI/CD pipeline
- **REST API** - Client-server communication over HTTPS

## Screenshots

<div align="center">
  <img src="https://raw.githubusercontent.com/AgriLens/agrilens-mobile-app/main/screenshots/home.png" width="200" alt="Home Dashboard"/>
  <img src="https://raw.githubusercontent.com/AgriLens/agrilens-mobile-app/main/screenshots/camera.png" width="200" alt="Camera Interface"/>
  <img src="https://raw.githubusercontent.com/AgriLens/agrilens-mobile-app/main/screenshots/result.png" width="200" alt="Diagnosis Result"/>
  <img src="https://raw.githubusercontent.com/AgriLens/agrilens-mobile-app/main/screenshots/history.png" width="200" alt="History"/>
</div>

## Repository Structure

```
AgriLens/
├── agrilens-mobile-app/     # Flutter mobile application
├── agrilens-backend-api/    # FastAPI Python backend
├── srs.pdf                  # Software Requirements Specification v1.0
└── .github/                 # Organization profile & workflows
```

## Quick Start

### Prerequisites
- Flutter SDK >= 3.16.0
- Python >= 3.9
- Docker & Docker Compose (optional)

### Backend Setup

```bash
cd agrilens-backend-api
cp .env.example .env
# Configure environment variables
docker-compose up -d --build
# API docs available at http://localhost:8000/docs
```

### Mobile Setup

```bash
cd agrilens-mobile-app
flutter pub get
flutter run
```

## System Performance

| Metric | Target | Status |
|--------|--------|--------|
| Classification F1-Score | >= 0.90 | Achieved |
| API Response Time (4G) | < 5 seconds | Achieved |
| Concurrent Users | 50+ | Tested |
| Mobile App Size | < 100 MB | Optimized |
| Model Size (TFLite) | < 20 MB | Optimized |

## Documentation

- [Software Requirements Specification (SRS)](./srs.pdf)
- [API Reference (Swagger UI)](https://api.agrilens.com/docs)
- [Mobile App Documentation](https://github.com/AgriLens/agrilens-mobile-app#readme)
- [Backend Documentation](https://github.com/AgriLens/agrilens-backend-api#readme)

## Security & Compliance

- TLS 1.2+ encryption for all communications
- API key authentication for backend access
- KVKK & GDPR compliant data handling
- No PII storage on servers
- Input validation and rate limiting

## License

This project is developed for academic and research purposes as part of the graduation project at Konya Food and Agriculture University. Submitted for TUBITAK evaluation.

## Contact

- Email: agrilens@example.com
- Website: [agrilens.github.io](https://agrilens.github.io)
- Location: Konya, Turkey

---

<div align="center">
  <sub>2026 AgriLens Development Team. All rights reserved.</sub>
</div>
