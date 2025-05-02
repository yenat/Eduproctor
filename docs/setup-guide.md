# EduProctor Setup Guide

## 1. Prerequisites

### System Requirements
- **Operating System**: Ubuntu 20.04+ / macOS 12+ / Windows 10+
- **Node.js**: v18.x or higher
- **Python**: 3.9+ with pip
- **Docker**: 20.10+ and Docker Compose
- **Cloud Account**: AWS or Azure (for production deployment)

### Accounts Needed
- GitHub account (for repository access)
- Cloud provider account (AWS/Azure)
- Container registry (Docker Hub/GitHub Container Registry)

## 2. Installation

### Frontend Setup
```bash
# Clone repository
git clone https://github.com/yenat/EduProctor.git
cd EduProctor/frontend

# Install dependencies
npm install

# Configure environment
cp .env.example .env

# Start development server
npm run dev