## Python Project : A Flask Web Application which displays table data and basic information for Customer Shopping data in Istanbul.


## Description
This Flask-based web application showcases how to present a table and essential details on a webpage using HTML. The table is created dynamically by fetching data from an SQLite database using Python. Utilizing Flask, a minimalistic Python web framework, the application serves the HTML content.

### Features
- Presents a dynamically generated table sourced from an SQLite database.
- Incorporates essential information on the webpage's layout.

### Prerequisites
Before running the application, make sure you have following installed:
- Python (version 3.x)
- Flask (install via `pip install flask within python`)
- SQLite3 (install via`pip install sqlite3 within python`)
- Pandas (install via `pip install pandas within python`)

### Usage
1. Clone or download this repository to your local machine
2. Clone the repository https://github.com/Chhavinder058/Project.git
3. Install the required dependencies using the command: pip install -r requirements.txt
4. Navigate to the folder where you downloaded this repository.
5. Configure the database path In the app_template_detail_2.py file, locate the database configuration section. By default, it may look like this: r"C:\Users\chhav\OneDrive - St. Clair College\DAB111 - python\Flask"
6. Change 'path/to/your/database.db' to the desired path where you want to store your database file. For example: DATABASE_PATH = "C:\Users\chhav\OneDrive - St. Clair College\DAB111 - python\Flask\Database\customer_shopping.db"
7. Run the Flask application by executing the following command:
    ```
    python app_template_detail_2.py
    ```
8. Open your web browser and go to `http://127.0.0.1:5000/#` to view the application.

### Files
- `app_template_detail_2.py`: Main Flask application file containing routes and logic.
- `templates/about.html`: HTML template file detailing the source of the data and definition of each variable.
- `templates/data_table.html`: HTML template file table webpage.
- `templates/index_links.html`: HTML template file for the main webpage containing links to other webpages.
- `Database/Dataset.csv`: The csv file containing data about the customer shopping details from Istanbul.
- `customer_shopping.db`: The database file containing the data.

### Refrences
https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset
