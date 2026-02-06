# Setup and Installation Guide
#
# This file contains step-by-step instructions for setting up the project
#
# Prerequisites:
# - Python 3.8 or higher
# - pip (Python package manager)
# - Node.js and npm (for frontend development, optional)
# - Git for version control
#
# Installation Steps:
#
# 1. Clone the repository
#    git clone <repository-url>
#    cd MOVIE RECOMEND
#
# 2. Create Python virtual environment
#    python -m venv .venv
#
# 3. Activate virtual environment
#    Windows: .venv\Scripts\activate
#    macOS/Linux: source .venv/bin/activate
#
# 4. Install dependencies
#    pip install -r requirements.txt
#
# 5. Setup environment variables
#    cp .env.example .env
#    Edit .env with your configuration (database URL, secret keys, etc)
#
# 6. Initialize database
#    python -c "from backend.app import create_app; app = create_app(); app.app_context().push()"
#    python -m flask db upgrade
#
# 7. Load sample data (optional)
#    python scripts/load_data.py
#
# 8. Run backend server
#    python backend/app.py
#    Server will start at http://localhost:5000
#
# 9. Run frontend (in another terminal)
#    Open frontend/index.html in a web browser
#    OR use a simple HTTP server: python -m http.server 3000 -d frontend
#
# 10. Run tests
#    pytest tests/
#
# Development Workflow:
# - Make changes to code
# - Run tests to verify changes
# - Backend auto-reloads in development mode
# - Frontend auto-refreshes in browser
#

