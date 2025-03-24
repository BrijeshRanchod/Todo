# Clone the repository
git clone https://github.com/your-username/TodoApp.git

# Navigate into the project directory
cd TodoApp

# Create a virtual environment
python3 -m venv venv

# Activate the virtual environment
# On macOS/Linux
source venv/bin/activate

# On Windows
# venv\Scripts\activate

# Install the dependencies from requirements.txt
pip install -r requirements.txt

# Set up the database by running the app (this will create the necessary tables)
python3 todo.py

# Run the Flask app
python3 todo.py
