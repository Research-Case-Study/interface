# Hunter: Hate Speech Detection Interface

Hunter is an AI-powered interface designed to detect hate speech. This repository contains the full backend and frontend setup to run the detection system.

This project is forked from [Open WebUI](https://github.com/open-webui/open-webui).

## Installation Guide

### 1. Clone the Repository
First, clone this repository to your local machine:
```bash
git clone https://github.com/your-repo/interface.git
cd interface
```

### 2. Create a Python Virtual Environment
To ensure a clean setup, create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### 3. Install Dependencies
Install the required Python packages using:
```bash
pip install -r requirements.txt
```

## Running the Interface
To start the interface, run the following command:
```bash
python __init__.py
```

This will launch the system, allowing you to use Hunter for hate speech detection.

## Project Structure
- `frontend/` - Contains the UI components of the interface.
- `internal/` - Backend logic and API handling.
- `migrations/` - Database migrations.
- `models/` - Data models used in the application.
- `retrieval/` - Information retrieval components.
- `routers/` - API routes.
- `socket/` - WebSocket communication.
- `static/` - Static files for the interface.
- `storage/` - File storage.
- `test/` - Unit tests for the application.
- `utils/` - Utility functions.



