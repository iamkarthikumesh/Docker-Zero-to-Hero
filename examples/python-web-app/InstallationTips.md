# 1. Update packages and install Python + venv tools
```bash

sudo apt update


sudo apt install python3 python3-pip python3-venv -y

# 2. Create a virtual environment
```bash
python3 -m venv venv

# 3. Activate the virtual environment
source venv/bin/activate

# 4. Install Django
pip install --upgrade pip
pip install Django==5.2.5

# 5. Verify Django installation
django-admin --version

# 6. (Optional) Reactivate venv in new sessions
# source venv/bin/activate

# 7. (Optional) Exit venv
# deactivate
