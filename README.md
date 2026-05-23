# ML Flow Starter

A starter template for machine learning projects.

## Setup Instructions

### 1. Create Virtual Environment

#### Windows
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
.venv\Scripts\activate
```

#### Linux/macOS
```bash
# Create virtual environment
python3 -m venv venv

# Activate virtual environment
source venv/bin/activate
```

### 2. Update requirements.txt

#### Install dependencies from requirements.txt
```bash
pip install -r requirements.txt
```

#### Add a new package and update requirements.txt
```bash
# Install a package
pip install <package_name>

# Update requirements.txt with installed packages
pip freeze > requirements.txt
```

#### Generate requirements.txt from current environment
```bash
pip freeze > requirements.txt
```

### 3. .gitignore Configuration

Add the following to your `.gitignore` file to exclude virtual environment and other common files:

```
# Virtual Environment
venv/
env/
ENV/
.venv

# Python
__pycache__/
*.py[cod]
*$py.class
*.so
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
wheels/
*.egg-info/
.installed.cfg
*.egg

# IDE
.vscode/
.idea/
*.swp
*.swo
*~

# OS
.DS_Store
Thumbs.db

# Environment variables
.env
.env.local

# Jupyter Notebook
.ipynb_checkpoints/

# MacOS
.AppleDouble
.LSOverride
```

## Quick Start

1. Clone the repository
2. Create and activate virtual environment (see section 1 above)
3. Install dependencies: `pip install -r requirements.txt`
4. Start developing!
