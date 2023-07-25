## Requirements

- Python 3.7 or higher
- Flask
- Flask-SQLAlchemy
- Flask-Migrate

## Installation

1. Clone the repository to your local machine:

2. Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate # On Windows use venv\Scripts\activate

3. Install the required dependencies:
pip install -r requirements.txt

4. Set up the database:
flask db init
flask db migrate
flask db upgrade

## Usage

1. Run the application:

