# Codility Clone

A web application for solving coding challenges, inspired by Codility.

## Prerequisites
- Docker & Docker Compose
- Python 3.10
- Virtualenv

## Installation & Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/codility_clone.git
   cd codility_clone

2. **Create a Virtual Environment**
   python3 -m venv venv
   source venv/bin/activate

3. **Install dependencies**
   pip install --no-cache-dir -r requirements.txt

4. **Create environment variables file**
   cp .env.example .env
    *Edit .env to set your database credentials if needed.

5. **Build and run the services**
   docker-compose up --build

6. **Access the application**
   Open your browser and navigate to:
   http://localhost:5000