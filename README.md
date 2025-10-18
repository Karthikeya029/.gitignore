# Python/OS/Environment Secrets
.env # Configuration files where actual secrets might be stored if not using pure environment variables
.DS_Store # macOS system file

# Python Environment & Build Artifacts
__pycache__/
*.pyc
venv/ # The virtual environment directory

# Flask/Web specifics
*.log

# Crucially, never commit the file that holds the secret!
# (If you had a config.py file that stored the key, you would list it here)
